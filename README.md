# Acoustic Geometry and Sound-Ray Dynamics in Relativistic Spherical Accretion

This repository contains the preprint, LaTeX source, bibliography, and figures
for:

> Alexander V. Semyannikov, “Acoustic Geometry and Sound-Ray Dynamics in
> Relativistic Spherical Accretion” (2026).

## Abstract

This work studies the relativistic acoustic metric of spherical Michel
accretion onto a Schwarzschild black hole and treats high-frequency sound rays
as null geodesics of the effective spacetime. It identifies the acoustic
horizon, stationary-limit surface, and ergoregion; derives a generalized Binet
equation for sound-ray deflection; compares acoustic and vacuum Shapiro delays;
locates the acoustic photon sphere; and relates the analogue Hawking scale to
hydrodynamic gradients. Results are presented for polytropic indices
`γ = 4/3` and `γ = 5/3`.

## Repository contents

- `article.pdf` — compiled preprint
- `article.tex` — LaTeX source
- `article.bib` — bibliography database
- `figs/` — figures used in the article
- `CITATION.cff` — machine-readable citation metadata
- `.zenodo.json` — Zenodo deposit metadata

## Building the article

A TeX distribution with `latexmk`, BibTeX, and the `elsarticle` document class
is required. Build the PDF from the repository root with:

```sh
latexmk -pdf article.tex
```

To remove generated auxiliary files:

```sh
latexmk -c
```

## Citation

Please use the metadata in `CITATION.cff` when citing this work. A DOI will be
added after the first Zenodo release.

## License

The article, its source, and the accompanying figures are licensed under the
Creative Commons Attribution 4.0 International License (CC BY 4.0). See
`LICENSE` for details.
