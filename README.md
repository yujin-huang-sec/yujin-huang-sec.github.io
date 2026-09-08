# Yujin Huang Personal Website

A lightweight static academic homepage, served by GitHub Pages.

## Structure

- `index.html` - the whole page: profile, about, news, publications, awards, teaching, service
- `styles.css` - all styling; the palette lives in the `:root` custom properties at the top
- `assets/` - portrait and paper PDFs

## Design

- Typography: IBM Plex Sans throughout.
- Palette: navy `#1b4176` for badges, link blue `#1a6dd4`, bronze `#8a6b3d`, near-black `#0e1219` text.
- Type scale: 21.6px section headings, 16px body, 15.2px list entries, 14.1px secondary, 11.7px badges.

## Deploy

This is a GitHub Pages **user site**. The repository must be owned by the `yujin-huang-sec`
account and named `yujin-huang-sec.github.io`; pushing to the default branch publishes to
<https://yujin-huang-sec.github.io>.

## Local preview

```bash
python -m http.server 4173
```
