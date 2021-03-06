# Improving public policy by predicting car accident severity using machine learning

This project is part of the [IBM Data Science Certification](https://www.coursera.org/professional-certificates/ibm-data-science) offered via coursera.

*__Disclaimer__: All project ideas are fictitious and serve only the purpose of developing a data science project to access the certification.*


## Table of Contents

- [Introduction](#introduction)
- [Repository contents](#repository-contents)
- [The code](#the-code)
- [Project report](#project-report)





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

      `git clone https://github.com/joseferncruz/coursera-capstone.git`

2) Install a python environment with jupyter notebooks/lab such as the [anaconda distribution](https://www.anaconda.com/products/individual). In order to create an environment with all the required packages, open the annaconda powershell type:  

      `conda env create -f environment.yml`

3) Alternatively install the following required python packages:  

`notebook==6.0.3`  
`sklearn==0.23.1`  
`pandas==1.0.1`  
`numpy==1.18.1`  
`scipy==1.4.1`  
`matplotlib==3.1.3`  
`seaborn==0.11.0`  
`imblearn==0.7.0`


#### B) Run the code on an online executable environment:

1) Load the notebooks on [google colaboratory](https://colab.research.google.com):
- Create a google colaboratory account;
- From an google colab environment, select `file > open notebook > github` and paste the link to this repository.


## Project report


In addition to the interactive Jupyter Notebook, I wrote a report with information about the process that I undertook to complete this project. You can **access** the document **[here](https://docs.google.com/document/d/15EvVyyEokxCvwtYD3CShfXqDteALbU_kGJTnf0WRIVI/edit?usp=sharing).**


---

José Oliveira da Cruz, 2020
