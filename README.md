# BGC-Argo Data Calibration & Qualification

The **bgc_argo** module consists of a collection of python-based Jupyter-notebooks design to show how to calibrate and qualify BGC-Argo float data. 

## License

TO DO

## Authors

* [**Gwenaël Caër**] - [CNRS / ODATIS](https://www.odatis-ocean.fr/en/)
* [**Catherine Schmechtig**] - [CNRS / ODATIS](https://www.odatis-ocean.fr/en/)


## Prerequisites

You will require `Jupyter Notebook` to run this code. We recommend that you install the latest [Anaconda Python distribution](https://www.anaconda.com/) for your operating system. Anaconda Python distributions include Jupyter Notebook.

## Installation

The simplest and best way to install these packages is via Git. Users can clone this repository by running the following commands from either their terminal (on Linux/OSx), or from the [Anaconda prompt](https://docs.anaconda.com/anaconda/user-guide/getting-started/). 

Once you have opened a terminal/prompt, you should navigate to the directory where you want to put the code. Once you are in the correct directory, you should run the following command;

`git clone https://gitlab.ifremer.fr/odatis/vre/use-cases/1_bgc_argo.git`

This will make a local copy of all the relevant files.

## Usage

### Python environments

Python allows users to create specific environments that suit their applications. 
This tutorials included in this collection require a number of non-standard packages - e.g. those that are not included by default in Anaconda. In this directory, users will find a *environment.yaml* file which can be used to construct an environment that will install all the required packages.

To construct the environment, you should open either **terminal** (Linux/OSx) or an **Anaconda prompt** window and navigate to repository folder you downloaded in the **Installation** section above. In this folder there is a file called **environment.yml**. This contains all the information we need to install the relevant packages.

To create the environment, run:

`conda env create -f environment.yml`

This will create a Python environment called **odatis_bgc_argo**. The environment won't be activated by default. To activate it, run:

`conda activate odatis_bgc_argo`

Now you are ready to go!

*Note: remember that you may need to reactivate the environment in every new window instance*

### Running Jupyter Notebook

This module is based around a series of [Jupyter Notebooks](https://jupyter.org/). These support high-level interactive learning by allowing us to combine code, text description and data visualisations.

To run Jupyter Notebook, open a terminal or Anaconda prompt and make sure you have activated the correct environment. Again, navigate to the repository folder.

Now you can run Jupyter using:

`jupyter notebook` or `jupyter-notebook`, depending on your operating system.

This should open Jupyter Notebooks in a browser window. On occasion, Jupyter may not be able to open a window and will give you a URL to past in your browser. Please do so, if required.

*Note: Jupyter Notebook is not able to find modules that are 'above' it in a directory  tree, and you will unable to navigate to these. So make sure you run the line above from the correct directory!*

Now you can run the notebooks! We recommend you start with the [index](./index.ipynb) module.

<hr>
<hr>

### Overview for advanced users

**Installation:**

`git clone https://gitlab.ifremer.fr/odatis/vre/use-cases/1_bgc_argo.git`

**Create and set environment**

`conda env create -f environment.yml` \
`conda activate odatis_bgc_argo`

`ipython kernel install --user --name=odatis_bgc_argo`

**Run**

`jupyter notebook` or `jupyter-notebook`