# IDP-X static website

Static, framework-free version of the IDP-X website for GitHub Pages.

## Structure

```text
idpx-github-pages/
├── index.html
├── previousprojects/
│   └── index.html
├── impressum/
│   └── index.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── images/
├── .nojekyll
├── CNAME.example
└── README.md
```

## Application

There is **no application form**. Both application buttons open an email to:

`idpx.lfe@ed.tum.de`

To change the address, search the HTML files for `idpx.lfe@ed.tum.de`.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload everything in this folder to the repository root.
3. Commit and push.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select your main branch and `/ (root)` as the folder.
7. Save.

For a project repository named `idpx`, GitHub will normally publish it at:

`https://idpx-lfe.github.io/idpx.github.io/`

All internal links use relative paths, so the site works both on a project Pages URL and on a custom domain.

## Custom domain

If you later move `idpx.lfe.ed.tum.de` to GitHub Pages:

1. Configure the custom domain in **Settings → Pages**.
2. Ask the TUM DNS administrator to point the subdomain to the GitHub Pages hostname specified by GitHub.
3. Rename `CNAME.example` to `CNAME` and keep only the domain name inside.

Do **not** add the active `CNAME` file until DNS migration is intended.

## Editing content

- Main page: `index.html`
- Previous projects: `previousprojects/index.html`
- Imprint: `impressum/index.html`
- Colours/layout: `assets/css/style.css`
- Mobile menu: `assets/js/main.js`

## Notes before publishing

- The current Summer Semester 2026 dates are included as editable HTML content.
- The imprint page should be checked against the current official TUM legal wording before publication.
- Local copies of visual assets from the existing IDP-X site are included for the reconstruction. Confirm that the repository/publication has the required rights for these images, particularly staff photographs.
