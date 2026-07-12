# ilkingh.github.io

Personal landing page for **Lorenzo Privitera** ([@ilkingh](https://github.com/ilkingh)),
hosted on GitHub Pages at **https://ilkingh.github.io**.

Static site, no build step — plain HTML + CSS.

## Structure

```
.
├── index.html              # All page content (hero, about, skills, projects, contact)
├── assets/
│   └── css/
│       └── styles.css      # Styling (dark theme, responsive)
└── README.md
```

## Customize before publishing

1. **LinkedIn URL** — in `index.html`, find the contact link marked
   `<!-- TODO: replace with your real LinkedIn URL -->` and set your profile.
2. **Email** — find `<!-- TODO: replace with your real email address -->` and
   set your `mailto:` address (e.g. `mailto:lorenzo@example.com`).
3. **Bio / tagline** — edit the text inside the `#about` and `.hero .tagline`
   sections in `index.html`.
4. **Skills** — edit the lists inside the `#skills` section to match your real
   stack.
5. **Projects** — the three cards in `#projects` already point to your real
   repositories. Update descriptions or add/remove cards as needed.
6. **Avatar** — currently pulled from your GitHub avatar URL
   (`https://avatars.githubusercontent.com/u/83762913?v=4`). Replace with a
   local image in `assets/img/` if you prefer.

## Deploy on GitHub Pages

This repo is a **user site**, so it must be named exactly `ilkingh.github.io`
and published from the `main` branch root.

```bash
# 1. Create the repo on GitHub (via the web UI, name it ilkingh.github.io)
# 2. From this folder, initialize and push:
git init
git add .
git commit -m "Add landing page"
git branch -M main
git remote add origin https://github.com/ilkingh/ilkingh.github.io.git
git push -u origin main
```

Then in **Settings → Pages**, set the source to `Deploy from a branch` →
`main` → `/ (root)`. The site will be live at https://ilkingh.github.io
(usually within a minute).

## Local preview

Just open `index.html` in your browser, or run a quick server:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```
