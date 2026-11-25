YERWA EMPOWERMENT FOUNDATION WEBSITE - REFINED SOURCE PACKAGE

PROJECT STRUCTURE
- Existing HTML, CSS, JavaScript, Bootstrap, jQuery and font assets are retained.
- The supplied 30-image folder is included at images/ and image filenames are preserved.
- No frontend framework conversion has been performed.
- Existing visual styles have been retained, with supplementary donation-page styles.

DONATION PAGE STATUS
The donation page now provides currency selection, suggested/custom amounts, donation purpose, one-time/monthly enquiry selection, bank details for NGN and USD, account-number copy and a prefilled email enquiry.

IMPORTANT: This is not an online payment gateway. No Paystack or Flutterwave credentials were supplied. No card collection, payment processing, recurring debit, server-side transaction verification or automated receipt has been activated. GBP and EUR bank accounts were not supplied, so the page directs donors to contact YEF. Configure a payment provider and secure backend before advertising online card payments.

VERCEL DEPLOYMENT
1. Extract the ZIP into a Git repository.
2. Import the repository into Vercel.
3. Set Framework Preset to Other.
4. Leave Build Command and Output Directory empty for this plain static site, or use the project root as the output directory.
5. Deploy.
6. Test every page and asset path on the deployed domain.

WHOGOHOST CPANEL DEPLOYMENT
1. Extract the ZIP locally.
2. Upload the contents of this folder, not the parent folder, into public_html.
3. Ensure index.html is directly inside public_html.
4. Enable SSL in cPanel and force HTTPS using the hosting provider's recommended settings.
5. Test every page, image, stylesheet and script.

IMAGE ASSETS
The supplied images.zip has been integrated into images/. It includes the YEF logo and the supplied gallery, activity, team, slider and testimonial photographs. Keep the images/ folder at the website root when deploying. Image filenames have been preserved. The original uploaded images.zip remains unchanged.

FUNCTIONALITY LIMITATIONS
The contact and newsletter forms in the original source still require a configured server-side or third-party submission endpoint. The donation enquiry link opens the visitor's email application. A browser-only static site cannot securely process donations or store form submissions.

VERIFICATION
Run a full browser test after adding the missing assets and configuring any required external services.
