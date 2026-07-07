# Zyren | ザイレン — VTuber Site

Personal landing page for **Zyren (ザイレン)**, a VTuber and electronic music singer.
Live at **[zyren-vtuber.github.io](https://zyren-vtuber.github.io/)**.

<p align="center">
  <img src="zyren-logo.png" alt="Zyren logo" width="200">
</p>

## About

A single-page, hash-routed site with four sections — **About me**, **FAQ**,
**Official socials**, and **Credits** — over an animated blue particle
background. Built as a single static `index.html` with no build step and no
external frameworks.

## Features

- 🎨 **Custom blue theme** with the rounded *Mali* typeface.
- ✨ **Animated particle background** rendered on a `<canvas>` (vanilla JS, no libraries).
- 🧭 **Hash-based routing** — sections switch via `#one` … `#four` with no page reloads.
- 📱 **Responsive** — adapts to mobile with image constraints to prevent cropping.
- 🔍 **SEO-ready** — meta description, Open Graph & Twitter Card tags, canonical URL, `robots.txt` and `sitemap.xml`.
- ♿ **Accessible** — hidden `<h1>` for crawlers, `alt` text on images, and a static-stars fallback that respects `prefers-reduced-motion`.
- 🛡️ **Casual image-save deterrents** — right-click, drag, and `Ctrl+S`/`Ctrl+U` are blocked on images (client-side only; not a substitute for watermarking).

## Project structure

```
.
├── index.html      # The entire site (HTML + CSS + JS in one file)
├── zyren-logo.png  # Logo shown on the landing section
├── robots.txt      # Crawler directives
├── sitemap.xml     # Sitemap for search engines
└── README.md
```

Section banners and model images are hosted externally (ImgBB) and referenced by URL.

## Local development

No build tools required — it's plain static HTML. To preview locally:

```bash
# Python 3
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Deployment

The site is served by **GitHub Pages** from the `main` branch (root `/`).
Any push to `main` publishes automatically within a minute or two.

## Credits

- Model & artwork credits are listed on the site's **[Credits](https://zyren-vtuber.github.io/#four)** section.
- Design inspired by [batgirlazuki.carrd.co](https://batgirlazuki.carrd.co/), rebuilt from scratch with an original blue palette.

## License

All artwork, branding, and the Zyren character belong to their respective
owners and are **not** licensed for reuse. The site code may be used as a
reference.

---

<p align="center">Made with 💙 by Zyren | ザイレン</p>
