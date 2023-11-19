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

![image](https://github.com/SINGHxTUSHAR/DiamondPricePrediction/assets/113624520/f2e41112-c8a9-42c9-98c2-621e11c459fa)
![image](https://github.com/SINGHxTUSHAR/DiamondPricePrediction/assets/113624520/c3910f80-9504-4a1c-8ea9-72239e768d7c)
![image](https://github.com/SINGHxTUSHAR/DiamondPricePrediction/assets/113624520/15b945c5-fa5f-4972-b4b6-1d91855a3f82)
![image](https://github.com/SINGHxTUSHAR/DiamondPricePrediction/assets/113624520/5acd0ede-c093-4872-ae9f-f0fcdde0bedb)
![image](https://github.com/SINGHxTUSHAR/DiamondPricePrediction/assets/113624520/dec5e6a9-694d-4c38-8ab8-2ac516ff39c3)


## Contributing :
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## License :
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/DiamondPricePrediction/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.


























