# Strategic classification made practical reproduction

* Strategic classification:  the problem of learning in settings where users can strategically modify their features to improve outcomes.
* The contribution of the original author: a flexible, practical and socially-aware framework for learning in strategic environments.
* Our addition: A combined dataset where some users are gaming and some are not.

## Description

Strategic classification regards the problem of learning in settings where users can strategically modify their features to improve outcomes. This setting applies broadly and has received much recent attention. But despite its practical significance, work in this space has so far been predominantly theoretical. The original authors presented a learning framework for strategic classification that is practical. Our approach directly minimizes the "strategic" empirical risk, achieved by differentiating through the strategic response of users. This provides flexibility that allows us to extend beyond the original problem formulation and towards more realistic learning scenarios.

## Requirements
Setup the environment using 
```setup
conda create --name "name"
conda activate "name"
pip install -r requirements.txt
pip install jupyter
jupyter notebook
```
Download the card fraud dataset from https://www.kaggle.com/mlg-ulb/creditcardfraud and put it in the data folder

## Training and Evaluation
Use the Reproduction plots.ipynb to create the plots with the saved models
Run a notebook from start to finish to train the model and get the evaluation

## Original Authors
Sagi Levanon  
[@SagiLevanon](sagilevanon@campus.technion.ac.il)

Nir Rosenfeld  
[@NirRosenfeld](nirr@cs.technion.ac.il)

## notes

* If the environment file doesn't work you need to manually install the modules

## Acknowledgments

* [cvxpylayers](https://github.com/cvxgrp/cvxpylayers)
