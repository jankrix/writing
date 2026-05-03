# Writing

Books by Erick Liemarga, published at <https://jankrix.github.io/writing/>.

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). Auto-deployed via GitHub Actions on push to `main`.

## Local preview

```bash
pip install mkdocs-material
mkdocs serve
```

Then open <http://127.0.0.1:8000/>.

## Structure

- `docs/` — published source. Anything in here is what the site builds from.
- `mkdocs.yml` — site config and navigation.
- `.github/workflows/deploy.yml` — auto-deploy workflow.

Editorial workspace (briefs, drafts, voice rules) lives separately and is not in this repo.
