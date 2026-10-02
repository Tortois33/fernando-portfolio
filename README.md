# Fernando Nicolas Jr. Portfolio

Static portfolio site for **Fernando Nicolas Jr.**

- Primary domain: https://porfoliokoto.online/
- Repository: `Tortois33/fernando-portfolio`
- Main entry point: `index.html`
- Custom domain declaration: `CNAME`

## Deployment

The repository includes a GitHub Pages workflow at `.github/workflows/pages.yml`. It publishes the repository root whenever `main` changes.

GitHub requires Pages to be enabled for the repository and configured to use **GitHub Actions** as the publishing source. The `CNAME` file alone does not configure the custom domain in repository settings.

After Pages is enabled, set the custom domain to:

```
porfoliokoto.online
```

Then configure the domain's DNS records according to GitHub Pages' custom-domain instructions and enable HTTPS once GitHub finishes verifying the domain.

## Validation

`.github/workflows/validate.yml` checks the production HTML, `CNAME`, duplicate IDs, JavaScript syntax, embedded résumé marker, canonical URL, and the Vanguard project URL on pushes and pull requests.

## Project notes

The portfolio is intentionally a dependency-free static site. The résumé and profile imagery are embedded directly into `index.html`, so the live deployment does not depend on separate asset files.
