# Amber Tang portfolio — GitHub Pages export

This ZIP contains the current static portfolio. No build command or dependency installation is needed. The working activation case study is excluded from this public export; its non-clickable “Work in progress” card remains on the Calendly projects page.

## Publish on GitHub Pages

1. Create a GitHub repository and extract this ZIP. Upload the **contents** of the extracted folder to the repository root, so `index.html`, `app.js`, `style.css`, `assets/`, and `work/` are at the top level. GitHub does not extract an uploaded ZIP for Pages.
2. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
3. In the same Pages settings, enter your custom domain. Follow GitHub's displayed DNS instructions with your domain provider, then enable **Enforce HTTPS** when available.

This export also supports opening `index.html` directly from the extracted folder and previewing from a `username.github.io/repository` address before you connect a custom domain. Keep the folder structure intact so assets and project pages resolve.

GitHub Pages setup: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
Custom domain: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

To revise the site later, edit `app.js` for content and interactions and `style.css` for styling. The pages under `work/` load that shared code. Avoid publishing the activation draft until it is ready.
