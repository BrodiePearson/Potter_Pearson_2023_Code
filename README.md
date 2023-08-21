# Potter & Pearson (2023) Analysis Code
A repository containing analysis code for **Potter &amp; Pearson 2023** (*"Assessing the global ocean science community: Understanding international collaboration, concerns, and the current state of ocean basin research"*) published in *npj Ocean Sustainability*

## How to use this repository

The two Notebooks are numbered and available in the *Notebook* directory. The notebooks should be run them in sequential order. 

### The first notebook (*01_api_extraction-github*) 

This notebook contains the ocean basin terms for searching Web of Science using its extended API. An API access key is required to run such a search. See [this website](https://developer.clarivate.com/apis) for more information. The notebook will return a data frame of all relevant articles, which will be used for analyses in the second notebook.

### The second notebook (*02_analysis-github*)

This notebook will produce the figures and tables in the paper and supplementary material. Note that additional information from UNESCO ([GERD](http://data.uis.unesco.org/index.aspx?queryid=74#); and [researchers per million inhabitants](http://data.uis.unesco.org/index.aspx?queryid=3685)) and [InCites](https://incites.clarivate.com/) is required to complete some analyses.

This repository can be cited via ![DOI](https://zenodo.org/badge/679380409.svg)](https://zenodo.org/badge/latestdoi/679380409)
