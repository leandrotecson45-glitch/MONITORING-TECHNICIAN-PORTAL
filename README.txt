OW MONITORING PORTAL

Upload these files to Vercel or GitHub Pages:
index.html
sw.js
manifest.json

BEFORE DEPLOYING:
Open index.html and change:
const WEB_APP_URL="PASTE_YOUR_WEB_APP_URL_HERE";
to your Apps Script /exec URL.

Also change:
const COMPANY_NAME="YOUR COMPANY NAME";

After the first successful online load, the portal stores the latest Google Sheet records locally. Search, filters, VIEW DETAILS and reading history continue to work offline.

For true offline reopening/installable PWA, use HTTPS hosting such as Vercel or GitHub Pages.
