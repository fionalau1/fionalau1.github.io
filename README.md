# Fiona Lau — Personal Website

This repository powers Fiona Lau's GitHub Pages site.

## Site

Once GitHub Pages is enabled, the site will be available at:

https://fionalau1.github.io/

## Current setup

The first version intentionally uses plain HTML and CSS:

- `index.html` — page structure and content
- `style.css` — responsive visual styling

There is no build step or framework, so edits can be made directly in GitHub.

## Enable GitHub Pages

1. Open **Settings** for this repository.
2. Select **Pages** in the left sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Click **Save**.
6. Wait for the Pages deployment to finish, then visit `https://fionalau1.github.io/`.

## Next styling directions

### Plain HTML/CSS
Best for a fast, lightweight personal site with complete control. Add pages such as `about.html`, `projects.html`, or `writing.html`, or keep everything on one page.

### Jekyll
A natural GitHub Pages upgrade if the site becomes content-heavy. Jekyll can turn Markdown files into pages and supports layouts, collections, tags, and blogs.

Typical structure:

```text
_config.yml
_layouts/
_posts/
_pages/
assets/
index.md
```

### Jekyll theme
Use a Jekyll theme when you want a polished baseline quickly and prefer configuring the design over building it from scratch. The theme can still be customized with CSS and layouts.

## Ideas for the site

- Short professional bio
- Selected projects and case studies
- Resume / CV
- Writing or notes
- Current interests / Now page
- Talks, publications, or presentations
- Links to GitHub and other professional profiles
- Contact information
- A downloadable resume
- Photography, design, or other personal work

## Local preview

Because this version is plain HTML/CSS, you can open `index.html` directly in a browser. For a local HTTP server, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.
