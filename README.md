# AWA Pilot MVP decision board

A public, standalone HTML reading board for the AWA pilot MVP decision record.

## View locally

```sh
python3 -m http.server 8765 --directory site
```

Open `http://localhost:8765`.

## Deploy

Pushing `main` deploys `site/` to GitHub Pages. The published page is intentionally self-contained: it has no remote assets or runtime dependencies.
