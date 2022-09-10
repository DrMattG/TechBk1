# Chapter 1: Management, Research and Experimental Design 
<!-- usage note: edit the H1 title above to personalize the manuscript -->

[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://DrMattG.github.io/TechBk1/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://DrMattG.github.io/TechBk1/manuscript.pdf)
[![GitHub Actions Status](https://github.com/DrMattG/TechBk1/workflows/Manubot/badge.svg)](https://github.com/DrMattG/TechBk1/actions)

## Manuscript description

<!-- usage note: edit this section. -->

This repository contains text for the Wildlife Techniques Manual.

### Subject: Wildlife Techniques Manual Chapter 1 

## Manuscript description

<!-- usage note: edit this section. -->

Chapter 1 of the next edition of the Wildlife Techniques Manual will include issues around open and reproducible science. Given the theme we have decided to write the Chapter using a publically assessable and open-source platform. 

## Important links and dates

**Links**

**Project deadlines**

### Repository directories & files

The directories and main files are as follows:
+ [`/` (`main` root)](https://github.com/DrMattG/TechBk1) this directory contains this document `README.md`, which helps users with the general information about this repository and our project.
+ [`CONTRIBUTING.md`](CONTRIBUTING.md) contains procedures and directions for prospective authors to contribute to this manuscript.
+ [`USAGE.md`](USAGE.md) contains a getting started with Git guidelines, information on formatting text, citing references, adding figures and tables, and other manuscript editing.
+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references and figures.
+ [`R`](R) contains R scripts and RMarkdown documents used to generate figures and tables.
+ [`data`](data) contains files with raw data used in generating some figures and tables.
+ [`output`](output) (and the `output` and `gh-pages` branches) contains the outputs (generated files) from Manubot including the resulting manuscript files (in `HTML`, `PDF`, and other formats).
  You should not edit these files manually, because they will be overwritten by the Manubot.
+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.
+ [`LICENSE.md`](LICENSE.md) and [`LICENSE-CC0.md`](LICENSE-CC0.md) contain the licenses associated with Manubot and with the content we are developing in this project. Please see the "License" section below.

### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations. 
If your pull request build fails, see the CI logs for the cause of failure and revise your pull request accordingly.

When a commit to the `main` branch occurs (for example, when a pull request is merged), CI builds the manuscript and writes the results to the [`gh-pages`](https://github.com/DrMattG/TechBk1/tree/gh-pages) and [`output`](https://github.com/DrMattG/TechBk1/tree/output) branches.
The `gh-pages` branch uses [GitHub Pages](https://pages.github.com/) to host the following URLs:

+ **HTML manuscript** at https://DrMattG.github.io/TechBk1/
+ **PDF manuscript** at https://DrMattG.github.io/TechBk1/manuscript.pdf

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml).

**NOTE**: Currently the CI build process does not run and render R Markdown documents.  For full reproducibility, files in `/R/` need to be 'knit' manually to generate some files needed to build the complete manuscript.

## License

<!--
usage note: edit this section to change the license of your manuscript or source code changes to this repository.
We encourage users to openly license their manuscripts, which is the default as specified below.
-->

[![License: CC BY 4.0](https://img.shields.io/badge/License%20All-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![License: CC0 1.0](https://img.shields.io/badge/License%20Parts-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Except when noted otherwise, the entirety of this repository is licensed under a CC BY 4.0 License ([`LICENSE.md`](LICENSE.md)), which allows reuse with attribution.

Please attribute by TODO 

Since CC BY is not ideal for code and data, certain repository components are also released under the CC0 1.0 public domain dedication ([`LICENSE-CC0.md`](LICENSE-CC0.md)).
All files matched by the following glob patterns are dual licensed under CC BY 4.0 and CC0 1.0:

+ `*.sh`
+ `*.py`
+ `*.yml` / `*.yaml`
+ `*.json`
+ `*.bib`
+ `*.tsv`
+ `.gitignore`

All other files are only available under CC BY 4.0, including:

+ `*.md`
+ `*.html`
+ `*.pdf`
+ `*.docx`


## About Manubot

<!-- usage note: do not edit this section -->

Manubot is a system for writing scholarly manuscripts via GitHub.
Manubot automates citations and references, versions manuscripts using git, and enables collaborative writing via GitHub.
An [overview manuscript](https://greenelab.github.io/meta-review/ "Open collaborative writing with Manubot") presents the benefits of collaborative writing with Manubot and its unique features.
The [rootstock repository](https://git.io/fhQH1) is a general purpose template for creating new Manubot instances, as detailed in [`SETUP.md`](SETUP.md).
See [`USAGE.md`](USAGE.md) for documentation how to write a manuscript.

Please open [an issue](https://git.io/fhQHM) for questions related to Manubot usage, bug reports, or general inquiries.
