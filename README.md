# SafeDrive — premium static car rental website

A responsive, single-page marketing website built with HTML, CSS and vanilla JavaScript. The design direction is an original forest-green / warm-sand / coral visual identity for a Mangaluru car rental and taxi business.

## Files
- `index.html` — page content and sections
- `style.css` — responsive styles
- `script.js` — mobile menu, service tabs, date validation, fleet filters and WhatsApp enquiries

## Run locally
Extract the ZIP and open `index.html` in a modern browser. Internet access is needed for the remote images and Google Fonts.

## Customize before publishing
1. In `script.js`, replace `WHATSAPP_NUMBER = "919876543210"` with the actual WhatsApp number in country-code + digits format.
2. In `index.html`, update phone, email, location, fleet, rental prices, destinations and policies.
3. Replace sample car and destination images with photos you own or have permission to use.
4. Check that all stated services and tax/document information match the business. Sample prices are placeholders.

## Static-site limitations
The booking form sends a prefilled enquiry to WhatsApp; it does not save bookings to a database, authenticate customers or process payments. Tax/document sections are informational and do not verify official records or submit tax payments.

## GitHub Pages
Upload `index.html`, `style.css`, `script.js`, and `README.md` to the root of a GitHub repository. Under Settings → Pages, deploy from the `main` branch and `/ (root)`.
