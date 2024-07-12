# Bulldozer-sales-price-prediction

# Predicting the Sale Price of Bulldozers using Machine Learning

![](https://github.com/AkilsuryaS/Bulldozer-sales-price-prediction/blob/main/images/Cover%20pic.jpg)

## 1. Problem Definition
> How well can we predict the future sale price of a bulldozer, given its
characteristics and previous examples of how much similar bulldozers have been
sold for?

## 2. Data
Downloaded from Kaggle Bluebook for Bulldozers competition:

The data for this competition is split into three parts:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from
January 1, 2012 - April 30, 2012 You make predictions on this set throughout the
 majority of the competition.
* Test.csv contains data from May 1, 2012 - November 2012. Your score on the
test set determines your final rank for the competition.

## 3. Data
The **evaluation metric** for this competition is the **RMSLE**
 (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check:
https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview

**Note:** the goal for most regression evaluation metrics is to minimize the
error. Likewise, our goal for this project will be to build a ML model which
minimizes RMSLE.

## 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset.
You can view this data dictionary on Google sheets:
https://docs.google.com/spreadsheets/d/181y-bLR8sbDJLITkWG7ozKm813RyieQ2Fpgix-beSYI/edit?usp=sharing

### Feature Importance
Feature importance seeks to figure out which different attributes of the data were most importance when it comes to predicting the target variable (SalePrice).
