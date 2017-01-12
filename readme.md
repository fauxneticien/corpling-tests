# CorpLing Tests

This repository hosts a series of tests/experiments exploring various platforms for delivering corpus material and import/processing pipelines to prepare material for the platforms.

The goal will be to assess the overall ease of use for both deployment of the system as well as conversion of legacy materials into the forms required for import.

## Notes

### Organisation

The repository is organised as a [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) project (see link for documentation of overall directory structure; additionally, each directory also has accompanying descriptions in their `readme.md`).

### Dependencies/raw data

For testing, data and dependencies have been included in the current repository. During development, `/dependencies` and `/data/raw` should be placed in `.gitignore` and each developer should manage their own local copies of the data and dependencies as symlinks to appropriate locations (e.g. raw data may be sourced from a local Dropbox path, or attached from an S3 bucket).
