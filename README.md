# Coinlook Global responsive crypto UI prototype

Open `index.html` in a browser.

Implemented frontend interactions:
- Desktop + mobile responsive layouts
- Home, Markets, Spot Trade, Futures, Assets, Profile, Earn, More
- Market tabs, quote filters, favorites, market search
- Click market pair -> trade screen
- Buy/Sell switch and order total calculation
- Deposit, login, signup, 2FA, referral, settings modals
- Mobile bottom navigation + desktop top navigation

Production API integration points:
1. Public market data REST/WebSocket
2. Candlestick/OHLC data
3. Authentication/KYC backend
4. User balances and ledger
5. Deposit address generation + blockchain confirmation webhooks
6. Withdrawals with risk controls and 2FA
7. Spot/futures order management and matching/liquidity provider connection
8. Referral and rewards engine
9. Notifications

Never put exchange API secrets/private keys in frontend code.
