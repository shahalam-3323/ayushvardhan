Majoon-e-Asar-e-Khass — Google Sites / Static Landing Pack
---------------------------------------------------------

Files included:
- index.html       -> Main landing HTML (static)
- style.css        -> Styles for the landing page
- assets/          -> Product images and video (if available)
- README.txt       -> This file

Quick usage options (choose one):

OPTION A — Host as static site (recommended)
1. Upload the entire folder to any static host (Netlify, Vercel, Surge, GitHub Pages).
2. Your index.html will serve as the landing page URL. Share that URL with leads.
3. The Google Form is embedded (uses provided form). Razorpay link set to: https://rzp.io/rzp/6iSAna5

OPTION B — Use with Google Sites (two ways)
B1 — Embed via URL (if you host index.html somewhere):
   - Host index.html (see Option A)
   - In Google Sites, Insert -> Embed -> By URL -> paste hosted page URL

B2 — Embed using "Embed Code" (limited):
   - Google Sites sanitizes many HTML tags and may not accept a full page.
   - Alternative: Upload images & video to Google Drive, update index.html image src with public Drive links and host the page, then Embed via URL.

How to replace images and video:
- If you want to use your own images hosted elsewhere, update the <img src="..."> paths in index.html.
- If using Google Drive, make files public and use the drive direct link (or host externally).

Google Form behavior:
- The form is the provided form ID (short link). Google Forms will show a "Submit another response" and may not auto-redirect.
- Best practice: In form's confirmation message, include the Razorpay link and instructions to complete payment immediately.

Important notes:
- The page uses only simple HTML/CSS — no server-side code. For automated order confirmation/payment matching you'll need to implement a server or use Razorpay webhooks.
- Keep the Razorpay link private and monitor payments manually to reconcile orders with form responses.

If you want, I can:
- Create a public hosted version (I can prepare the static files — you will still need to host via Netlify/GitHub Pages or I can give step-by-step hosting help)
- Generate a ZIP file for direct download (I have created it already).

Razorpay payment link used in this pack:
https://rzp.io/rzp/6iSAna5

Google Form (short URL provided):
https://forms.gle/FLGfjSiCaFBY4PL96