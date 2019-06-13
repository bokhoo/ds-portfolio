
# Data Science, Machine Learning and AI portfolio

- [Data Science, Machine Learning and AI portfolio](#data-science-machine-learning-and-ai-portfolio)
  - [Introduction](#introduction)
  - [Full Stack Data Science](#full-stack-data-science)
  - [Workflow (CRISP-DM)](#workflow-crisp-dm)
    - [1. Business Understanding](#1-business-understanding)
    - [2. Data Understanding](#2-data-understanding)
    - [3. Data preparation](#3-data-preparation)
    - [4. Modelling](#4-modelling)
    - [5. Evaluation](#5-evaluation)
    - [6. Deployment](#6-deployment)
  - [Directory Organisation](#directory-organisation)

## Introduction
As an aspiring Data Scientist and experienced Data Engineer, wanted to build personal Data Science and Machine Learning portfolio to share learnings, experiences and collaborate with people who have the same interest in this field. 

## Full Stack Data Science
Recently, came across many articles and discussion around Full Stack Data Science, what does it mean and how it works. It sounds quite mystery and challenging. However, it quite possible and easy for someone who has experiences and skills in both Data Engineering and Full Stack Developer roles. 

In terms of Full Stack Data Science, it's basically meant to develop end-to-end data science product to solve business problems which sounds not really a new concept, but since more and more Data Science projects are moving into the cloud and many steps within data science project are becoming automated made this concept popular and essential. 

On top of that, developing and deploying continuously (CI/CD), tuning and monitoring models are becoming essential skills for Data Scientist or Data Engineers who work in this field.

## Workflow (CRISP-DM)
Its believed that having well-organised workflow and best practices are helpful to meet a deadline in a Data Science project.

### 1. Business Understanding
### 2. Data Understanding
### 3. Data preparation 
### 4. Modelling
### 5. Evaluation
### 6. Deployment


## Directory Organisation

------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
