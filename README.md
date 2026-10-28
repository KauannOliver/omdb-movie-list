# OMDb Movie List

A static browser app for searching movie information through the OMDb API and saving a personal list in browser storage.

## Features

- Search by title and optional release year.
- View details returned by OMDb.
- Add or remove titles from a `localStorage` list.

## Stack

HTML, CSS, JavaScript, and the OMDb API.

## Run locally

Serve the repository directory with `python -m http.server 8000` and open `http://localhost:8000`. The current `js/key.js` contains a placeholder; add your own OMDb API key locally to use search. Browser-side API keys are visible to users, so do not reuse a sensitive key or commit a real one.




## Snapshot review

Setup and capabilities are based on the included code. External services and operating-system-specific integrations were not exercised during this publication review. Use synthetic data in a separate local environment.

Git-triggered Vercel deployment is disabled in the included web configurations. This update publishes source and documentation only.

## License

Original application code is available under the [MIT license](LICENSE). Third-party libraries, models, fonts and bundled assets retain their own licenses.

## Verification record

See [snapshot checks and remaining limitations](docs/VERIFICATION.md).
