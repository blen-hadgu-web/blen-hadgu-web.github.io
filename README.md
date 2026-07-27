#  Semantic Resume

A responsive, accessible personal resume for **Blen Hadgu**, built with semantic HTML5 and modern CSS.

## Live Deployments

Replace the Netlify and Cloudflare placeholders after deployment.

- GitHub Pages: `https://blen-hadgu-web.github.io/`
- Netlify: `https://YOUR-SITE-NAME.netlify.app/`
- Cloudflare Pages: `https://YOUR-PROJECT-NAME.pages.dev/`

## Repository

`https://github.com/blen-hadgu-web/blen-hadgu-web.github.io`

## Project Files

```text
blen-hadgu-web.github.io/
├── .nojekyll
├── favicon-32.png
├── favicon.svg
├── index.html
├── netlify.toml
├── og-image.png
├── README.md
├── robots.txt
└── styles.css
```

## Production Optimizations

- Search-engine-friendly page title and description
- Canonical URL
- Open Graph metadata for professional sharing previews
- Twitter/X large-image card metadata
- 1200 × 630 Open Graph preview image
- SVG and PNG favicons
- Public `robots.txt`
- Netlify root publish configuration
- `.nojekyll` for direct static publishing on GitHub Pages

## Run Locally

No dependencies or build step are required.

1. Clone or download this repository.
2. Open `index.html` in a browser.

## Deployment Configuration

### GitHub Pages

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/(root)`

### Netlify

- Repository: `blen-hadgu-web/blen-hadgu-web.github.io`
- Production branch: `main`
- Base directory: leave blank
- Build command: leave blank
- Publish directory: `.`

### Cloudflare Pages

- Repository: `blen-hadgu-web/blen-hadgu-web.github.io`
- Production branch: `main`
- Framework preset: None
- Root directory: leave blank
- Build command: `exit 0`
- Build output directory: `.`

## AI Collaboration Prompt

> I have deployed my raw HTML/CSS resume to GitHub Pages, Netlify, and Cloudflare Pages. Act as a senior DevOps engineer and frontend performance expert. Review my HTML and CSS code and provide the code/instructions for three critical production optimizations:
>
> Open Graph (OG) Meta Tags: Generate the `<meta>` tags I need to add to my `<head>` so that when I share my resume link on LinkedIn, Slack, or Discord, it displays a professional preview card (including title, description, and a preview image).
>
> SEO & Favicon: Give me the exact HTML code to point to a professional favicon and add a search-engine-friendly description.
>
> Performance Diagnostics: Explain what a `robots.txt` file is, and generate a basic, valid `robots.txt` file for my site that allows search engines to index it.

## What robots.txt Does

`robots.txt` is a plain-text file at the root of a website that gives web crawlers instructions about which public paths they may crawl. It is not a security mechanism and does not hide private information. This project allows crawlers to access the entire public resume.

## Author

**Blen Hadgu**
