# Filip Peralov CV Website

This repository contains the published static version of my personal CV website.

The source code is developed separately in a private Nuxt project. This public
repository is intentionally simple: it should contain only the generated HTML,
CSS, JavaScript, and small public-facing files needed for GitHub Pages.

## Website

This site presents my frontend engineering profile, including:

- Career summary
- Technical focus areas
- Position timeline
- Skills snapshot
- Contact flow

## Publishing

The static files are generated from the private source project and copied here
with:

```bash
bun run publish:static
```

The script builds the Nuxt site, copies `.output/public` into this repository,
commits the result, and pushes `main`.

## Notes

- This repository should not contain source-only files, API keys, private
  credentials, or local environment files.
- The GitHub Pages source should be configured to serve from the `main` branch.
