# Majoon-e-Asar-e-Khass — 7 Day Trial Pack (Landing + Checkout)

## Overview
Simple static landing page with integrated checkout modal (Netlify Forms) and Razorpay payment link.
This site is hosted on Netlify and served from this GitHub repository.

## Files
- `index.html`  — Main landing page (includes modal checkout form and JS to submit form + redirect to payment).
- `style.css`   — Styles used by the page.
- `checkout.html` / `thankyou.html` — (Not used if modal is in index.html)
- `README.md`   — This file.
- Assets (images & video):  
  - `ayushvardhan-bottle.jpg.jpg`  
  - `ayushvardhan-herbs.jpg.jpg`  
  - `ayushvardhan-review.jpg.jpg`  
  - `ayushvardhan-usage.jpg.jpg`  
  - `Buy now – Limited stock available!.mp4`

> **Note:** Filenames above must match exactly (case-sensitive). If you rename images (recommended: remove double `.jpg`), update `index.html` accordingly.

## Netlify / Deployment
1. Connect this repository to Netlify (or use drag & drop).  
2. For a static site (this repo), set **Publish directory** = `/` (root). No build command required.
3. Netlify automatically enables HTTPS.

## Netlify Forms
- The checkout form in `index.html` uses Netlify Forms (`data-netlify="true"`).  
- Submitted orders appear in Netlify dashboard → Site → Forms → `order`.  
- If you do not see submissions, check Netlify Forms settings or ensure the site is deployed via Netlify (not just local).

## Payment
- Payment is handled via a Razorpay payment link:  
  `https://rzp.io/rzp/6iSAna5`  
- The modal form submits order details (name, mobile, address, state, pincode) to Netlify, then redirects user to this link.

## How to change Razorpay link
- Open `index.html` and find the constant: `const RAZORPAY_LINK = "https://rzp.io/rzp/6iSAna5";`  
- Replace with your new link and commit → Netlify will redeploy.

## Quick troubleshooting
- Images not showing → check exact filenames in repo root and update `index.html`. Linux servers are case-sensitive.
- Form not submitting → ensure site is deployed on Netlify (Netlify Forms works only when served from Netlify).
- If modal doesn't open → open browser console (F12) and share errors.

## Recommended future improvements
- Rename image files to remove duplicated extensions (e.g., `ayushvardhan-bottle.jpg`) and update `index.html`.
- Add `favicon.png` in root and add `<link rel="icon" href="favicon.png">` in `<head>`.
- Optional: move assets to an `assets/` folder and change `src` paths in HTML.

## Contact / Owner
- Owner: Shahalam Ansari  
- WhatsApp: +91-XXXXXXXXXX (replace in code / site where needed)

