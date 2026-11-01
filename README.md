# jdrechsel13.github.io

Personal academic website of Jonathan Drechsel. Plain static HTML/CSS/JS, no build step.

- `index.html`: homepage (about, news, publications, artifacts, experience, education)
- `cv.html`: HTML CV; `cv.pdf` is rebuilt automatically by GitHub Actions on every change to `cv.html` or `styles.css`
- `assets/profile.jpg`: profile photo (add yourself)

Local preview: `python -m http.server` and open http://localhost:8000.

Enable hosting under *Settings → Pages → Deploy from branch → `main` / root*.
