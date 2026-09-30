# Cacheell.github.io

Personal academic website for Cache Ellsworth, served by GitHub Pages at <https://cacheell.github.io>.

Built on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Where things live

| What | File |
| --- | --- |
| Home page / bio | `_pages/about.md` |
| Research page | `_pages/research.md` |
| Teaching page | `_pages/teaching.md` |
| CV (linked from the nav) | `files/MyCV.pdf` |
| Nav bar links | `_data/navigation.yml` |
| Name, photo, sidebar links | `_config.yml` (`author:` section) |
| Styles | `_sass/` |

## Previewing locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>. Or, with Docker: `docker compose up`.
