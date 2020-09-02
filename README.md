ML_projects
==============================
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/loulouds/ML_projects/master?filepath=notebooks)

Selection of [Jupyter](https://jupyter.org/) notebooks to for some machine learning projects on fraud detection.

### Requirements
To be able to run the notebooks locally, you need to have [Python](www.python.org) installed.

A simple way to manage Python environment is to install [Conda package manager](https://conda.io/en/latest/)


### Quickstart

- Clone or download the repository
```
git clone https://github.com/loulouds/ML_projects.git
```

- Assuming that you have [Conda](https://conda.io/en/latest/) installed, create and activate the Conda environment *ML_projects* containing the relevant python libraries (the creation of the environment can take a few minutes):
```
cd ML_projects
conda env create -f environment.yml
conda activate ML_projects
```

- Run Jupyter notebook
```
cd notebooks
jupyter-lab
```
