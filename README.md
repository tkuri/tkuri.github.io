# tkuri.github.io

Single-page personal homepage built with Quarto for GitHub Pages.

## Local Preview

```powershell
quarto render
quarto preview
```

If `quarto` is not on your Windows `PATH`, use the installed executable directly:

```powershell
& "$env:LOCALAPPDATA\Programs\Quarto\bin\quarto.exe" render
& "$env:LOCALAPPDATA\Programs\Quarto\bin\quarto.exe" preview
```

The site is configured to render into `docs/`, so GitHub Pages can publish from the `main` branch and `/docs` folder.

## Before Publishing

Replace placeholders in `index.qmd` and `_quarto.yml`:

- `[Your Name]`
- `YOUR_GOOGLE_SCHOLAR_ID`
- `YOUR_NAME_PLACEHOLDER`
- `YOUR_KAGGLE_USERNAME`
- `YOUR_GITHUB_USERNAME`
- `YOUR_LINKEDIN_ID`
- `YOUR_ORCID_ID`
- `YOUR_RESEARCHMAP_ID`
- `<github-username>`

Do not include confidential employer information, unpublished product names, customer names, internal organization details, unreleased performance data, or unpublished patent ideas.

Keep education and employment history abstracted on the public page. Do not add employer names, past employer names, university names, degrees, departments, internal role history, or employment periods, except for the approved Visiting Researcher experience at UCLA.

The IPSJ SIG-CVIM activity is listed as `Apr. 2021 – Mar. 2026`; do not change it to `present` or `current`.
