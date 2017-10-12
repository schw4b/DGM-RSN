# DGM-RSN

## Notebooks with results and figures
- [DGM-RSN](https://rawgit.com/schw4b/DGM-RSN/master/results/DGM-RSN16.nb.html)

## Reproducing full analysis

* Clone this repository.
* Install all packages suggested at the top of the notebook.
* Adjust the `PATH_HOME` and `PATH` variables at the top of the notebooks.
* You may (re)estimate all networks with [`multdyn`](https://cran.r-project.org/web/packages/multdyn/index.html) but the notebook will load the already computed networks.
* As I will not provide the HCP time series, so time-series related chunks need to be disabled for the Notebook to completely run.

## Obtaining the data
#### Network data
* All network data can be produced with [`multdyn`](https://cran.r-project.org/web/packages/multdyn/index.html) or loaded from the `RData` containers in the results folder.

#### Raw time series
* Human RSN time series can be obtained from the Human Connectome Project, Parcellation+Timeseries+Netmats (PTN) from [here](https://db.humanconnectome.org).
