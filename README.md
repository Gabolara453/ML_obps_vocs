# ML_obps_vocs

The approach used in this work is to search for odorant-binding protein descriptors (amino acid sequences) and volatile organic compounds (SMILES) to predict the protein-ligand binding affinity value with regression machine learning models.

![Figure](https://github.com/Glarah453/ML_obps_vocs/blob/main/figures/Esquema%20de%20Flujo%20de%20trabajo.jpg)


# Installation

## Data

To get the datasets, please refer to the [iobpdb_app](https://github.com/sshuklz/iobpdb_app.git) github for more details. You have to place "data" folder under "source" directory.

## Requirements

You will need to install the following to run the codes.


*   [Python 3.9.2 <=](https://www.python.org/downloads/)
*   [Pandas 2.2.x](https://pandas.pydata.org/docs/getting_started/install.html)
*   [Numpy 1.26.x](https://numpy.org/install/)
*   [Matplotlib 3.7.x](https://matplotlib.org/3.7.0/)
*   [Scipy 1.10.x](https://scipy.org/install/)
*   [Joblib 1.2.x](https://joblib.readthedocs.io/en/stable/installing.html)
*   [Padelpy 0.1.x](https://pypi.org/project/padelpy/)
*   [Propy 1.1.x](https://pypi.org/project/propy3/)
*   [Rdkit 2022.09.x](https://www.rdkit.org/docs/Install.html)
*   [Openpyxl 3.1.x](https://openpyxl.readthedocs.io/en/stable/tutorial.html)
*   [Hyperopt 0.2.x](https://hyperopt.github.io/hyperopt/)
*   [Scikit-learn 1.5.x](https://scikit-learn.org/1.5/install.html)
*   [Xgboost 2.1.x](https://xgboost.readthedocs.io/en/latest/install.html)
*   [Lightgbm 4.5.x](https://lightgbm.readthedocs.io/en/latest/Installation-Guide.html)


# Usage

To use the codes, you can run them in two ways:

1. **Option 1**:

To run all the stages in a single code, you must download the ipynb file [ML_IOBPdb_obps_covs.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_IOBPdb_obps_covs.ipynb) and run all the cells.

2. **Option 2**:

To run the stages separately, you must download the files:

* Data Collection and Filtering [ML_obps_covs - Etapa 1.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%201.ipynb). 

* Search for descriptors and creation of dataset [ML_obps_covs - Etapa 2 y 3.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%202%20y%203.ipynb). 

* Preprocessing, Normalization and Optimization of Hyperparameters of the Models run the files in the [Opt for Models](https://github.com/Glarah453/ML_obps_vocs/tree/main/Opt%20for%20Models)  folder for hyperparameter optimization,

* Results of Best Hyperparameters of the Models [ML_obps_covs - Etapa 4 y 5.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%204%2C%205.ipynb).

* Evaluating Model Predictions [ML_obps_covs - Etapa 6.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%206.ipynb).