# TDS Vancouver website preview

Static HTML preview of the new tdsvancouver.com pages. Every internal link is relative, so it works
from a folder on your computer, from GitHub Pages, or from any static host.

## Open it on your computer
Open `index.html` in a browser (double-click). All menus and links work offline except photos,
which load from tdsvancouver.com.

## Put it on GitHub Pages
1. Create a repository and upload everything in this folder (keep the folder structure and the `.nojekyll` file).
2. In the repository go to Settings > Pages.
3. Under "Build and deployment" choose "Deploy from a branch", pick the `main` branch and `/ (root)`, then Save.
4. After a minute the site appears at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Notes
- Each page has a `noindex, nofollow` robots tag so this preview is not indexed by Google. Remove it when the pages go live.
- Links to the Contact, Blog, Privacy Policy and Carbon Neutral pages point to the live tdsvancouver.com site, because those pages are not part of this build.
- The quote form is a front-end mockup and does not send messages yet.
