# IPO Listing Price Prediction
This project builds a machine learning model to predict the listing price of an initial public offering (IPO) on the stock market.

## Features
* Uses a dataset of IPOs listed on NSE (National Stock Exchange of India) between 2010-2021
* Preprocesses data by handling missing values, converting datatypes, standardizing features etc.
* Trains a Random Forest Regressor and XGBoost Regressor model. Tuned XGBoost model achieves low Mean Squared Error and high R2 score of 0.9 on test data
* Provides actual vs predicted price plot on test set to evaluate model performance
* Useful for investors to estimate potential listing price of an upcoming IPO based on issue details

## Code
The main notebook is IPO_Predictor.ipynb which covers:

* Importing libraries and dataset
* Data preprocessing
* Training RF and XGBoost model
* Evaluating model performance
* Plotting results
* Requirements

## The code was developed with:

* Python 3, Pandas, Numpy, Matplotlib, Seaborn
* Scikit-learn, XGBoost
* Google Colab GPU runtime
## Usage
To use the trained model to make listing price predictions:

* Clone the repo
* Open IPO_Predictor.ipynb in Colab/Jupyter Notebook
* Import the trained XGBoost model object
* Pass input data (after preprocessing) to model's predict() method
* Output will be predicted listing price
