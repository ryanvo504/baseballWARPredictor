# # Project Overview

In this project, we'll predict future season stats for baseball players.  Specifically, we'll predict the wins above replacement (WAR) a player will generate next season. First we download baseball season data using pybaseball and clean it.  We'll do feature selection using a sequential feature selector to identify the most promising predictors for machine learning.  We'll then train a ridge regression model to predict future season WAR.  We'll measure error and improve the model.

We now have a model that can predict future season WAR

**Project Steps**

* Download baseball season data
* Clean the data and prepare it for ML
* Run feature selection
* Create a machine learning model and estimate accuracy
* Improve accuracy

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pybaseball
    * pandas
    * scikit-learn
    * numpy

## Data

We'll download the data during this project, using the `pybaseball` package.
