# Maya Thille — PhD Portfolio

A responsive, four-page academic portfolio designed for GitHub Pages.

## Before publishing

1. Open `contact.html` and replace `YOUR_EMAIL@example.com` in both places.
2. Replace the four `href="#"` values with your Google Scholar, ORCID, LinkedIn, and GitHub URLs. Remove any profile link you do not use.
3. Review the CV content and add exact degree titles, dates, laboratory name, supervisors, presentations, publications, awards, and teaching experience as appropriate.
4. If you want a downloadable PDF CV, add the PDF to the project and insert a link to it on `cv.html`. The existing **Print / Save PDF** button already produces a clean printable version.

## Publish with GitHub Pages

1. Create a new GitHub repository. For a personal site, name it `YOUR-USERNAME.github.io`; otherwise choose any repository name.
2. Upload the contents of this folder to the repository root—not the folder itself.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. GitHub will show the published URL after deployment finishes.

## Local preview

You can open `index.html` directly in a browser. For a more accurate local preview, run a small local server from this folder, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Structure

- `index.html` — home page
- `research.html` — research program and projects
- `cv.html` — web and print CV
- `contact.html` — contact details and profile links
- `assets/styles.css` — shared design and responsive styles
- `assets/script.js` — navigation, current year, and subtle reveal effects
- `assets/favicon.svg` — browser icon

## Customizing the visual style

Colors are defined at the top of `assets/styles.css` as CSS variables. The site uses Newsreader and DM Sans from Google Fonts; browser fallbacks are included.
