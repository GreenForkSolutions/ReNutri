# ReNutri — Recovery with Nutrition

A responsive static website, ready for GitHub and Netlify.

## Preview locally
Open `index.html` in your browser. For a more accurate preview, run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish using GitHub + Netlify
1. Create a new GitHub repository (for example `renutri-website`).
2. Upload **all files from this folder** to the repository root.
3. In Netlify, choose **Add new project → Import an existing project → GitHub**.
4. Select the repository. Leave the build command blank; set the publish directory to `.` (root).
5. Deploy. Netlify will provide a `*.netlify.app` URL. You can add a custom domain later.
6. Enable/check form detection in Netlify and redeploy if necessary. Test the contact form on the live Netlify URL; it will not send messages from a local file preview.

## Customize
- Replace the CSS-built text logo with your official transparent logo when available.
- Update wording to match your approved organizational mission, programs and services.
- Add real recipe pages, downloadable guides, and photography when ready.
- Contact form submissions can be reviewed in Netlify's Forms area, subject to your plan and form settings.

This starter site does not claim medical outcomes, list unverified contact information, or invent organization credentials.
