# Prophet Capital — Website

A high-end, 3D/interactive cash-homebuyer website for **Prophet Capital** (an XDA Enterprise company).

## Pages
- `index.html` — main site: WebGL hero (Three.js), instant cash-offer calculator, opt-in lead form, content modals
- `privacy.html` — Privacy Policy (incl. mobile/SMS data practices)
- `terms.html` — Terms of Use & SMS Policy

## Features
- Real-time 3D scene, custom cursor, scroll-driven animations
- Interactive instant-offer estimator
- A2P 10DLC / CTIA-compliant SMS opt-in (optional unchecked consent, STOP/HELP, message-type/frequency/rate disclosures)
- Lead form wired to Web3Forms (delivers submissions by email)

## Run locally
```bash
python3 -m http.server 4321
```
Then open http://localhost:4321

## Notes
- Static site — no build step. Pure HTML/CSS/JS with Three.js via CDN.
- Contact details and the lead-delivery email are placeholders to be finalized before launch.
