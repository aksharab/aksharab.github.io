# Portfolio site

Personal portfolio for Akshara Beatham — QA Engineer — published as a static site with GitHub Pages.

## Structure

```
index.html                    # the whole site (self-contained: HTML + CSS + JS)
assets/Akshara_Beatham_CV.pdf # the downloadable CV, linked from the "Download CV" button
```

## Publishing this repo as a live site

1. Push this repo to GitHub as `aksharab.github.io` (the name matters — that exact repo name is what makes GitHub serve it at the root domain rather than a `/reponame/` subpath).
2. On GitHub, go to the repo's **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
4. Wait 1–2 minutes, then visit `https://aksharab.github.io/` — the site should be live.

## Updating later

Edit `index.html` directly (it's a single file — search for the section you want, e.g. `id="project"` or `id="profile"`), commit, and push to `main`. GitHub Pages redeploys automatically within a minute or two of every push.

To replace the CV, drop a new PDF into `assets/` with the same filename (`Akshara_Beatham_CV.pdf`) so the existing download link keeps working, or update the `href` in the "Download CV" button in `index.html` if you rename it.
