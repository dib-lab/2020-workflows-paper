# Streamlining data-intensive biology with workflow systems

[![GitHub Actions Status](https://github.com/greenelab/covid19-review/workflows/Manubot/badge.svg)](https://github.com/dib-lab/2020-workflows-paper/actions)


## Current Manuscript

PDF: [![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://dib-lab.github.io/2020-workflows-paper/manuscript.pdf)

HTML: [![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://dib-lab.github.io/2020-workflows-paper/)



## Code of Conduct

This project operates under a code of conduct.
Participating in the project in any way (issues, pull requests, gitter, or other media) indicates that you agree that you will follow the [code of conduct](CODE_OF_CONDUCT.md).
We take this very seriously.
If you experience harassment or notice violations of the code of conduct, please raise the issue to one of the project organizers (@taylorreiter or @bluegenes).


## Project Description
<!-- usage note: edit this section. -->

As the scale of biological data generation has increased, the bottleneck of research has shifted from data generation to analysis. Researchers commonly need to build computational workflows that include multiple analytic tools and require incremental development as experimental insights demand tool and parameter modifications. 
Data-centric workflow systems can alleviate some of these challenges, but knowledge of and training in these techniques is still lacking. Our goal is to generate a helpful set of strategies for leveraging workflow systems to streamline large-scale biological analyses. 

[Our initial version](https://github.com/bluegenes/2020-latex-gep) has been much improved through iterations of feedback primarily from members and friends of the [DIB-lab](http://ivory.idyll.org/lab/). 
While the practices are written with specific examples for high-throughput sequencing data, we hope many of the perspectives and guidance provided by the document apply more generally to all workflow-enabled biology. 

This repository is a living document (written with [manubot](https://manubot.org/)) that aims to consolidate and integrate helpful information about workflow systems and their applications in data-intensive biology.
**We welcome constructive feedback from workflow-enabled biologists of all levels anywhere in the world.**


## Contributions

You'll need to make a free [GitHub account](https://github.com/join?source=header-home).

Instructions and procedures for contributing are [outlined here](CONTRIBUTING.md).

We will follow the [ICMJE Guidelines](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html) for determining authorship.

## Pull Requests

If you are not familiar with git and GitHub, you can use [these directions](INSTRUCTIONS.md) to start contributing.

Please feel encouraged to ask questions by opening a [Request for Help issue](https://github.com/dib-lab/2020-workflows-paper/issues/new?assignees=rando2&labels=&template=request-for-help.md&title=Help%3A+%5BAdd+topic+here%5D)
[![GitHub issues](https://img.shields.io/github/issues-raw/dib-lab/2020-workflows-paper?label=Open%20Issue&style=social)](https://github.com/dib-lab/2020-workflows-paper/issues/new/choose)

This project is a collaborative effort that will benefit from the expertise of scientists across a wide range of workflow applications!

## Manubot
<!-- usage note: do not edit this section -->

Manubot is a system for writing scholarly manuscripts via GitHub.
Manubot automates citations and references, versions manuscripts using git, and enables collaborative writing via GitHub.
An [overview manuscript](https://greenelab.github.io/meta-review/ "Open collaborative writing with Manubot") presents the benefits of collaborative writing with Manubot and its unique features.
The [rootstock repository](https://git.io/fhQH1) is a general purpose template for creating new Manubot instances, as detailed in [`SETUP.md`](SETUP.md).
See [`USAGE.md`](USAGE.md) for documentation how to write a manuscript.

Please open [an issue](https://git.io/fhQHM) for questions related to Manubot usage, bug reports, or general inquiries.

## Repository directories & files

+ This file is called [`README.md`](README.md)
It is the centralized document for the repository and will help direct users to other relevant information.
+ [`CONTRIBUTING.md`](CONTRIBUTING.md) contains procedures and directions for contributing to this effort.
+ [`INSTRUCTIONS.md`](INSTRUCTIONS.md) contains instructions for new GitHub users for how to navigate GitHub in the browser as well as GitHub vocabulary.
It also includes some instructions for more experienced users about the procedures we recommend and how to run manubot on the command line.
+ [`USAGE.md`](USAGE.md) describes formatting instructions for formatting text, citing references, adding figures and tables, etc.
+ [`SETUP.md`](SETUP.md) includes information about setting up manubot
+ [`LICENSE.md`](LICENSE.md) and [`LICENSE-CC0.md`](LICENSE-CC0.md) contain the licenses associated with manubot and with the content we are developing in this project. Please see the "License" section below.

The directories are as follows:

+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references. 
These are the files that most contributors will be editing.
  See [`USAGE.md`](USAGE.md) for more information.
+ [`output`](output) contains the outputs (generated files) from Manubot including the resulting manuscripts.
  You should not edit these files manually, because they will get overwritten.
+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.

## License

<!--
usage note: edit this section to change the license of your manuscript or source code changes to this repository.
We encourage users to openly license their manuscripts, which is the default as specified below.
-->

[![License: CC BY 4.0](https://img.shields.io/badge/License%20All-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![License: CC0 1.0](https://img.shields.io/badge/License%20Parts-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Except when noted otherwise, the entirety of this repository is licensed under a CC BY 4.0 License ([`LICENSE.md`](LICENSE.md)), which allows reuse with attribution.
Please attribute by linking to https://github.com/dib-lab/2020-workflows-paper.

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

Please open [an issue](https://github.com/manubot/rootstock/issues) for any question related to licensing. 

## Attribution

Many of the documents (especially `*.md` documents) and issues presented in this repository were modified from [another manubot repository](https://github.com/greenelab/covid19-review).
