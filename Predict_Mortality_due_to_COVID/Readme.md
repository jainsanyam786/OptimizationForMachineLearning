# Predicting Covid Mortality with Machine Learning.
> The aim of this project is to design a predictor to predict mortality among confirmed CoVID-19 patients in South Korea using logistic regression and support vector machines. 
Compare the predictor based on ogistic regression and support vector machines and identify best among them. 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [Code](#code)
* [Results](#results)
* [Conclusion](#conclusion)

## General info
* Dataset for the project is taken from [kaggle](https://www.kaggle.com/kimjihoo/coronavirusdataset). The dataset was released by Korea Centers for Disease Control and Prevention, and it contains information the Covid-19 cases in South Korea.
* Logistic regression and Support Vector Machines models are designed from scratch.
* Models are compared on the basis of Accuracy, Precision, Recall, F1 score and RUC_AUC_SCORE.
* The predictor is based on age, gender, province, and whether the patient had been in contact with a COVID positive patient.

## Technologies
* Programming Language -  Python3.

## Code
* Code -  [Jupyter notebook.](https://github.com/jainsanyam786/OptimizationForMachineLearning/blob/master/Predict_Mortality_due_to_COVID/FinalProject.ipynb) 
* Above jupyter notebook contains code for data pre-processing, model designing, training and testing.

## Features
SMOTE (Synthetic Minority Oversampling Technique) and ADASYN (Adaptive Synthetic Sampling Method) are use reduce the impact of class imbalance in data.
* ### SMOTE
  Data augmentation technique for the minority class which duplicates exiting examples in the minority class. These examples don’t add any new information to the model.  
* ### ADASYSN
  ADASYSN is similar to SMOTE as it also duplicates existing examples but prefernce is given to examples that are not in homogenous neighborhoods, thus generating "hard to learn"
  samples
* Polyak's momentum based stochastic gradient descent is used to train logistic regression classifier.
* Normal stochastic gradient descent is used to train SVM classifier. 
  
## Results
![Example screenshot](./image.png)

## Conclusion
Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!
