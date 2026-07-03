# Personal website — Ade Febriady

A single-page static job-market site. No build step, no dependencies.

## Files
- `index.html` — the whole site (HTML + CSS inline).
- `Ade_Febriady_CV.pdf` — CV linked from the site (regenerate from the LaTeX CV and copy over to update).
- `photo.jpg` *(optional)* — drop a square headshot here, then see the note in `index.html` to switch the "AF" avatar to the image.

## Preview locally
Just double-click `index.html`, or open it in any browser.

## Deploy to GitHub Pages (free)
This repo is `febriady/febriady.github.io`, so the site is served at **https://febriady.github.io**.
To update the live site after editing files here:

```
git add -A && git commit -m "Update site" && git push
```

Changes appear at https://febriady.github.io within a minute or two.

### Custom domain (optional, later)
Buy a domain (e.g. adefebriady.com), add a `CNAME` file containing the domain to the repo,
and point the domain's DNS to GitHub Pages per GitHub's docs. Free HTTPS is included.

## Things to fill in
- **Google Scholar**: add your profile URL where marked in `index.html` (two commented spots).
- **Photo**: see above.
- **JMP PDF**: currently links to the EconStor copy of GLO DP 1731; swap for a hosted PDF if you prefer.
