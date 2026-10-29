# Dev with Daryl — Static HTML Website

A single-file website using plain HTML, CSS, and JavaScript. No Node.js, build step, or package installation is required.

## Preview locally
Open `index.html` in your browser.

## Publish with GitHub Pages
1. Create a repository at https://github.com/new.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages** in the repository.
4. Choose **Deploy from a branch**, select your default branch (usually `main`) and `/ (root)`, then save.
5. Wait for the published URL to appear in the Pages settings.

## Customize before publishing
Edit `index.html` and find `const SITE_CONFIG` near the bottom. Set your real `email`, `bookingUrl`, `linkedinUrl`, and `githubUrl`.

The contact form uses `mailto:`: it opens the visitor's email application and does not send submissions automatically or provide server-side email notifications. To receive form submissions directly, connect a form service or backend later.

Project cards are illustrative placeholders. Add real screenshots, links, and accurate project details before publishing.
