# eugkim0120.github.io

Eugene's old portfolio site, a Jekyll site built on the Academic Pages template
and served by GitHub Pages. It is being retired in favour of the Vercel site
(`eugene-kim.vercel.app`, repo `~/projects/eugene-site`).

Shared dev-host rules (`~/.agents/AGENTS.md`) also apply. This file wins where
they conflict.

## Hard rules

- The default branch is `master`, not `main`. GitHub Pages serves from it, so
  every push to `master` goes live.
- A redirect to the Vercel site is in progress: `redirect_target` in
  `_config.yml` feeds a meta refresh, a script redirect and a canonical link in
  `_includes/head.html` and `_includes/seo.html` (GitHub Pages cannot send HTTP
  redirects). Do not remove it. New content belongs in `eugene-site`, not here.

## Same name, different things

- `eugkim0120.github.io` (this repo) is the old Jekyll portfolio;
  `eugene-site` is the new Next.js site on Vercel. Edit `eugene-site` for
  anything a visitor should see.

## Commands

```bash
bundle install
bundle exec jekyll serve -l -H 127.0.0.1   # preview on http://127.0.0.1:4000
npm run build:js                           # rebuild assets/js/main.min.js
```

## Layout

Standard Academic Pages layout: `_config.yml` (site settings), `_pages/`,
`_posts/`, `_portfolio/`, `_publications/`, `_talks/`, `_teaching/` (content),
`_layouts/`, `_includes/`, `_sass/`, `assets/` (theme), `files/` (downloads),
`markdown_generator/` and `scripts/` (content generators). See README.md
(upstream template docs).
