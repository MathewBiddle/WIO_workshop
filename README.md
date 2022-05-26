# WIO_workshop
This repository contains materials for the [Regional Training Workshop on Observing the Coastal and Marginal Seas in the Western Indian Ocean](https://www.clivar.org/events/regional-training-workshop-observing-coastal-and-marginal-seas-western-indian-ocean) 
session on best practices including data standards and quality assurance.

The tutorial provided herein discusses the [ioos_qc](https://github.com/ioos/ioos_qc) package, providing background on [QARTOD](https://ioos.noaa.gov/project/qartod/),
and exemplifying the importance of standards and data sharing using tools like [ERDDAP](https://coastwatch.pfeg.noaa.gov/erddap/index.html).

Slides are generated from the [Jupyter Notebook](https://github.com/MathewBiddle/WIO_workshop/blob/main/Western-Indian-Ocean-Workshop-ioos_qc-demo.ipynb) and hosted online using [GitHub Pages](https://pages.github.com/) at the following url: 
<https://mathewbiddle.github.io/WIO_workshop/Western-Indian-Ocean-Workshop-ioos_qc-demo.slides.html>

To generate the slides using [nbconvert](https://nbconvert.readthedocs.io/en/latest/usage.html) and the notebook in this
repository, run:
```shell
jupyter nbconvert Western-Indian-Ocean-Workshop-ioos_qc-demo.ipynb --output-dir=./docs --to slides --SlidesExporter.reveal_theme=simple --SlidesExporter.theme=light --SlidesExporter.reveal_scroll=True --SlidesExporter.reveal_transition=slide --SlidesExporter.reveal_number=c/t
```

