# OJS Zenodo DOI

The purpose of this notebook is to generate [Zenodo](https://zenodo.org/) [DOIs](https://www.doi.org/) for the [Open Journal Systems](https://pkp.sfu.ca/ojs/) publishing system.

DOIs historically have had a monetary cost that an open access, no publication fee journal may find unsupportable.

Zenodo solves this problem by providing DOIs free of charge and permanently archiving journal publications at the same time. [Zenodo is an initiative for open science funded and maintained by EU as part of CERN](https://en.wikipedia.org/wiki/Zenodo).

This notebook requires Jupyter with [F# support](https://github.com/fsprojects/IfSharp), which may require [additional installation of libraries depending on your operating system](https://fsharp.org/).
Alternatively, this notebook can be used in the web browser without installing any software through the [Azure Notebooks](https://notebooks.azure.com/) service.
Additional libraries include [F# Data](https://fsharp.github.io/FSharp.Data/) and [Json.NET](https://www.newtonsoft.com/json).

The focus of this notebook is to upload extract the relevant metadata from OJS, upload the metadata and journal articles to Zenodo, and obtain DOIs through the [Zenodo API](https://developers.zenodo.org/#rest-api).
