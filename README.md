# Strategic classification made practical reproduction

* Strategic classification:  the problem of learning in settings where users can strategically modify their features to improve outcomes.
* Our contribution: a flexible, practical and socially-aware framework for learning in strategic environments.

## Description

Strategic classification regards the problem of learning in settings where users can strategically modify their features to improve outcomes. This setting applies broadly and has received much recent attention. But despite its practical significance, work in this space has so far been predominantly theoretical. The original authors presented a learning framework for strategic classification that is practical. Our approach directly minimizes the "strategic" empirical risk, achieved by differentiating through the strategic response of users. This provides flexibility that allows us to extend beyond the original problem formulation and towards more realistic learning scenarios.

## Requirements
Setup the environment using 
```setup
conda env create -f environment.yml
conda activate "name env"
```

## Training and Evaluation
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
