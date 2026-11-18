# klinkerklank.github.io

Personal homepage of Dennis op 't Roodt, served at <https://klinkerklank.github.io/>.

Built with Jekyll and based on the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) theme by Yaoyao Liu.

## Structure

- `index.md` — page content (about, education, research, teaching)
- `_config.yml` — name, position, contact details, links, and theme options
- `_layouts/homepage.html` — the page template
- `_includes/publications.md`, `_data/publications.yml` — publication list (currently example entries; enable by uncommenting the include in `index.md`)
- `_includes/services.md` — services section (currently example content; enable the same way)
- `assets/` — stylesheets, scripts, and images

## Local preview

```bash
bundle install
bundle exec jekyll serve
```
