# photo-search-assistant

An AI-powered photo search tool for newsrooms. Paste in a headline or story description, pick a story type, and get smart search term suggestions — routed directly to AP Newsroom, Getty Images, and Reuters Connect.

---

## Setup

1. **Download** `photo-search-v2.html`
2. **Open it** in Chrome (just double-click the file — no server or install needed)
3. **Add your API key** — click the `⚙ API Key` link at the bottom of the page, paste in the Anthropic API key you were given, and hit Save
4. **Log in** to AP Newsroom, Getty Images, and Reuters Connect in your browser first (the tool opens tabs, so you'll need active sessions)

That's it. Your key is saved in your browser locally and is never shared.

---

## Usage

| What to do | How |
|---|---|
| Get AI suggestions | Paste a headline → pick story type → click **Suggest terms** (or press `Enter`) |
| Search a term | Click any chip to open it across all selected sources |
| Open everything | Click **Open all ↗** to open every suggested term at once |
| Copy a term | `Cmd`+click (Mac) or `Ctrl`+click (Windows) a chip to copy the text |
| Recent news | Check **Recent only** to sort results by newest instead of best match |
| Adjust sources | Toggle AP / Getty / Reuters checkboxes on/off |
| Update your key | Click `⚙ API Key` at any time |

**Chip colors** tell you where a term will search:
- 🔴 · 🔵 · 🟠 — AP + Getty Editorial + Reuters (wire/news terms)
- 🔵 only — Getty Creative (illustrative/stock)
- 🔵 + both — Getty Editorial + Creative (conceptual)

**⚠ Verify badge** — some chips are flagged when the AI is uncertain whether a person's role is still current. Always double-check before publishing.

---

## Sources

- [AP Newsroom](https://newsroom.ap.org) — editorial wire photos
- [Getty Images](https://gettyimages.com) — editorial and creative/stock
- [Reuters Connect](https://reutersconnect.com) — editorial wire photos

---

## Cost

This tool uses the [Anthropic Claude API](https://console.anthropic.com), billed per search (~$0.007/search). A busy team of 5 typically runs $10–30/month. Set a spend cap in the Anthropic console under **Billing → Spend limits** to avoid surprises.
