# kaggle_xuxuxushhhhhhh
Kaggle in-msbd5001 competition 
Description
The dataset provides the average traffic speed per hour for a major road in Hong Kong from 2017 to 2018. Part of the dataset is provided as the training data, and your task is to predict the rest. 80% of the dataset is provided as the training data and 20% as the testing data, including the timestamp and the corresponding average speed. We sampled the testing data only from the year 2018 to provide you a training dataset that has the complete data spanning the year 2017. However, the speed information is sometimes missing due to device malfunction.

You have to submit the predicted results of these testing samples, which are then compared with the ground truth to evaluate the performance of your model.

I write this program mainly in Google Colaboratory, and the language used is Python.

Following packages needed：pandas, numpy, re, datetime, wwo-hist, urllib, matplotlib, sklearn, xgboost。

To get the submit file:1. Run traindata_clean.ipynb to generate the processed train and test data file.
2. Run model_train.ipynb steply to generate the final submit csv file.


And my resulting test.csv file is xgboost_submit_final.csv

Here are some websites I refered in my project:https://www.freecodecamp.org/news/obtain-historical-weather-forecast-data-in-csv-format-using-python/, https://cloud.tencent.com/developer/article/1080593
