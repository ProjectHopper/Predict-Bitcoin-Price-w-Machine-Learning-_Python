# Project Overview

This project predicts the future price of Bitcoin using historical data on the price of Bitcoin and data from Wikipedia on the edits to the Bitcoin page. We can train a random forest model to tell us if Bitcoin prices will increase or decrease tomorrow. Then we use a gradient boosting model and improve the predictors to increase accuracy.


We'll develop a backtesting system and use a robust error metric so we can tell if the algorithm is performing well.

This project can be extended to other cryptocurrencies as well.

**Project Steps**

* Load in data
* Clean and merge data
* Create an initial machine learning model and estimate accuracy
* Switch to a more powerful model and improve our predictors

## Code

File overview:

* `Downloading Bitcoin Price Data.ipynb` -  a Jupyter notebook that creates our wikipedia edit dataset.
* `Prep data for Machine Learning_Training Baseline ML Mode.ipynb` - a Jupyter notebook that contains the code to predict Bitcoin prices

![Screenshot 2023-12-26 013524](https://github.com/ProjectHopper/Predict_Bitcoin_Price_W_MachineLearning-Python/assets/139052598/c929b294-ba02-473f-9a67-6649dbc5938e)  

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * yfinance
    * scikit-learn
    * xgboost
    * mwclient
    * transformers

## Data

Computing the Wikipedia edit data takes time.  It can be faster to use the version that's already been generated.  It's in this repository, and called `wikipedia_edits.csv`.  Feel free to download and use the file.  You can also get it from [here](https://drive.google.com/uc?export=download&id=1XwJZ07bl2u-62yRMqV_emJGEXCI1u8dl).




