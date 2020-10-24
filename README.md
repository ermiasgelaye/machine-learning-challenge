# Machine Learning- Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. To help process this data,a machine learning models were created to classifying candidate exoplanets from the raw dataset.

1. [Preprocess the raw data](#Preprocessing-the-Data)
2. [Tune the models](#Tune-Model-Parameters)
3. [Reporting](#Reporting)
    * [Logistic_Regression](#Logistic-Regression)
    * [Random_Forest](#Random_forest)
    * [Support Vector Machine(SVM)](#Support-Vector-Machine)
    * [K-Nearest Neighbors Algorithm](#K-Nearest-Neighbors-Algorithm) 
    * [Neural_Networks_and_Deep_Learning](#Neural_Networks_and_Deep_Learning)

### Preprocess the Data
* Preprocessing was conducted to the dataset prior to fitting the models.
* Feature selection and remove unnecessary features was conducted fro all models.
* I used `MinMaxScaler` to scale the numerical data.
* I Separate the data into training and testing data.

### Tune Model Parameters

* I used `GridSearch` to tune model parameters.
* I tuned and compare the reported classifiers.

### Reporting
In this project I used five machine learning models in order to tarin, test and classifying candidate exoplanets from the raw dataset. In the reporting section summary about the findings, assumptions and comparison of models is executed.

 #### Logistic Regression
 
  |               | BeforeCV      | AfterCV       |
  |:-------------:|:-------------:|:-------------:|
  |Training Score | 0.749         | 0.872         |
  |Testing Score  | 0.757         | 0.864         |
 
 ![Logistic Regression Classification Report](/all_ML_code/image/logisticregression_classifier.png)

 #### Random Forest
  |               | BeforeCV      | AfterCV       |
  |:-------------:|:-------------:|:-------------:|
  |Training Score | 1.0           | 1.0           |
  |Testing Score  | 0.897         | 0.899         |

![Random_Forest Classification Report](/all_ML_code/image/randomforest_classifier.png)
 
 #### Support Vector Machine(SVM)
  |               | BeforeCV      | AfterCV       |
  |:-------------:|:-------------:|:-------------:|
  |Training Score | 0.845         | 0.886         |
  |Testing Score  | 0.841         | 0.879         |
  
 ![Support Vector Machine Classification Report](/all_ML_code/image/svm_classifier.png)
  
 #### K-Nearest Neighbors
  |               | BeforeCV      | AfterCV       |
  |:-------------:|:-------------:|:-------------:|
  |Training Score | 0.675         | 1.0           |
  |Testing Score  | 0.636         | 0.842         |
  
  ![K-Nearest Neighbors Classification Report](/all_ML_code/image/Knn_classifier.png)
 
 #### Neural Networks and Deep_Learning
 
- Normal Neural Network - Loss: 0.2826294135174435, Accuracy: 0.8787185549736023
- Deep Neural Network - Loss: 0.2919023224500006, Accuracy: 0.8655606508255005

  ![Neural Network Plot](/all_ML_code/image/neuralnetwork.png)
  
### Comaprison Summary

The logistic regression training and test score significantly increases BeforeCV and AfterCV but comparing the other model's value was lower. The f1-score of FALSE POSITIVE for the logistic regression model is 0.89 meaning, it can predict FALSE POSITIVE well, and it's reliable, but comparing random forest (0.98) and K-Nearest Neighbors(0.98), which the value is 0.98 it is lower. Random Forest model's best score of (0.89) seems better than the SVM model (0.87) when comparing the scores. The Normal Neural Network accuracy(0.87) is better than Deep Neural Network(0.86).

In general, from the executed machine learning models on the given exoplanets dataset, I found that the random forest model is better to predict the data. It was a good experience to know which machine learning model does what and comparing the training, testing, accuracy, recall, precision results of the models. 

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -


##### © 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
