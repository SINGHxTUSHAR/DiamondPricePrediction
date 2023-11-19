# Diamond Price Prediction

## Overview

This project aims to predict the price of diamonds using regression algorithms. It leverages machine learning techniques to analyze various features of diamonds and build a predictive model.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features :
The goal is to predict `price` of given diamond (Regression Analysis).

There are 10 independent variables (including `id`):

* `id` : unique identifier of each diamond
* `carat` : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
* `cut` : Quality of Diamond Cut
* `color` : Color of Diamond
* `clarity` : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
* `depth` : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
* `table` : A diamond's table is the facet which can be seen when the stone is viewed face up.
* `x` : Diamond X dimension
* `y` : Diamond Y dimension
* `x` : Diamond Z dimension

Target variable:
* `price`: Price of the given Diamond.

## Requirements :

Ensure you have the following dependencies installed:

- Python (version 3.9)
- Jupyter Notebook
- Other dependencies (refer to the requirements.txt)

You can install the required Python packages using:

```bash
pip install -r requirements.txt
```
## Setup :

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/diamond-price-prediction.git
cd diamond-price-prediction
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Usage :

- Open the Jupyter Notebook:
```bash
jupyter notebook
```
- Navigate to the Diamond_Price_Prediction.ipynb notebook and open it.
- Follow the instructions in the notebook to run the code cells.


## Dataset Source Link :
[https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)

## Models :

- Linear Regression
- Lasso(L1 Regularization)
- Ridge(L2 Regularization)
- ElasticNet
- DecisionTreeRegressor
- RandomForestRegressor
- SVR(Support Vector Regression)

## Results :

* LinearRegression Model Training Performance :
   - RMSE: 1013.9047094344004
   - MAE: 674.0255115796832
   - R2 score 93.68908248567512

* Lasso Model Training Performance :
  - RMSE: 1013.8784226767013
  - MAE: 675.0716923362161
  - R2 score 93.68940971841704

* Ridge Model Training Performance :
  - RMSE: 1013.9059272771647
  - MAE: 674.0555800798206
  - R2 score 93.68906732505937

* Elastic net Model Training Performance :
  - RMSE: 1533.4162456064048
  - MAE: 1060.7368759154729
  - R2 score 85.56494831165182

* DecisionTreeRegressor Model Training Performance :
  - RMSE: 838.7860494085679
  - MAE: 423.35310763649716
  - R2 score 95.68082679027064

* RandomForestRegressor Model Training Performance :
  - RMSE: 610.7311352754283
  - MAE: 311.5482746987208
  - R2 score 97.71019581207089


## Contributing :
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## License :
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/DiamondPricePrediction/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.


























