# PredictionProject
Coursera - Practical Machine Learning - Course Project - Prediction

## Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. 

The goal of this project is to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. 

More information is available from the website here: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

### Data

The training data for this project are available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

The data for this project come from this source: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har

## Executive Summary

This report describes different methods used to build models, how they are cross validated, what is the accuracy of each of the model, and which is the best model. Here, we tried 3 different models. We first used the training data to build the models, and then used the models to predict using the test data and identified the Accuracy in each of the model. After comparing all the 3 models, we then concluded the best model with evidence (with respect to Accuracy).

## Conclusion

The goal of this project is to predict the manner in which the participants did the exercise. This is the "classe" variable in the training set, against which 3 models were built.

* Classification Tree - Accuracy: 48.78%
* Random Forest - Accuracy: 99.39%
* Gradient Boost - Accurtacy: 96.04%

We can conclude that the Random Forest model fitted the best.
