# Titanic Survival Prediction

We aim to predict whether a person aboard the RMS Titanic survived the disaster or not, given his/her relevant data.

## Getting Started

The code has organized to jupyter notebooks, of which details can be found here : http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/

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

Since the code is organized as jupyter notebooks, every individual notebook can be run separately (instructions on running a jupyter python notebook can be seen here : http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)

NOTE: The notebook ensemble_xgboost_rft_logreg_models.ipynb requires the output csv files(prefixed with kaggle_out) be generated for randomforest, logistic regression and xgboost models (by running random_forest_models.ipynb, logistic_regression_models.ipynb and xgboost_models.ipynb notebooks respectively).

## Acknowledgments

* Thanks for everyone who helped out at the discussion forum : https://www.kaggle.com/c/titanic/discussion
 
