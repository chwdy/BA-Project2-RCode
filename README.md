#  Default Risk Prediction



##  Overview 

This is the 2nd project of 8413 Business analyst class.

The project is a subset of [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/overview) , using credit card history and previous application as external dataset

Instructor: JC Bonilla

Team: Diwei Zhu, Gabriela Caballero, Kunyang Que, Ullas Srivastava, Yangxing Liu

##  Data Cleaning



* application data

  Some columns in the dataset such as *Flag own a car* and *car age* are inter connected. We performed data validation check to see if there is logical error. For column like these, We replace

  We removed categorical data which are <1%.

* credit card & previous application

  For a single *sk_ID_CURR* in application set, there are more than 1 record in these external set. We engineered statistic data such as approved rate, record count.



##  Model Training & selection

* Logistic model

* gbm
* lgbm



##  Outcome

Lgbm model reached 73% accuracy on the given submission set