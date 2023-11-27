# Pip installation in DATALAB's basic jupyterlab

## Official Documentation

Package installation is well documented in the [official documentation](https://www.datalabs.esa.int/help), at the  ["getting started with jupyter datalabs" helppage](https://s2e2.cosmos.esa.int/www/esadatalabs_iapplications/Getting_started_with_Jupyter_datalabs.html).


## Workaround

Incase the above documentation should not work, the following is a (non recommended) workaround.
The python environment in DATALAB's jupyterlab is essentially a conda environment.
To install further python packages the following should be done:

## 1. Intial setup
In an .ipynb the following command should be run once at the start of the jupyterlab. In the future this might not be necessary anymore

```bash
!conda init

```
## 2. Further package installation
Further packages can now be installed either via the terminal, or more easily directly from a notebook to the environment. In this example drizzle , astropy and scipy.

```bash

!/opt/miniconda/bon/python -m pip install drizzle, astropy, scipy

```
These packages will then be installed to the following path. There they can be modified, if necessary. 

```bash

/home/{YOURUSERNAME}/.local/lib/python3.XX/site-packages

```