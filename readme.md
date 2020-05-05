
## Houses prices modelling

The aim of the project is to analyze data and build model to predict housing prices. 
Project is based on dataset accessible on Kaggle.com here. 
Dataset contains information on sold houses in King County (including Seattle) between May 2014 and May 2015. 
Variables include date of sale, price, number of beedrooms, number of beedrooms, floor area, and more.
More informations about dataset may be found there: [kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction).

#### Project contains:

Jupyter notebook file named “housing_case.ipynb”, based on kc_house_data.csv dataset. 
Main algorithm used in the notebook is XGBoost. Notebook contains:

* Data exploration
* Data preparation
* Data modelling
* Regression models evaluation
* Choosen model optimization

Jupyter notebook file named “housing_case_2_reg.ipynb”, based on modified dataset 'house.csv'. There is one more variable, which differentiate
if house's cost is below or above $1 mln. Regression problem is solved in the notebook. It is based on
“housing_case.ipynb” notebook with various improvements. Main algorithm used in the notebook is XGBoost. Notebook contains:

* Data exploration
* Data preparation
* Data modelling
* Regression models evaluation
* Choosen model optimization

Jupyter notebook file named “housing_case_2_cls.ipynb” is based on modified dataset 'house.csv' as above. Classification problem is solved - 
differentiation if house's cost is below or above $1 mln. Main algorithm used in the notebook is XGBoost. Notebook contains:

* Data exploration
* Data preparation
* Data modelling
* Classification model evaluation
* Choosen model optimization

Jupyter notebook file named “housing_case_2_reg_MLP.ipynb” is based on modified dataset 'house.csv' as above. 
Regression problem is solved in the notebook - prediction of houses' prices. 
Main algorithm used in the notebook is Multilayer Perceptron (MLP), a kind of Artificial Neural Network. 
Notebook contains:

* Data exploration
* Data preparation
* Data modelling
* Classification model evaluation
* Choosen model optimization


#### Data source:

[kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)


If Github does not render notebooks properly, try to open them in nbviewer under links:

[housing_case](https://nbviewer.jupyter.org/github/John-smith-889/housing-prices-modelling/blob/master/housing_case.ipynb)

[housing_case_2_reg](https://nbviewer.jupyter.org/github/John-smith-889/housing-prices-modelling/blob/master/housing_case_2_reg.ipynb)

[housing_case_2_cls](https://nbviewer.jupyter.org/github/John-smith-889/housing-prices-modelling/blob/master/housing_case_2_cls.ipynb)


