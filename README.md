# CUNEF Server User Guide

Source of <https://cunef-hpc.github.io/>, a practical guide to `naranjito`, the compute server of CUNEF Universidad.

Written and maintained by [Roi Naveiro](https://roinaveiro.github.io/), CUNEF Universidad.

## Editing

Each page is a Quarto Markdown file:

| File | Sections of the PDF |
|---|---|
| `index.qmd` | Title page, contents, Before You Start (plus citation and about) |
| `getting-started.qmd` | 1.1–1.4 |
| `server.qmd` | 1.5–1.7 |
| `first-job.qmd` | 1.8–1.10 |
| `working-with-jobs.qmd` | 1.11–1.17 |
| `arrays.qmd` | 2.1–2.3 |
| `gpus.qmd` | 2.4 |
| `multicore.qmd` | 2.5–2.6 |
| `troubleshooting.qmd` | 2.7–2.8 |
| `reference.qmd` | 3.1–3.3, 4 |

The text is kept identical to the PDF, including its section numbers: headings carry the number (`## [1.7]{.secnum} Usage Limits`) and cross-references read "Section 1.7" with a link. When sections are added or moved in the PDF, renumber them here too.

Navigation is in `_quarto.yml`; the look is in `theme.scss` and the code colours in `naranjito.theme`.

Preview locally with `quarto preview`. Pushing to `main` renders the site and publishes it to GitHub Pages (`.github/workflows/publish.yml`).

The PDF in `assets/` is compiled from the LaTeX version of the guide. Replace it whenever the guide changes, so both versions stay in step.
