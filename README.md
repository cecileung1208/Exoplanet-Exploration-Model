# Exoplanet-Exploration-Model

![Image](https://github.com/cecileung1208/Exoplanet-Exploration-Model/blob/main/Image/exoplanets.jpg)

## Background
The purpose of this project was to build multiple machine learning models and compare them to identify the best model for classifying candidate exoplanets from the data provided by NASA.

## Requirements
* Compare the accuracy of at least 2 different Sci-Kit Machine Learning.
* Models Used:
  * Locgical Regression
  * Random Forest
  * KNN
  * SVM
  * Deep Learning

## Method
* Preprocessed the dataset prior to fitting the models.
* Scaled the numerical data.
* Separated the data for training and testing.
* Used GridSearchCV to hypertune the models and boost performance.
* Tuned and compared multiple classifiers.

## Results
| Model    | Training Data Score | Testing Datascore (Tuned) |
| ------------- | ------------- | ------------- |
| Logical Regression | 84.87% | 88.04%|
| Random Forest | 90.10% | 89.47%|
| KNN |83.83% | 82.13%|
| SVM | 84.55% | 87.14%|

| Model    |  Loss | Accuracy |
| ------------- | ------------- | ------------- |
| Deep Learning | 26.82% | 88.50%|

In conclusion, based on the results presented above, it is clear that all the models are great. Depending on the limitations, any of these models could be used. However, the Deep Learning models and Random Forest model have the highest accuracy and would be recommended if there are no restrictions.
