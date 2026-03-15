# Summaries

Source files for the course summaries and cheat sheets. Each subdirectory contains materials for one course:

- **LaTeX projects** — folder with a `main.tex` (compiled by CI)
- **Typst projects** — folder with a `main.typ` (compiled by CI)
- **Pre-compiled PDFs** — copied directly to the website

Output PDFs are named after their folder path with `/` replaced by `-` (e.g. `summaries/analysis1/cheatsheet/` → `analysis1-cheatsheet.pdf`).

## Contributing

1. Add your source files under `summaries/<course>/` with `main.tex` or `main.typ` as the entry point
2. Add an entry to [`homepage/src/_data/documents.json`](../homepage/src/_data/documents.json) so the website knows about it
3. Push to `main` — CI compiles and deploys automatically
