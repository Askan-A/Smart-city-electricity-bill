# SmartCity — Electricity Bill Demo (Static)

This is a static demo site for paying electricity bills (client-side simulation).
It contains:

- `index.html` — Home + Login (email + password)
- `dashboard.html` — Account dashboard showing CCC number, meter number and transaction history
- All data is stored in `localStorage` for demo purposes.

## Demo Credentials
- `user@example.com` / `pass123` (Asha Patel — CCC-1001)
- `raj@smartcity.com` / `raj2025` (Raj Kumar — CCC-2077)

## How to use
1. Create a new GitHub repository (public or private).
2. Drag & drop these files into the repo (or upload ZIP).
3. Enable GitHub Pages (Settings → Pages) and choose the main branch root.
4. Visit the published URL.

> ⚠️ **Important:** This is a demo. For production use you must:
> - Implement a secure backend (authentication, password hashing).
> - Store transactions server-side (database).
> - Integrate a secure payment gateway (Razorpay / PayU / Stripe).
> - Use HTTPS and follow PCI/DIP compliance when handling payments.
