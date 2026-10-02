# Alexandra Gamez — Personal Website

Source code for my personal website, built with Quarto and
deployed via GitHub Pages.

**Live site:** https://alexg171.github.io

## Built with
- [Quarto](https://quarto.org)
- GitHub Pages

## Structure

### Website
- `index.qmd` — home page (CV, research interests, skills, contact)
- `project.qmd` — research project page
- `about.qmd` — about page
- `_quarto.yml` — site configuration and navbar
- `styles.css` — custom styling
- `files/` — downloadable CV
- `images/` — headshot and other images
- `docs/` — rendered site (published output, do not edit directly)

### Research project (U.S. inflation and shocks)
- `code/data_memo.ipynb` — pulls price indexes from FRED, transforms them to annualized monthly inflation, and produces the figures and summary tables
- `data/raw/` — raw FRED index levels as downloaded (`fred_prices_raw.csv`), with a README recording the retrieval date and series
- `data/clean/inflation_annualized.csv` — annualized monthly inflation (π = 1200·Δln P), 1985-01 to 2026-08
- `output/` — figures (`fig_*.png`) and summary statistics tables (`table_summary_*.csv`)
- `paper/` — research paper