# Improving public policy by predicting car accident severity using machine learning


This project is part of the [IBM Data Science Certification](https://www.coursera.org/professional-certificates/ibm-data-science) offered via coursera.

*__Disclaimer__: All project ideas are fictitious and serve only the purpose of developing a data science project to access the certification.*


## Table of Contents

- [Introduction](#introduction)
- [Repository contents](#repository-contents)
- [The code](#the-interactive-code)




---
## Introduction

In this project, I used publicly available data from the Seattle Police Department to understand the problem and develop metrics that can be used to reduce car accident severity. Results from this project could be used to design and implement new public policies aiming at reducing injury-related accidents.
To execute this project

Briefly, to tackle this issue I performed exploratory data analysis and developed a machine learning model to understand and predict accident accident's severity using different data attributes such as weather, road condition, date, individuals involved, among others.

The execution of this project followed the [**Cross Industry Standard Process for Data Mining (CRISP-DM)**](https://www.sv-europe.com/crisp-dm-methodology/) methodology.

This project is based on publicly available data collected by the Seattle Police Department and recorded by [Traffic Records](https://data-seattlecitygis.opendata.arcgis.com/datasets/collisions).


## Repository contents

In the folder `notebooks/` you can find the complete notebook used for exploratory data analysis and modeling:  

`notebooks/ibm_capstone_nb01.ipynb`

The dataset used is located under the directory `datasets/` and the metadata associated is located under the directory `docs/`:  

`datasets/collisions_data.csv`  
`docs/collisions_metadata.pdf`


## The code

This project was executed using python 3 and jupyter notebooks.


#### A) Run the code a local machine:

1) Download or clone this repository using [git](https://git-scm.com/downloads) on bash:  

      git clone https://github.com/joseferncruz/coursera-capstone.git

2) Install a python environment with jupyter notebooks/lab such as the [anaconda distribution](https://www.anaconda.com/products/individual).

3) Install the required python packages:  

`notebook==6.0.3`  
`sklearn==0.23.1`  
`pandas==1.0.1`  
`numpy==1.18.1`  
`scipy==1.4.1`  
`matplotlib==3.1.3`  
`seaborn==0.11.0`  
`imblearn==0.7.0`


#### B) Run the code an online executable environment:

1) Load this repository on [Binder](https://mybinder.org/v2/gh/joseferncruz/coursera-capstone/master).  

2) Load the notebooks on [google colaboratory](https://mybinder.org/v2/gh/joseferncruz/coursera-capstone/master):
- Create a google colaboratory account;
- From an google colab environment, select `file > open notebook > github` and paste the link to this repository.


---
José Oliveira da Cruz, 2020
