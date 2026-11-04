# Sunkyung Lee

Personal academic homepage: https://skleee.github.io/

The site uses Jekyll and a lightweight single-page layout inspired by al-folio.
GitHub Pages deploys the root of the `master` branch.

## Editing

- `_pages/about.md`: biography, publications, experience, and education.
- `_pages/cv.md`: CV download link.
- `_data/navigation.yml`: header links.
- `_layouts/modern.html`: page layout and footer.
- `assets/css/modern.css`: typography, spacing, and responsive styles.
- `_config.yml`: site metadata and professional links.
- `images/profile.jpg`: profile photo.

## Local preview

Install the Ruby dependencies with `bundle install`, then run:

```sh
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

The development configuration disables visitor analytics. Build with
`bundle exec jekyll build` before publishing.

The original site was based on Academic Pages / Minimal Mistakes. See `LICENSE`
for the retained license notice.

## Organization logo sources

These marks identify the organizations in Experience and Education. Original
artwork is stored locally in `images/logos/` and displayed without recoloring.

- Roblox: [official press kit](https://about.roblox.com/press-kit), `Roblox_Tilt_Black.svg` from the logo pack.
- Snap Research: avatar of its [verified GitHub organization](https://github.com/snap-research).
- NAVER: [official website](https://www.naver.com/) apple touch icon (`https://s.pstatic.net/static/www/nFavicon96.png`).
- Sungkyunkwan University: [official symbol page](https://www.skku.ac.kr/skku/about/symbol/symbol_01.do), `SymbolMark.jpg` from the JPG download.
