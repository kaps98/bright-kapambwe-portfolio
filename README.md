# Bright Kapambwe Portfolio

This is a lightweight static portfolio site designed for easy deployment on GitHub Pages.

## Files

- `index.html`: page structure
- `styles.css`: visual design and responsive layout
- `script.js`: content data and interactive behavior
- `assets/Bright-Kapambwe-Resume.pdf`: downloadable CV
- `assets/favicon.svg`: browser icon

## Local Preview

You can preview the site with a simple local server, for example:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish Notes

- The site is ready for GitHub Pages because it has no build step.
- GitHub and LinkedIn links can be added later in `script.js` under `portfolioData.profile`.
- Resume content in the site was adapted from the attached CV to create a stronger portfolio presentation.
