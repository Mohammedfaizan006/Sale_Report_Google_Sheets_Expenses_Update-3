SALE REPORT — ANDROID-FRIENDLY APP

Files:
- index.html: the app
- manifest.json: installable web app settings
- sw.js: offline cache
- README.txt: these instructions

HOW TO USE ON ANDROID
1. Put these files on a static HTTPS host (for example GitHub Pages, Netlify, or another trusted static host). Keep index.html, manifest.json and sw.js together in the same folder.
2. Open the hosted HTTPS address in Chrome on your Android phone.
3. Open Chrome's ⋮ menu and choose "Install app" or "Add to Home screen".
4. Launch the Sale Report icon from your home screen.

FEATURES
- Tap a menu item and enter quantity/date to record a sale.
- Automatic line total (quantity × unit price).
- Daily totals and best seller.
- Monthly revenue, item count, best seller, product performance, and daily revenue bars.
- Sales history, filtering, delete entry, CSV export for Excel/Google Sheets.
- Editable menu prices.
- JSON backup/restore.

IMPORTANT
- This is an installable Progressive Web App (PWA), not a signed APK file.
- Sales are stored locally in the browser on that device. Export backups regularly; clearing browser storage can erase data.
- Extra Pav starts at ₹0 because its price was not visible in the supplied menu. Set the price in Menu before recording sales.
- It is designed to be mobile-first. Hosting on HTTPS is needed for the install prompt and offline caching.
