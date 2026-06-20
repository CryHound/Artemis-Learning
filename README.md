# Quantum Notes

Source for my quantum computing notes site, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Run locally

```bash
pip install -r requirements.txt
mkdocs serve
```
Visit `http://127.0.0.1:8000`.

## Deploy

Pushes to `main` auto-deploy to GitHub Pages via the included GitHub Action.
Alternatively, deploy manually:

```bash
mkdocs gh-deploy
```

## Add a new note

1. Create a new `.md` file in `docs/`
2. Add it to the `nav:` section in `mkdocs.yml`
