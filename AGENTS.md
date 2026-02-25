# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub Profile README** containing only `README.md` and `LICENSE`. There is no application code, build system, test suite, or runtime dependencies.

### Linting

Run markdown linting with:

```
markdownlint README.md
```

Note: The README uses inline HTML (badges, `<div>`, `<img>`, `<p>`, `<a>`) which triggers MD033 warnings, and long badge URLs trigger MD013 warnings. These are expected and intentional for a GitHub Profile README.

### Previewing

To preview the rendered README locally, open it in a browser using a markdown renderer or view it directly on GitHub. The README relies on external badge services (shields.io, readme-typing-svg, github-readme-stats, etc.) which require network access to render properly.
