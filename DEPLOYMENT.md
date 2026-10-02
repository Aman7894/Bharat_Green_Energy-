## Run locally
Extract the ZIP. Open this folder in VS Code and use Live Server, or run:

    python -m http.server 8000

Then visit http://localhost:8000. Keep assets/ beside index.html.

## Deploy on Cloudflare Pages (recommended)
1. Sign in at https://dash.cloudflare.com/.
2. Open Workers & Pages. Select Create application, then the Pages/Get started option and Drag and drop your files (Direct Upload).
3. Enter a project name, such as bharat-green-energy.
4. Upload this ZIP, or the extracted folder containing index.html directly at its root.
5. Select Deploy site / Save and Deploy. Open the provided pages.dev URL.
6. Check Home, About, Gallery, product links, mobile navigation and WhatsApp enquiry.
7. To update, open the same Pages project, choose Create a new deployment, select Production and upload the complete updated files.
8. For your own domain, open the Pages project's Custom domains section and follow its DNS instructions.

Official instructions: https://developers.cloudflare.com/pages/get-started/direct-upload/
This is plain static HTML: there is no build step.

## Other hosting
For conventional hosting, upload the HTML files, style.css, script.js and assets/ into public_html. index.html must be at the document root. Use HTTPS.

## Contact form behavior
The form validates the fields and opens WhatsApp for 8303347611 with the customer's entered details. The customer must press Send inside WhatsApp. It does not send email automatically or save enquiries to a server/database. The floating WhatsApp button, phone links, email links and Google Maps links are included.

