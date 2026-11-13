# ThePacer-Web

The public website for The Pacer, served at <https://thepacer.app> by GitHub Pages from `main`. The app's own repository is private; this one holds only what is public.

## What is here

| Path | Content |
|---|---|
| `index.html` | Home page |
| `manual/` | The user manual, one Markdown file per chapter. Chapter order is the `manual` list in `_config.yml` |
| `privacy.md`, `impressum.md` | Legal pages |
| `_layouts/`, `_includes/`, `assets/css/site.css` | Layout and styles |
| `assets/fonts/` | Lexend, self-hosted (OFL), so the site loads nothing from other domains |
| `assets/img/screens/` | Screen images, copied from the app repository's design renders |

## Keeping it consistent with the app

- **Colours** in `assets/css/site.css` are the app's tokens (`docs/design/tokens.json` in the app repository, spec 2.1), light and dark.
- **Screens** are the renders `tool/render_screens.sh` writes to `docs/design/screens/`. When a design changes, re-render and copy the changed files here under the same name. Device screenshots can replace them later.
- **The manual** describes what the app does today, following the spec (`docs/spec/project_specs.md`). A feature that is designed but not built does not go in.
- **The privacy policy** must match the shipped app. Slice 29 (diagnostics) changes it before it ships.

## Preview locally

GitHub Pages builds with Jekyll 3.10. To preview:

```bash
gem install --user-install 'jekyll:3.10.0' kramdown-parser-gfm webrick
jekyll serve        # http://127.0.0.1:4000
```
