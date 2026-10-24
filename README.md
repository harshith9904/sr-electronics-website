# S.R. Electronics & Home Appliances — website

Single-page site for S.R. Electronics & Home Appliances, Mehdipatnam, Hyderabad.
Live at https://sr-electronics-hyd.netlify.app

## Files
- `index.html` — the whole site: styles at the top, content in the middle, animations at the bottom.
- `assets/sr-logo.png` — original logo (also the browser-tab icon).
- `assets/sr-logo-dark.png` — light version of the logo for the dark design.

## Things you may want to change
- **WhatsApp number:** `var SR_WHATSAPP = '919573162285';` near the top of the script in `index.html`.
- **Prices:** search `index.html` for `Starting from`.
- **Phone numbers / address / hours:** in the "Visit" section and the footer of `index.html`.

## Preview locally
```
python3 -m http.server 8765
```
then open http://localhost:8765

## Publish
Drag this folder onto the project's **Deploys** page on Netlify.
