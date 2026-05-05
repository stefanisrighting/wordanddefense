# Word & Defense — Bible in a Year Apologetics Planner

## Files included
- `app.html` — The full PWA planner app
- `landing.html` — Sales/marketing landing page
- `manifest.json` — PWA manifest (enables "Add to Home Screen")
- `README.md` — This file

---

## How to deploy & sell

### Step 1 — Add app icons
You need two PNG icons for the PWA to install properly:
- `icon-192.png` (192×192px)
- `icon-512.png` (512×512px)

Design these in Canva using a cross, open book, or shield motif.
Place them in the same folder as your app files.

### Step 2 — Host on GitHub Pages (free)
1. Create a GitHub account at github.com
2. Create a new repository named `wordanddefense` (or any name)
3. Upload all files (app.html, landing.html, manifest.json, icons)
4. Go to Settings → Pages → Source: main branch → Save
5. Your app will be live at: `https://yourusername.github.io/wordanddefense/app.html`
6. Your landing page: `https://yourusername.github.io/wordanddefense/landing.html`

### Step 3 — Set up payment (Gumroad recommended)
1. Create a free account at gumroad.com
2. Create a new product → Digital product → $9 price
3. In the product description, paste your landing page URL
4. For the delivery file, upload a PDF or text file with:
   - Your GitHub Pages app URL
   - Instructions for installing as a PWA
5. Connect Stripe or PayPal for payouts

### Step 4 — Update the landing page
In `landing.html`, find all instances of `href="#"` on the CTA buttons and replace with your Gumroad product link.

### Step 5 — Promote
- Share on Facebook Christian groups
- Post on Instagram/TikTok with apologetics hashtags
- Submit to Christian app directories
- List on Etsy as a digital product (link to your Gumroad)

---

## PWA Installation instructions for customers

### iPhone / iPad
1. Open the app link in Safari (must be Safari, not Chrome)
2. Tap the Share button (box with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add" — the app appears on your home screen

### Android
1. Open the app link in Chrome
2. Tap the 3-dot menu (top right)
3. Tap "Add to Home Screen" or "Install app"
4. Tap "Add"

### Desktop
1. Open in Chrome or Edge
2. Look for the install icon in the address bar (computer with arrow)
3. Click "Install"

---

## Customization tips
- To change the price: edit `landing.html` — search for "$9"
- To change the app name: edit `app.html` and `manifest.json` — search for "Word & Defense"
- To add more weeks: the app auto-generates all 52 weeks from the book schedule in `app.html`
- To change colors: edit the `:root` CSS variables at the top of each file

---

## Support
The app stores all user data in browser localStorage — completely private, no server needed.
