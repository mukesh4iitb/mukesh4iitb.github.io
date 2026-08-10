# mukeshphy-site

A clean, static replacement for https://sites.google.com/view/mukeshphy/home — plain HTML/CSS, no build step, ready for GitHub Pages.

## Structure

```
mukeshphy-site/
├── index.html          Home
├── about.html            About (education, advisors, leadership, links)
├── research.html        Research
├── publications.html    Publications
├── code.html             Code
├── workshops.html        Workshops & Conferences
├── links.html            Links
├── assets/
│   ├── style.css         shared stylesheet
│   ├── about/             figures used on the About page
│   ├── research/          figures used on the Research page
│   └── profile.jpg        (add your own photo here — see below)
└── README.md
```

The "Code" nav link points straight to your existing GitHub Pages site
(`https://mukesh4iitb.github.io/`) rather than a local page, matching how it
worked on the Google Sites version.


### Template for Academic CV_short are taken from here:
https://github.com/topics/academic-cv-latex-template

### Template for Academic CV_long are taken from here:
https://www.overleaf.com/latex/templates/a-customised-curve-cv/mvmbhkwsnmwv

<!-- ## Add your photo (optional)

The homepage currently shows a placeholder "MS" monogram avatar. To use a
real photo:

1. Drop an image into `assets/profile.jpg` (a square photo, roughly 300×300px, works best).
2. In `index.html`, replace the avatar block:
   ```html
   <div class="avatar">
     MS
   </div>
   ```
   with:
   ```html
   <div class="avatar">
     <img src="assets/profile.jpg" alt="Mukesh Singh">
   </div>
   ```

## Deploy on GitHub Pages

1. Create a new GitHub repo (e.g. `mukeshphy-site`, or `mukesh4iitb.github.io`
   if you want it at the root of your GitHub Pages domain — note you already
   have a repo at that name for your Code page, so a distinct repo name is
   simplest here).
2. From inside this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/mukeshphy-site.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`. Save.
4. Your site will be live at `https://<your-username>.github.io/mukeshphy-site/`
   within a minute or two.
5. Optional: add a custom domain in the same Pages settings if you have one.

## Local preview

No build tools needed — just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Editing content

Every page is a self-contained HTML file with the same header/nav/footer
markup repeated at the top and bottom — edit the text in the `<main>` section
of whichever page you want to change. All shared visual styling lives in
`assets/style.css`. -->
