# Repository Guidelines

## Project Structure & Module Organization

This repository is a Jekyll-based Academic Pages personal website. The homepage content lives in `_pages/about.md`, with site-wide identity, author profile links, theme settings, and URL configuration in `_config.yml`. Header navigation is defined in `_data/navigation.yml`. Collection content is organized under `_publications/`, `_posts/`, `_talks/`, `_teaching/`, and `_portfolio/`. Layouts and reusable HTML snippets are in `_layouts/` and `_includes/`; Sass styles are in `_sass/`, with the main stylesheet entry at `assets/css/main.scss`. Images belong in `images/`, downloadable files in `files/`, and generated or helper publication scripts in `markdown_generator/` and `scripts/`.

## Build, Test, and Development Commands

- `bundle install`: install Ruby and Jekyll dependencies from `Gemfile`.
- `bundle exec jekyll serve -l -H localhost`: build and serve the site locally at `http://localhost:4000` with live reload.
- `bundle exec jekyll build`: generate the static site and catch template or Markdown build errors.
- `npm install`: install JavaScript tooling used by the theme.
- `npm run build:js`: rebuild `assets/js/main.min.js` from theme JavaScript sources.
- `docker compose up`: run the site in Docker when local Ruby setup is inconvenient.

Restart the Jekyll server after editing `_config.yml`; ordinary Markdown changes usually rebuild automatically.

## Coding Style & Naming Conventions

Use Markdown with YAML front matter for content pages and collection entries. Keep front matter keys lowercase where possible and follow existing file naming patterns, such as `_posts/YYYY-MM-DD-title.md` and `_publications/YYYY-MM-DD-paper-title.md`. Use two-space indentation in YAML, HTML includes, and Sass nesting. Keep prose edits concise and avoid changing theme internals unless the site behavior or design requires it.

## Testing Guidelines

There is no dedicated automated test suite. Validate changes by running `bundle exec jekyll build` before committing. For visual or navigation updates, also run the local server and check the homepage, sidebar links, navigation anchors, and any changed collection pages in a browser.

## Commit & Pull Request Guidelines

Recent commits use short imperative summaries, for example `Modify profile.png`, `Correct a date`, and `Fix github url`. Keep commit subjects brief and specific. Pull requests should describe the visible site change, list affected pages or assets, link related issues when applicable, and include screenshots for layout, image, or style changes.

## Security & Configuration Tips

Do not commit private credentials, analytics secrets, or unpublished documents. Public files under `files/` and `images/` may be served directly by GitHub Pages, so review uploads before committing.
