# PocketPilot — Android offline-first expense tracker

## What's included
- Monthly allowance plan: ₹2,000
- Suggested allocation: canteen ₹900, personal ₹300, unexpected ₹300, savings target ₹500
- Starting emergency fund: ₹3,000 (editable)
- Add/delete expenses, weekly and monthly views, category charts, CSV export
- Expense data stored locally in the browser on this device
- Service worker caches the app shell for offline use after the first successful visit

## Install on Android
A Progressive Web App must be served from HTTPS (or localhost) for installation and offline service-worker support.

1. Upload the contents of this folder to an HTTPS static host you control (for example, a private GitHub Pages repository/site or another static hosting provider).
2. Open the resulting HTTPS site in Chrome on your Android phone.
3. Tap Chrome's three-dot menu → **Install app** or **Add to Home screen**.
4. Open PocketPilot once while online. After it has loaded, the app shell is cached and can open offline.

## Data and privacy
- Expense entries are stored in this browser's localStorage; they are not sent to a server by this app.
- Clearing Chrome site data, using a different browser/profile, or changing phones can remove access to the saved entries.
- Use **Export CSV** regularly and keep the exported file somewhere safe.
- This app does not connect to UPI, bank accounts, or make payments.
- The ₹500 savings figure is a planning target, not a real bank transfer or a verified balance.

## Important note about weekly periods
Week 1–5 are calendar-month blocks: days 1–7, 8–14, 15–21, 22–28, and 29–31. Monthly category totals use the current calendar month.
