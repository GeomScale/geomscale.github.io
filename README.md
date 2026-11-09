# GeomScale homepage

Source of [geomscale.github.io](https://geomscale.github.io), built with [Jekyll](https://jekyllrb.com)
and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes) theme.

## Build locally

Requires Ruby ≥ 3.1 and Bundler.

    bundle install
    bundle exec jekyll serve      # http://127.0.0.1:4000

## Deployment

Every push to `gh-pages` is built and deployed by `.github/workflows/pages.yml`.
Pull requests are built and their internal links checked, but not deployed.

## Writing

- Posts go in `_posts/YYYY-MM-DD-slug.md`. The URL is `/slug/`.
- Pages and posts take their title from front matter (`title:`) or, if absent, from the first `#` heading.
- Add `math: true` to the front matter of a page that uses LaTeX (`$...$`, `$$...$$`); MathJax loads only there.
