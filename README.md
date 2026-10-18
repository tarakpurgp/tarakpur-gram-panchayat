# Tarakpur Gram Panchayat Website Starter

A bilingual (English/Bengali), responsive static website starter for GitHub Pages. It links to the existing Google Forms and Google Drive folders supplied by the Panchayat.

## Included

- `index.html`: complete single-page bilingual website
- `assets/`: six user-supplied images, including the GP logo, office photograph, Government of Tripura logo, Panchayati Raj logo, Model Women Friendly Panchayat logo and Amar Sarkar logo
- About Us profile with establishment year, population, households, wards, location, initiatives and public email
- Existing suggestion, complaint and service-application Google Form links
- Links to the supplied Google Drive folders for notices, development photographs and beneficiary lists
- Language switch, responsive layout and basic privacy notice

## Important limits

1. This starter does not create or publish a GitHub repository, change Google sharing permissions, or access private Google content.
2. Form submissions continue to be processed by the existing Google Forms and their configured Apps Script. Test that receipt-number generation and automatic acknowledgement still work.
3. Drive folders open in Google Drive. Their contents are not automatically displayed as an in-page gallery or live notice feed. To display images/documents directly on the site, use publicly shareable files and add approved image/document links to the site, or configure a public publishing method.
4. Check beneficiary lists carefully before making them public. Do not publish Aadhaar numbers, bank details, personal contact details, signatures, or other sensitive information.
5. The supplied logos and GP office photograph are included in `assets/`. Ensure the use of each official/programme logo is authorised and do not imply endorsement beyond the intended official purpose.

## Deploy on GitHub Pages (free)

1. Sign in to GitHub and create a **public** repository, for example `tarakpur-gram-panchayat`.
2. In the repository, choose **Add file → Upload files**.
3. Upload `index.html` from this folder to the repository root (not inside another folder).
4. Commit the file to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then click **Save**.
8. Wait for the Pages deployment to finish. GitHub will show the published URL, usually:
   `https://YOUR-GITHUB-USERNAME.github.io/tarakpur-gram-panchayat/`
9. Open the published URL on desktop and mobile. Test every Google Form and Drive link, the language switch, and the form receipt/acknowledgement workflow.
10. When updating the site, edit or upload `index.html` and commit the changes. GitHub Pages redeploys the site.

## Google Drive sharing

The website links use the folder URLs supplied by the user. If citizens receive an access-denied message, review the folder and file sharing settings in Google Drive. Only share material approved for public disclosure.

## Additional forms

The current website includes the three supplied forms. If you add another Google Form, add another service card in `index.html` with its verified URL.
