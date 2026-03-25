# AGENTS.md

## Cursor Cloud specific instructions

This is a **static single-page HTML site** (`index.html`) with zero dependencies — no package manager, no build step, no JavaScript, no backend.

### Running the site

Serve with any static HTTP server, e.g.:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080` in a browser.

### Lint / Test / Build

- **No linter, test framework, or build tool is configured.** HTML validation can be done with an external validator if needed.
- There is no `package.json`, `Makefile`, or CI config.
