# Repository Guidelines

## Project Structure & Module Organization

This repository is a Jekyll academic website deployed through GitHub Pages from `master`. Main sections live in `_pages/`; dated news items belong in `_posts/YYYY-MM-DD-kebab-case-title.md`. `_data/navigation.yml` controls the top navigation, while `index.html` defines the home page. The remote Minimal Mistakes theme supplies most templates; files in `_layouts/` and `_includes/` are deliberate local overrides. Root-level `styles.css` and `script.js` support the People cards, while `new-styles.css` supports Data and Software cards. Store images, papers, structures, and course files in the matching `assets/` subdirectory. Never edit generated `_site/` or commit `vendor/` or `Gemfile.lock`.

## Build, Test, and Development Commands

- `bundle install`: install the Ruby 3.3.5 dependencies declared in `Gemfile`.
- `bundle exec jekyll serve --livereload`: serve the site at `http://localhost:4000` and refresh changed pages.
- `bundle exec jekyll build`: generate `_site/` and catch configuration, Liquid, or rendering errors.

Restart the server after changing `_config.yml` because Jekyll does not reload that file automatically.

## Coding Style & Naming Conventions

Use two-space indentation for YAML and nested HTML or Liquid; match the surrounding style in CSS and JavaScript. Keep YAML front matter at the top of every page and post. Use lowercase, hyphenated filenames, and preserve the required date prefix for posts. When adding a main page, update its explicit `permalink` and the corresponding navigation URL together. Retain descriptive image `alt` text and pair `target="_blank"` with `rel="noopener noreferrer"`.

## Testing Guidelines

There is no automated test suite, coverage target, or linter. Before submitting a change, run `bundle exec jekyll build`, then inspect the affected page through the local server. Check links, images, navigation, interactive cards, and both desktop and narrow-screen layouts as applicable. Confirm that any new plugin is supported by GitHub Pages.

## Commit & Pull Request Guidelines

Use a short, sentence-case, action-oriented commit subject, consistent with history: `Update Papers...`, `Add PDF links`, or `Remove orphan asset`. Keep each commit focused on one content or presentation change. Pull requests should summarize the visible effect, list validation performed, link a relevant issue when one exists, and include before/after screenshots for layout or styling changes. Pushes to `master` deploy automatically, so never commit credentials and verify the rendered result before merging.
