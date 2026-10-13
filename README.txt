TRADING JOURNAL PRO — CUSTOM VERSION 2.0

Fields implemented:
- Asset: XAUUSD, EURUSD
- Direction: BUY, SELL
- Lot Size
- Entry Price
- Exit Price
- P&L ($), manually entered as positive/negative/zero
- Six-item strategy checklist exactly as provided
- Mental State (Entry), Mental State (During Trade), Mental State (Exit)
- Optional Trade Notes / Mistakes
- Before-entry chart screenshot and after-exit chart screenshot

Analytics:
- Net P&L, win rate, total trades, profit factor, average win/loss
- Current streak, maximum losing streak
- Asset breakdown, checklist completion statistics
- Search, filter, view details, edit and delete trades
- CSV export (screenshot presence flags only) and JSON backup/restore (includes actual screenshot image data)

IMPORTANT:
- This app uses browser local storage. Records are separate on iPhone and Windows; no sync.
- Screenshots are resized before storage. Browser storage limits still apply. Export JSON backups regularly.
- CSV contains the journal fields and flags showing whether screenshots exist; the actual images are retained in JSON backup.
- P&L is manual, as requested. No broker P&L/lot calculation is performed.
- GitHub Pages hosts the application code publicly. Never commit personal trade data or screenshots to the repository.

Windows preview:
1. Extract ZIP and open index.html in Chrome/Edge.
2. For PWA service-worker/offline behaviour, publish via HTTPS (e.g. GitHub Pages); file:// preview is for testing the journal functionality.

iPhone install:
1. Upload index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png to a GitHub repository root.
2. Settings -> Pages -> Deploy from a branch -> main -> /(root) -> Save.
3. Open the published HTTPS URL in Safari on iPhone.
4. Share -> Add to Home Screen.
