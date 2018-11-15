# Urban Technologies Lecture

## Our task

Thecustomer doesn't wrangle / analyze data. He focuses more on the high level stuff and leads strategically. The data scientist does most of the actual work.

Presentation:

* Final results (if there is one) and how we got there.
* Besides explorative analysis it's recommended to also use predictive models, but it's not mandatory.

## Bike Sharing 

### Data Set

Bike Sharing in Washington D.C. Dataset -
Rental bikes in 2011 and 2012 with corresponding weather and seasonal info  (https://www.kaggle.com/marklvl/bike-sharing-dataset/home)

### Business Requirements

1. Predict demand per day (# of total customers)
1. Intereference of variables (predictors vs. outcome) -> interpretation
    1. parameteric: multiple regression 
	1. non-parameteric: tree based methods

## Some general Notes

* misconception of coefficients' interpretability in linear models occurs, if there's correlation between the (predictor) variables.
* another way to obtain interpretability: multiply coefficients (= weights) * covariance-matrix (see Bießmann's paper / lecture notes)
