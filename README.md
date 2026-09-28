# XAU/USD 14-Day Challenge Tracker V3

Mobile-first tracker for a 14-day XAU/USD trading challenge.

## V3 features

- Current-balance-based daily compound target
- $60 → $1,000 challenge dashboard
- Required daily profit and per-trade target
- Actual equity vs mathematical target chart
- Signal-group tracker
- BUY/SELL, entry, SL, TP, lot size
- Took signal / skipped signal
- Followed signal exactly / execution differed
- Signal outcome vs your actual P/L
- My trading performance statistics
- Signal-group performance statistics
- Win rate, profit factor, streaks and max drawdown
- 14-day daily breakdown
- Export/import JSON backups
- Reset challenge
- Automatically attempts to migrate data from the previous V2 localStorage key

## Deploy on GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` and this `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.
7. Open the generated GitHub Pages URL on your iPhone.
8. In Safari choose **Share → Add to Home Screen**.

## Important data note

The tracker stores data in your browser's localStorage. Export a JSON backup regularly. Clearing browser/site data can remove your local challenge data.

The app is a tracking/calculation tool. It does not provide trading signals or guarantee that the challenge target is achievable.
