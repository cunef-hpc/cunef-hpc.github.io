# CUNEF Server User Guide

Source of <https://cunef-hpc.github.io/>, a practical guide to `naranjito`, the compute server of CUNEF Universidad.

Written and maintained by [Roi Naveiro](https://roinaveiro.github.io/), CUNEF Universidad.

## Editing

Each page is a Quarto Markdown file:

| File | Page |
|---|---|
| `index.qmd` | Overview, contents, citation |
| `getting-started.qmd` | Glossary, Slurm, logging in, copying files |
| `server.qmd` | Hardware, partitions, usage limits |
| `first-job.qmd` | First job, Python with Conda or uv |
| `working-with-jobs.qmd` | Resources, monitoring, interactive sessions, notebooks |
| `arrays.qmd` | Job arrays and dependencies |
| `gpus.qmd` | GPU scaling with JAX |
| `multicore.qmd` | Multi-core jobs and checkpointing |
| `troubleshooting.qmd` | Common problems, good citizenship |
| `reference.qmd` | Quick reference |

Navigation is in `_quarto.yml`; the look is in `theme.scss` and the code colours in `naranjito.theme`.

Preview locally with `quarto preview`. Pushing to `main` renders the site and publishes it to GitHub Pages (`.github/workflows/publish.yml`).

The PDF in `assets/` is compiled from the LaTeX version of the guide. Replace it whenever the guide changes, so both versions stay in step.
