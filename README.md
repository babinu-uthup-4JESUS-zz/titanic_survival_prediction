# Titanic Survival Prediction

We aim to predict whether a person aboard the RMS Titanic survived the disaster or not, given his/her relevant data.

## Getting Started

The code has organized to jupyter notebooks, of which details can be found [here](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/).

### Prerequisites

Python 3.x must be installed along with the following libraries(that are not installed as part of the default installation)

```
xgboost-python
```

### Installing

Python 3.x can be installed in the following manner


```
Download the Python 3.x anaconda installer(graphical or command line) 
from https://www.anaconda.com/download/ corresponding to your operating system 
and proceed with the given instructions.
```

Once anaconda is installed, xg-boost package can be installed in the following 

```
Follow instructions for installing package xgboost-python using anaconda as given in
https://conda.io/docs/user-guide/tasks/manage-pkgs.html#installing-packages
```

## Running the scripts
  
Since the code is organized as jupyter notebooks, every individual notebook can be run separately (instructions on running a jupyter python notebook can be seen [here](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).

I am listing specific guidelines for each of subfolders here :

### Folder : first_attempts

Three models have been built and their corresponding notebooks are <MODEL METHOD>_models.ipynb (for example random_forest_models.ipynb).
 
These notebooks can be run separately and have their output files generated as kaggle_out_<MODEL METHOD>.csv

NOTE: The notebook ensemble_xgboost_rft_logreg_models.ipynb requires the output csv files(prefixed with kaggle_out) be generated for randomforest, logistic regression and xgboost models (by running random_forest_models.ipynb, logistic_regression_models.ipynb and xgboost_models.ipynb notebooks respectively).

### Folder : learn_from_aashita

In this folder we attempted to incorporate some xgboost ideas inspired by the following [kernel](https://www.kaggle.com/aashita/xgboost-model-with-minimalistic-features). 

exploratory_data_analysis.ipynb : Explored data analysis using seaborn package.


## Acknowledgments

* Thanks for everyone who helped out at the [discussion forum](https://www.kaggle.com/c/titanic/discussion).
 
