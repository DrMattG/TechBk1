# Chapter 1: Management, Research and Experimental Design 

[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://DrMattG.github.io/TechBk1/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://DrMattG.github.io/TechBk1/manuscript.pdf)
[![GitHub Actions Status](https://github.com/DrMattG/TechBk1/workflows/Manubot/badge.svg)](https://github.com/DrMattG/TechBk1/actions)

## Manuscript description

<!-- usage note: edit this section. -->

This repository contains text for the Wildlife Techniques Manual.

### Subject: Wildlife Techniques Manual Chapter 1 

## Manuscript description

<!-- usage note: edit this section. -->

Chapter 1 of the next edition of the Wildlife Techniques Manual will include issues around open and reproducible science. Given the theme we have decided to write the Chapter using a publicly assessable and open-source platform. 

## Philosophy of the 9th Edition

Philosophy of the 9th Edition:
The Wildlife Techniques Manual has been the cornerstone book on field, laboratory, and 
quantitative techniques for almost 60 years. The goals for the book are (1) to provide 
wildlife biologists (current and new) with expert advice and guidance on broadly used 
methods (i.e., not niche methods) for research and management, (2) to provide students in 
college courses with resource material to support learning exercises in their courses, and 
(3) to serve as an accepted set of best practices for techniques for research and 
management in the wildlife profession. The book will cover aspects of study design, 
management planning, animal capture and handling and identification, sampling 
populations, harvest management, habitat management, and laboratory techniques for 
studies in genetics and physiology.

We aspire to develop chapters with our authors that will (1) remain focused on the 
learning goals for the chapter, (2) represent holistic ecosystem management approaches to 
model best practices to the profession, and (3) fit decision-making frameworks that allow 
students and professionals to see how the modeled techniques or ideas relate back to 
advancing the ability of our profession to support effective and successful management 
decisions. 

Certainly, the Wildlife Techniques Manual serves as a review document. Despite challenges 
with the turnaround time for writing and publishing, we wish our authors to push new 
ideas or frameworks in the chapters to spur growth and thought in our field of study.
Outcomes for book:
+ to provide wildlife biologists (current and new) with expert advice and guidance on broadly used methods (i.e., not niche methods) for research and management
+ to provide students in college courses with resource material to support learning exercises in their courses
+ to serve as an accepted set of best practices for techniques for research and management in the wildlife profession to look to the future

## Structure for Chapters and On-line Support Material

Chapter Introduction:

Each chapter will start with a list of goals for the chapter, a chapter summary, and a short 
problem-case. The latter is primarily intended to be used by college/university students as 
a first step towards thinking about the material found in the chapter, to provide context. 
However, we have also structured the chapter introduction to be useful for current 
professionals who are using the book to learn about a new technique.

Chapter Structure and Challenge to Authors:

Authors will be asked to provide a concise, logical structure to the material in each chapter 
so that the objectives for the chapter define what is included. In addition, each chapter will 
be written in the context of management (decision-making) to provide clear connections 
between the methods and techniques described and the needs of managers to manage 
people, wildlife populations, and habitat. Specifically, authors will be challenged to provide 
clear descriptions of guiding principles, frameworks, and other decision-making rubrics or 
guides that are used by wildlife biologists and managers in that particular area of study. 
Authors will end chapters with a short list of additional resources, which point readers 
needing further details to other publications.

On-line Support Materials:

For use by instructors who have adopted the textbook for course in wildlife science or 
wildlife techniques, we propose to provide all images used in the chapter, for easy inclusion 
in instructors’ class presentations. We also will challenge each set of authors to develop 
one 15- to 30-minute active learning exercise (role playing, group problem solving, 
scenario development, decision exercise, or similar) to be used to complement the material 
found in the chapter.


## Important links and dates

**Links**


**Project deadlines**

Each week: Submit a pull request once a week. 

September 24th : My initial outline was a placeholder more than a template. I would like for you to update the outline for your section and write a sentence or two descriptions for each subsection. This will let the rest of know what you plan to cover. Each section leader should work with your coauthors and me on content decisions. If deemed necessary, we can have a group call at this point. 

November 1: ~Half draft of chapter. 

December 1: Full draft of chapter.


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
