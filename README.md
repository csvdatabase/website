# CSDB Website

This repository contains the static homepage for [csvdatabase.net](https://csvdatabase.net/).

The format specification is published separately at [specs.csvdatabase.net](https://specs.csvdatabase.net/).

## Deployments

The site deploys to GitHub Pages from `.github/workflows/deploy.yml` when a published release uses a major-version tag such as `v1` or `v1.0.0`. Non-major release tags are rejected by the workflow.

The deployed site uses `CNAME` for `csvdatabase.net`.
