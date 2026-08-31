# Coinlook Global V2
Responsive static frontend for GitHub Pages.

## Stack
- HTML5
- CSS3 (responsive desktop/mobile)
- Vanilla JavaScript (ES6)
- SVG/CSS charts and UI graphics

## Run locally
Open `index.html` or run: `python -m http.server 8080`

## GitHub Pages
Upload all files so `index.html` is in repository root. Deploy `main` + `/(root)`.

## Production APIs still needed
- Market prices / candles / order book: exchange market-data REST + WebSocket
- Trading execution: licensed exchange/liquidity provider backend API
- Auth/KYC/2FA: secure backend + KYC provider
- Deposit/withdrawal/custody: wallet/custody provider
- User ledger/history/referrals: backend database

Never place secret API keys, private keys, or wallet seeds in frontend files.
