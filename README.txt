# Crishjane Pajaron — Personal Portfolio

A responsive, single-page portfolio website built with HTML, CSS, and vanilla JavaScript.

## Run locally
1. Extract the ZIP file.
2. Open the `cj_personal_portfolio` folder.
3. Double-click `index.html` to open it in your browser.

You can also use VS Code with the Live Server extension.

## Personalize before publishing
1. Replace the photo placeholder in the hero section with your own professional photo.
   - Put your image in this folder, for example `images/profile.jpg`.
   - In `index.html`, replace the `<div class="portrait-placeholder">...</div>` block with:
     `<img class="profile-photo" src="images/profile.jpg" alt="Crishjane Pajaron">`
   - Add this CSS rule to `styles.css`:
     `.profile-photo{width:100%;height:100%;object-fit:cover;object-position:center;}`
2. Replace `YOUR_EMAIL@example.com` with your actual professional email.
3. Add your real GitHub and LinkedIn profile links.
4. Add project screenshots and repository/demo links where available.
5. Verify dates, project details, and award information before publishing.

## Publish free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a new public repository, for example `cj-portfolio`.
3. Upload `index.html`, `styles.css`, and `script.js` to the repository root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for the published website link to appear in the Pages section.

## Notes
- No backend or database is required.
- Google Fonts are loaded online; the page still works without them using fallback fonts.
- The portfolio text is a starting draft. Edit it to reflect only your verified experience and work.
