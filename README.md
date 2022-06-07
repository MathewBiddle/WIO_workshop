
[![DOI](https://zenodo.org/badge/495949275.svg)](https://zenodo.org/badge/latestdoi/495949275)


# Western Indian Ocean (WIO) Workshop
This repository contains materials for the [Regional Training Workshop on Observing the Coastal and Marginal Seas in the Western Indian Ocean](https://www.clivar.org/events/regional-training-workshop-observing-coastal-and-marginal-seas-western-indian-ocean) 
session on best practices including data standards and quality assurance.

The tutorial provided herein discusses the [ioos_qc](https://github.com/ioos/ioos_qc) package, providing background on 
[QARTOD](https://ioos.noaa.gov/project/qartod/), and exemplifying the importance of standards and data sharing using 
tools like [ERDDAP](https://coastwatch.pfeg.noaa.gov/erddap/index.html). The tutorial is based on the [example ioos_qc notebook](https://ioos.github.io/ioos_code_lab/content/code_gallery/data_analysis_and_visualization_notebooks/2020-02-14-QARTOD_ioos_qc_Water-Level-Example.html) 
provided in the [IOOS CodeLab](https://ioos.github.io/ioos_code_lab/content/intro.html), which is a collection of 
tutorials and examples of how to access and utilize the many IOOS technologies and data sources available.

Slides are generated from the [Jupyter Notebook](https://github.com/MathewBiddle/WIO_workshop/blob/main/Western-Indian-Ocean-Workshop-ioos_qc-demo.ipynb) 
and hosted online using [GitHub Pages](https://pages.github.com/) at the following url: 
<https://mathewbiddle.github.io/WIO_workshop/Western-Indian-Ocean-Workshop-ioos_qc-demo.slides.html>

You can run and interact with the notebook via [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MathewBiddle/WIO_workshop/HEAD?labpath=Western-Indian-Ocean-Workshop-ioos_qc-demo.ipynb)

To generate the slides using [nbconvert](https://nbconvert.readthedocs.io/en/latest/usage.html) and the notebook in this
repository, run:
```shell
jupyter nbconvert Western-Indian-Ocean-Workshop-ioos_qc-demo.ipynb --output-dir=./docs --to slides --SlidesExporter.reveal_theme=simple --SlidesExporter.theme=light --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_transition=slide --SlidesExporter.reveal_number=c/t
```

