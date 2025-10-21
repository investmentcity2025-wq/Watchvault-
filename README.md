
WatchVault — Watch Investments (Demo)
=====================================

This is a frontend-only demo app (React + Vite). It simulates watch investments in RM.
**It does NOT process real payments.** Admin confirms payments manually to credit balances (simulation).

Admin credentials (pre-set):
- Email: investmentcity2025@gmail.com
- Password: 232435Qis#

How to run locally:
1. Install Node.js (v18+)
2. npm install
3. npm run dev
4. Open http://localhost:5173

Deploy to Vercel (Upload method from mobile):
1. Go to https://vercel.com and sign in (create account if needed).
2. From dashboard, choose "New Project" -> "Import Project" -> select "Upload" or "Drag & Drop" and choose the extracted WatchVault folder.
3. Vercel will detect Vite and deploy automatically. Wait ~1-2 minutes.
4. After deploy, open the generated URL.

Notes:
- Data is stored in localStorage of the browser.
- Admin can add watches, view pending top-up requests, confirm payments (simulation) and update QR content.
