# STW Mod Configurator

Local-first static configurator for building STW Arma Reforger profile ZIPs.

## Run locally

Serve this folder with any static server (for example `python -m http.server`). No build step or dependencies are required. If you open `index.html` directly and the browser blocks local fetches, use the in-page **Choose the STW folder** fallback to load the reference JSON files with a folder picker.

## Export format

The browser download contains:

```text
STW/<profile-name>/
├── profile.json
├── <enabled-module>.json
└── README.txt
```

All export work is performed locally in the browser; no profile data is uploaded.
