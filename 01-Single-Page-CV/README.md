# Frontend Projects

This folder contains small frontend projects built while following exercises from Roadmap.sh. Each project is self-contained and can be opened directly in a browser for quick preview.

## Projects

- `01-Single-Page-CV` — a single-page CV/portfolio template.
- `02-Basic-HTML-Website` — a basic multi-page HTML website (index, article, contact, projects) with a stylesheet.

## Preview locally

Option 1 — Open in browser:

- Double-click the `index.html` file in the project folder to open it in your default browser.

Option 2 — Simple local server (recommended):

- Using Python 3 (PowerShell):

```
cd "Frontend Projects/02-Basic-HTML-Website"
py -3 -m http.server 8000; # then open http://localhost:8000
```

## Prepare for GitHub upload

Suggested steps (PowerShell):

```
cd "c:\Users\VITUS\OneDrive\Dokumen\Roadmap.sh-projects"
git init                # only if the repo is not already initialized
git add .
git commit -m "chore: add frontend projects"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
```

Replace `<your-github-repo-url>` with the HTTPS or SSH URL of your GitHub repository.

## Notes

- Keep assets (images, fonts) inside each project folder for portability.
- Use the included `.gitignore` to avoid committing editor or OS files.

If you want, I can also add per-project instructions, or create a single GitHub Pages branch and help deploy these projects as a static site.
