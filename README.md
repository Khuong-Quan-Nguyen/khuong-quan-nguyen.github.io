# khuong-quan-nguyen.github.io

Personal portfolio site — Quan Nguyen, AI Engineer (Toronto, ON).

**Live:** https://khuong-quan-nguyen.github.io

## About

A single-page static site: projects, experience, skills, and contact. No
framework, no build step, no dependencies — one `index.html` with inline CSS and
web fonts loaded from Google Fonts.

## Structure

```
index.html    # the entire site — markup, styles, content
```

## Running it locally

Open `index.html` in a browser. That's the whole workflow.

For a local server (needed only if you add anything that requires HTTP):

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

GitHub Pages serves the `main` branch from the repository root. Pushing to
`main` publishes; the build usually completes within a minute or two.

```bash
git add index.html
git commit -m "Update portfolio"
git push
```
