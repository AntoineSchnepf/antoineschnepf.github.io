# Personal homepage

Static site (no build step) for CV + publications. Sections live in `index.html`,
styling in `style.css`.

## Fill in

- Replace `<!-- TODO -->` placeholders in `index.html`: bio, education, experience, skills, publications, social links.
- Drop `assets/portrait.jpg` and `assets/resume.pdf` in place.
- Update BibTeX/PDF/code links per publication.

## Preview locally

```
python3 -m http.server 8000
```

then open http://localhost:8000

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. Repo Settings → Pages → Deploy from branch → `main` / root.
3. Site publishes at `https://<username>.github.io/<repo>/`.
