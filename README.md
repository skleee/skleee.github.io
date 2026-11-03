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
