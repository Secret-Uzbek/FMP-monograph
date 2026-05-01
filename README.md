# FMP Monograph

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17598953.svg)](https://doi.org/10.5281/zenodo.17598953)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--6394--4912-green)](https://orcid.org/0009-0000-6394-4912)
[![Layer](https://img.shields.io/badge/Layer-Monograph-8b5cf6)](https://github.com/Secret-Uzbek/FMP-monograph)
[![Release](https://img.shields.io/github/v/release/Secret-Uzbek/FMP-monograph?display_name=tag)](https://github.com/Secret-Uzbek/FMP-monograph/releases)
[![Last Commit](https://img.shields.io/github/last-commit/Secret-Uzbek/FMP-monograph)](https://github.com/Secret-Uzbek/FMP-monograph/commits/main)
[![Release Pipeline](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/release-and-publish.yml/badge.svg)](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/release-and-publish.yml)
[![Zenodo Sync](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/zenodo-release.yml/badge.svg)](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/zenodo-release.yml)
[![Terra Audit](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/terra-audit.yml/badge.svg)](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/terra-audit.yml)
[![Monograph Package](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/build-monograph-package.yml/badge.svg)](https://github.com/Secret-Uzbek/FMP-monograph/actions/workflows/build-monograph-package.yml)
[![Central Hub](https://img.shields.io/badge/Central-FMP--CENTRAL--REPO-blue)](https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO)
[![Legal](https://img.shields.io/badge/Legal-terra--legal-0f6b57)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal)

> Long-form monograph layer of the Fractal Metascience Paradigm, holding the
> evolving book-scale research spine and publication-ready monograph material.

## Layer role

This repository is the monograph layer of the Terra / FMP weave.

It should hold:

- the evolving monograph text;
- bibliography and citation-facing material;
- submission guidance and publication preparation files;
- monograph-specific release and DOI surfaces.

It should not act like:

- a flat archive dump;
- a substitute for the theory hub;
- a generic practice repository;
- a random mirror of every session trace.

## Reading path

1. `README.md`
2. `CITATION.cff`
3. `LIVING_INDEX.md`
4. `docs/Living_Map_v1_0.md`
5. `fmp_monograph_revised.md`
6. `main.tex` and bibliography files
7. supporting publication guides and submission files

## Ecosystem position

- `FMP-CENTRAL-REPO` — central public hub
- `Theory-of-fractal-metascience-paradigm` — theory branch
- `FMP-Full-Publication-Package` — article and package layer
- `terra-legal` — donor governance and publication rules

## Layer boundaries

Keep here:

- monograph text and structure;
- monograph-facing bibliography;
- submission and publication preparation for the monograph;
- monograph-specific release bundles.

Do not overload this repository with:

- unrelated practice artifacts;
- donor governance files rewritten without need;
- machine maps as first human entry;
- arbitrary archive debris.

## Build surface

This repository now exposes a dedicated `build-monograph-package` workflow.
It assembles the current primary monograph spine and supporting publication files
into a reusable workflow artifact instead of treating the repository as a flat
dump only.
