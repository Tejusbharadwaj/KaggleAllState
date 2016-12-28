# KaggleAllState

Domain Description

  Allstate is a personal insurance company in the US. Allstate is currently developing automated methods of predicting the cost, and hence severity, of claims. This project provides an algorithm that accurately predicts claims severity.

Description of Algorithm 

The algorithm used for predicting the Allstate claims severity is XGBoost. XGBoost is an algorithm that has recently been dominating applied machine learning and Kaggle competitions for structured or tabular data. XGBoost is an implementation of gradient boosted decision trees designed for speed and performance. It belongs to a broader collection of tools under the umbrella of the Distributed Machine Learning Community or DMLC who are also the creators of the popular mxnet deep learning library. The XGBoost algorithm was chosen because of its computational speed and model performance. It makes best use of available resources to train the model. Along with this, sklearn was also used. Specifically the packages preprocessing, metrics andcross-validation were used.
The training and test subsets were divided as 80:20.

Code

The code consists of the following modules:

 enter the number of folds from xgb.cv

 Load data set and target values

 set up KFold that matches xgb.cv number of folds

 Define cross-validation variables

 Build Model

 Evaluate Model and Predict

 Add Predictions and Average Them

 Print results of each fold (MAE) and the average MAE

 Write results into csv file

Mean Absolute Error

The average MAE obtained is 1145.863044

Instructions to Recreate the Result
1. Download the dataset from https://www.kaggle.com/c/allstate-claims-severity/data
2. In your folder, place the train and test files in input folder.
3. Install numpy, pandas, xgboost and sklearn.
4. Run the python script “script.py”
5. The MAE for each fold (in the 5 folds) and the average MAE will be shown on the
console.
6. The file with id and loss pair will be available in your folder.
