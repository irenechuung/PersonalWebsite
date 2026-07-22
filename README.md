# Personal Website

My personal portfolio site, built with plain HTML/CSS/JS and deployed via GitHub Pages.

## Editing content

All content lives in `index.html` — look for text in `[brackets]` and replace it with your own.

- **About**: bio + skills list
- **Projects**: one `<article class="project-card">` per project
- **Resume**: drop your PDF at `assets/resume.pdf` (the download button already points there)
- **Contact**: update the email, GitHub, and LinkedIn links

## Running locally

No build step needed — just open `index.html` in a browser, or serve it:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying

Push to `main` and enable GitHub Pages in the repo settings (Settings → Pages → Source: `main` branch, `/root`). The site will be live at:

```
https://irenechuung.github.io/PersonalWebsite/
```
