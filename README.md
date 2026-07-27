# fall-2026-global-health-data-science.github.io

## Rendering

Locally, in RStudio, click *Build Website* on the Build tab or in any editor (including RStudio), run `quarto render` in the Terminal.

## Publishing

Push changes to the repo to trigger the GitHub Action that publishes the website. If any R packages are added or updated, run `renv::snapshot()`, commit, and push the updated lockfile.