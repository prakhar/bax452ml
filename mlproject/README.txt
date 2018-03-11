SMS Spam Classifier

The goal of this project is to create a Spam Classifier for text messages. We would be using the SMS dataset provided by UC Irvine, which can be accessed at:https://archive.ics.uci.edu/ml/datasets/sms+spam+collection


Methodology
After data cleaning and EDA, various machine learning classification algorithms were applied on the dataset and out of all the algorithms, Multinomial Naive Bayes algorithm gave the best results with an accuracy rate of close to 98% on the test data set.

Applications
The trained models were further used to create a web-based interface for live-testing and to create an API. 
The web-based interface can be accessed at: http://192.241.231.87/spamsent
The API can be accessed at: http://192.241.231.87/spamsent/api.html