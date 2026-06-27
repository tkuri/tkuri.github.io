# tkuri.github.io

Personal homepage for Teppei Kurita, built as a single-page Quarto website and published with GitHub Pages.

Live site:

https://tkuri.github.io/

## Overview

This repository contains a clean academic / engineering profile site focused on image sensor R&D, AI signal processing, and computational imaging.

The site is intentionally compact:

- One-page homepage: `index.qmd`
- Custom styling: `styles.css`
- Static output for GitHub Pages: `docs/`
- Quarto project configuration: `_quarto.yml`
- GitHub Pages compatibility file: `.nojekyll`

## Local Preview

If `quarto` is available on your `PATH`:

```powershell
quarto render
quarto preview
```

On this Windows environment, Quarto may need to be run directly:

```powershell
& "$env:LOCALAPPDATA\Programs\Quarto\bin\quarto.exe" render
& "$env:LOCALAPPDATA\Programs\Quarto\bin\quarto.exe" preview
```

## Publishing

The Quarto output directory is `docs/`.

GitHub Pages should be configured to publish from:

- Branch: `main`
- Folder: `/docs`

After editing source files, run:

```powershell
& "$env:LOCALAPPDATA\Programs\Quarto\bin\quarto.exe" render
```

Then commit both the source changes and regenerated `docs/` files.

## Content Guidelines

Keep the public page concise and based only on public information.

Do not include employer-confidential information, customer names, unpublished product names, internal organization details, performance numbers, or unpublished patent ideas.

Keep education and employment history abstracted. Do not add employer names, past employer names, university names, degrees, departments, internal role history, or employment periods, except for the approved Visiting Researcher experience at UCLA.

The IPSJ SIG-CVIM activity is listed as `Apr. 2021 - Mar. 2026`; do not change it to `present` or `current`.

Do not list papers or patents exhaustively on the site. Use Google Scholar and Google Patents links instead.
