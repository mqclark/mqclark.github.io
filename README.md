# The Clark Lab: GitHub Pages site

A static, no-build website for GitHub Pages. It uses plain HTML, CSS, JavaScript, and local SVG artwork. No framework, database, or paid hosting is required.

## What is in this package

- `index.html` — home page
- `research.html` — research and selected publications
- `students.html` — undergraduate research and teaching
- `outreach.html` — Pueblo Brain Science, public science, creative work
- `about.html` — bio and publications
- `contact.html` — contact page
- `assets/styles.css` — all layout and visual styling
- `assets/script.js` — mobile navigation, reduced-motion-respecting reveal effects, current year
- `assets/img/` — original abstract SVG visuals that can later be replaced with cleared lab, student, microscopy, and outreach photographs

## Publish on GitHub Pages

1. Create a GitHub account if you do not have one.
2. Create a new public repository. Either:
   - Name it `YOUR-USERNAME.github.io` for a site at `https://YOUR-USERNAME.github.io`, or
   - Give it another name, such as `clark-lab-site`, for a project site at `https://YOUR-USERNAME.github.io/clark-lab-site/`.
3. Upload every file and folder in this package to the repository root. Do not upload the enclosing `clark-lab-github-pages` folder itself.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then save.
7. GitHub will give you the public address after the deployment completes.

## Before launch

- Confirm the faculty title, email address, and Bucknell affiliation.
- Replace the abstract SVGs in `assets/img/` with approved real imagery where possible. Keep the file names or update the image paths in the HTML.
- Add a current professional headshot and approved student / outreach images only after confirming public-use permissions.
- Add verified DOI, PubMed, or Google Scholar links to publications.
- Add a downloadable current CV only after deciding it is public-safe.
- Replace the "In focus" cards with dates and current developments once you decide what should be public.
- Add your custom domain in GitHub Pages only after buying and configuring it with a registrar.

## Editing copy

Open any `.html` file in a plain-text editor. The site is deliberately simple: headings and paragraphs are visible directly in the page files.

## Design intent

The site is intentionally low-text, mobile-first, and visual. The SVG artwork is abstract rather than data-derived so it does not imply unpublished figures or results.
