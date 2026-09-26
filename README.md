# Suraj Yadav — Portfolio

A small static portfolio site built with HTML and CSS. It summarizes frontend work and provides contact links; it has no JavaScript build step or application backend.

**Live site:** [surajy93.github.io/surajy](https://surajy93.github.io/surajy/)

## Run locally

From the repository root, start Python's built-in static file server:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

## Structure

- `index.html` — portfolio content and page metadata.
- `style.css` — page styles.

The page includes previews of three frontend design exercises stored in [`system_design_frontend`](https://github.com/surajy93/system_design_frontend). Those images load from that public repository; the page labels them as study artifacts, not shipped products.

The site is published with GitHub Pages from the `main` branch root. There is no dependency installation or build command.

## License

See [`LICENSE`](LICENSE) (GNU General Public License v3.0).
