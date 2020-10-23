# Machine Learning- Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. To help process this data,a machine learning models were created to classifying candidate exoplanets from the raw dataset.

1. [Preprocess the raw data](#Preprocessing-the-Data)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

### Models Used
In this project I used five machine learning models in order to tarin, test and classifying candidate exoplanets from the raw dataset. In the reporting section summary about the findings and assumptions of models is described. 
4. [K-Nearest Neighbors Algorithm](#K-Nearest-Neighbors-Algorithm) 
5. [Logistic_Regression](#Logistic-Regression)
6. [Neural_Networks_and_Deep_Learning](#Neural_Networks_and_Deep_Learning)
7. [Random_Forest](#Random_forest)
8. [Support Vector Machine(SVM)](#Support-Vector-Machine)
- - 

### Preprocess the Data
* Preprocessing was conducted to the dataset prior to fitting the models.
* Feature selection and remove unnecessary features was conducted fro all models.
* I used `MinMaxScaler` to scale the numerical data.
* I Separate the data into training and testing data.

### Tune Model Parameters

* I used `GridSearch` to tune model parameters.
* I tuned and compare the reported classifiers.

### Reporting

* Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* Not all variables are significant be sure to remove any insignificant variables.

* Make sure your `sklearn` package is up to date.

* Try a simple model first, and then tune the model using `GridSearch`.

- - -

## Submission

* Create a Jupyter Notebook for each model and host the notebooks on GitHub.

* Create a file for your best model and push to GitHub

* Include a README.md file that summarizes your assumptions and findings.

* Submit the link to your GitHub project to Bootcamp Spot.

##### © 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
