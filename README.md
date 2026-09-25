# Anas Norani — Personal Portfolio

A 5-page personal portfolio website built for **CS313: Web Engineering — Lab 3
(HTML Advanced, Personal Portfolio II)**.

## Live Site
Replace this line with your GitHub Pages link once deployed, e.g.:
`https://anasnorani1.github.io/portfolio/`

## Repository
Replace this line with your GitHub repository link, e.g.:
`https://github.com/anasnorani1/portfolio`

## Pages
- `index.html` — Home page with a short bio and photo
- `skills.html` — Personal skills (progress bars + tool tags)
- `hobbies.html` — Hobbies and interests
- `gallery.html` — Image gallery (6 images, laid out with CSS float + clear)
- `contact.html` — Contact details and a contact form

## Folder Structure
```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   └── profile.jpg
└── README.md
```

## What Was Done in This Lab
- Moved **all CSS into a single external stylesheet** (`css/style.css`) —
  no inline or `<style>` block styling anywhere in the HTML.
- Built the **navigation menu** as a horizontal bar using `float: left`
  on the `<li>` elements, cleared with a `.clearfix` utility class.
- Used **`float` and `clear`** to lay out the hero section (profile photo
  floated beside the intro text) and the **image gallery** (each photo
  floated into a 3-column grid, with a clearfix so the container wraps
  its floated children correctly).
- Organized the project into `css/` and `images/` folders as required.
- No JavaScript and no CSS framework/library were used — plain HTML5 and
  hand-written CSS3 only.

## Notes on the Gallery Images
The gallery images are linked directly from Pexels (free-to-use, no
attribution required) rather than stored locally, since only my own
profile photo was provided as a local file. `images/profile.jpg` is the
only image bundled in this repository.

## Deployment (GitHub Pages)
1. `git init`
2. `git add .`
3. `git commit -m "Lab 3: portfolio with external CSS and float/clear layout"`
4. `git remote add origin <your-repo-url>`
5. `git push -u origin main`
6. On GitHub: **Settings → Pages → Deploy from branch → main → / (root)**
7. Your live link will appear as `https://<username>.github.io/<repo-name>/`
