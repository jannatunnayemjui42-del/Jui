# Jannatun Nayem Jui — Academic & Professional Portfolio

A responsive static portfolio for Jannatun Nayem Jui, a final-year Botany student at the University of Barishal. The site uses an editorial academic layout, a light/dark theme toggle, and a mobile navigation menu.

## Project files

- `index.html` — semantic content and page structure.
- `style.css` — responsive layout, design tokens, and light/dark themes.
- `script.js` — theme switching, active navigation, mobile menu, and subtle reveal effects.
- `.github/workflows/pages.yml` — deploys the site to GitHub Pages when changes are pushed to `main`.

## Local preview

Open `index.html` in a browser. The page is static HTML, CSS, and vanilla JavaScript; Google Fonts are loaded over the internet.

## Add your own assets

- Fieldwork photos: add original photographs to:
  - `assets/images/fieldwork/sundarbans/`
  - `assets/images/fieldwork/bsri/`
  - `assets/images/fieldwork/pulses-research-centre/`
  Replace each clearly marked photo frame in `index.html` with an image and descriptive `alt` text. Use landscape images where possible.
- Certificate scans or photos: add image files to `assets/images/certificates/`.
- Certificate PDFs: add original files to `assets/documents/certificates/`. Add a gallery card only after the actual certificate title, issuing organization, and date are known. Link each card directly to its original image or PDF and open it in a new tab.
- CV: `assets/documents/cv/Jannatun_Nayem_Jui_CV.pdf` is the current CV used by the hero and contact links.

Do not add stock or generated photographs as fieldwork evidence, and do not add certificate details that are not on the original documents.

## Publish

Push changes to the `main` branch to trigger the GitHub Pages deployment workflow.
