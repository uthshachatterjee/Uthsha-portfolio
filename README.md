# Uthsha Chatterjee — Portfolio

This is a static bilingual website. No installation or build step is required.

## Preview locally

Open `index.html` for the French portfolio or `en.html` for the English portfolio. Keep both HTML files, `styles.css`, `script.js`, and the `assets` folder together. The tool logos are local SVG files in `assets/tool-logos`, so keep that folder when uploading the site.

## Add gallery photos

The Gallery section in both `index.html` and `en.html` has three placeholders. To add a photo, put the image in `assets`, replace a `.gallery-placeholder` element with an image such as `<img src="assets/project-photo.jpg" alt="Description of the photo">`, and update its caption. Add the same photo to both pages if it should appear in both languages.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository, for example `uthsha-portfolio`.
2. Upload the contents of this folder to the repository's root. Both `index.html` and `en.html` must be at the root, with `styles.css`, `script.js`, and `assets` beside them.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After GitHub finishes publishing, the site address appears on the Pages settings screen.

The French portfolio opens at the site address; add `en.html` to the end of the address for the English version. The site and documents in `assets` will be public to anyone with the website link. Remove any file you do not want to share before publishing.
