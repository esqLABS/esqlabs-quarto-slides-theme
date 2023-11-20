# esqLABS Quarto Slides Theme

A [Quarto](https://quarto.org) revealjs extension for authoring esqLABS presentations.  


## Requirements

You need [Quarto](https://quarto.org) (>= 1.0.15).

## Installation

This repository is private. You will have to use a Personal Access Token (PAT):

1. Generate a PAT: Go to GitHub settings → Developer settings → Personal access tokens → Generate new token.
2. Use the PAT: In R, use usethis::edit_r_environ() and add GITHUB_PAT=your_pat_here.
3. Restart R session after saving.

This extension can be installed/used using the following command:

- Install
  ```bash
  quarto add esqLABS/esqlabs-quarto-slides-theme
  ```
- Use
  ```bash
  quarto use template esqLABS/esqlabs-quarto-slides-theme
  ```

## Going further

Read the [Quarto documentation on reveal.js format](https://quarto.org/docs/presentations/revealjs/)