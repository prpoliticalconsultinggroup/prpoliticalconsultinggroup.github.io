# P&R Political Consulting Group — Website

Static site for GitHub Pages. No build step.

```
index.html
css/style.css
js/main.js
assets/hero.jpg   <- add your own (optional)
```

## Deploy to GitHub Pages
1. Create a repo (e.g. `pr-consulting`) and upload these files to the root.
2. Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
3. Site goes live at `https://<username>.github.io/<repo>/` in a minute or two.
4. Custom domain (optional): enter it under Settings → Pages and add a `CNAME` DNS record pointing to `<username>.github.io`.

## Hook up the audit form
GitHub Pages can't process form submissions, so the form posts to Formspree (free tier works):
1. Sign up at https://formspree.io and create a form.
2. In `index.html`, replace `YOUR_FORM_ID` in the form's `action` with your ID.

## Hero photo
Place a capitol/government building photo at `assets/hero.jpg` (≈1920×1080). Without it, the hero falls back to a navy gradient.
