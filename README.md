# KaydenRMaughan.github.io

Personal portfolio site: data science and AI work across healthcare, operations, education, and decision intelligence. Built with [Quarto](https://quarto.org) and published with GitHub Pages at <https://kaydenrmaughan.github.io>.

## Structure

| Path | Purpose |
|---|---|
| `_quarto.yml` | Site config: navbar, theme, footer |
| `index.qmd` | Home |
| `projects/` | Project listing and one page per finished project |
| `writing/` | Writing listing; posts in `writing/posts/` |
| `about.qmd` | About and resume |
| `consulting.qmd` | Consulting and contact |
| `images/` | Site images |

## Local development

Requires [Quarto](https://quarto.org/docs/get-started/) 1.10 or later.

```bash
quarto preview   # live-reloading local server
quarto render    # build into _site/
```

## Adding a project

A project gets a page only when it is finished: public repository, reproducible setup, clear README, results and limitations, and a working demo or screenshots. Work in progress is not listed.

1. Copy `projects/_template/` to `projects/<slug>/`. Folders that start with `_` are not built.
2. Fill in the 15 sections and delete each prompt as you go.
3. Set `draft: false` and add a `thumbnail.png`.

`draft: true` only hides a page from the listing, search, and sitemap. The page is still built at its URL, so keep write-ups in the project's own README until the project is done.

## History

The previous version of this site (Jekyll, 2023) is preserved at the `legacy-jekyll` tag.
