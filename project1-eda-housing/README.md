# Project 1: Exploratory Data Analysis - King County Housing Dataset

This repository contains the analysis of the publicly available King County Dataset documented. This short project was carried out as part of the Spiced Data Science Bootcamp curriculum.  

### Provided files

* assignment.md - goals and deliverables
* column_names.md - clarification of column names
* Exploratory_data_analysis.ipynb - Jupyter notebook documenting the exploratory analysis workflow and the main results

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies needed to replicate the analysis. 

Before installing the virtual environment, make sure to install postgresql if you haven't done it before.

```bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
