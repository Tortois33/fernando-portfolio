# Fernando Nicolas Jr. Portfolio

Static portfolio site for **Fernando Nicolas Jr.**

- Primary domain: https://portfoliokoto.online/
- Repository: `Tortois33/fernando-portfolio`
- Main entry point: `index.html`
- Custom domain declaration: `CNAME`

## Deployment

GitHub Pages is already enabled for this repository and publishes the static site from `main`. The custom-domain declaration is stored in `CNAME` as:

```
portfoliokoto.online
```

GitHub's built-in Pages deployment handles publishing, so the repository intentionally does not include a second custom Pages deployment workflow.

## Validation

`.github/workflows/validate.yml` checks the production HTML, `CNAME`, duplicate IDs, JavaScript syntax, embedded résumé marker, canonical URL, and the Vanguard project URL on pushes and pull requests.

## Project notes

The portfolio is intentionally a dependency-free static site. The résumé and profile imagery are embedded directly into `index.html`, so the live deployment does not depend on separate asset files.
