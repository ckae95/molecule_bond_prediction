# Description of this repository
The goal of this repo is to ...
This demo is based on the Kaggle competition 'Predicting Molecular Properties' (Link: https://www.kaggle.com/c/champs-scalar-coupling/overview) where the task is to predict the bond strength between atoms in molecules.

The repo contains the following:

* notebooks: main repository with the notebooks for feature creation and model fitting/testing
* code: directory with additional code (e.g. to create the non-TDA features)
* data: directory to store the data from Kaggle (download from here: https://www.kaggle.com/c/champs-scalar-coupling/data)
* README.md


# External code
The following Kaggle notebooks were used for this project:

* For non-TDA features: https://www.kaggle.com/robertburbidge/distance-features <br>
* For plotting molecules (but adapted): https://www.kaggle.com/mykolazotko/3d-visualization-of-molecules-with-plotly

# Some related publications
The idea to use topological data analysis for predictions on molecules is not new. Below you can find some interesting papers related to this:

* Persistent-Homology-based Machine Learning and its Applications – A Survey: https://arxiv.org/abs/1811.00252 (esp. section 5)
* Representability of algebraic topology for biomolecules in machine learning based scoring and virtual screening: https://arxiv.org/pdf/1708.08135.pdf
