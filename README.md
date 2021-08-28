# flighttakeoff_JFKairport

## This notebook is for a task on flight take off data - JFK airport

# Content:

This data was scraped under a Academic Paper under Review by IEEE transportation

This data file contains data about flights leaving from JKF ariport between Nov 2019-Dec-2020. Taxi-Out prediction has been an important concept as it helps in calculating Runway time and directly impact the cost of the flight.

# Problem Statement: 

Flight delays have a dramatic impact on the movement of taxiing aircraft between gates and runways. Taxi-out time is defined as the time between the actual pushback and wheels-off. Taxi-out time is difficult to predict in hub airports at peak hours. Consequently very long taxiing times and airport surface congestion would be suffered. The long-time taxiing aircraft may cause a blunder when dealing with the pushback and take-off slots, which not only destroys the balance of the arrival and departure process, but also increases fuel consumption and emissions. Moreover, the increasing workload of controllers is unfortunate. The delay is cumulative, but it is both stochastic and controllable in the taxi process. The stochastic characteristic is reflected in uncertainty events, such as shifts in the weather environment, the interaction of the departure/arrival aircraft surface movement, and the human factor. Controllable behaviours such as delays can be adjusted by alternating routes and taxiing speed and even by holding at gate 

Better prediction of taxi-out time allows all stakeholders to arrange the future activities in airport operation. Efficient taxi-out prediction methods are effective approaches when the aim is to eliminate delays and improve the utilization of resources. Once taxi-out time is predicted in advance, operators gain a flexibility that allows them to adjust the schedule, gates assignment, and pushback plan. This achieves the smoother operation of an airport and reduces its surface congestion and fuel-burn costs. The aim of this notebook is to develop the approaches that are more accurate predictors of the taxi-out time of departing aircraft

# Selected Model: 
Supervised Machine Learning is being used by many organizations to identify and solve business problems. The two types of algorithms commonly used are Classification and Regression.

In this notebook, the focus will be on Regression. Regression models are models which predict a continuous outcome like predicting taxi layout delay and we will implement the following linear regression models using scikit-learn:

- Linear Regression
- Ridge Regression
- Lasso Regression

# Evaluation Metrics:

We will evaluate the performance of the model using two metrics - R-squared value and Root Mean Squared Error (RMSE).

R-squared values range from 0 to 1 and are commonly stated as percentages. It is a statistical measure that represents the proportion of the variance for a target variable that is explained by the independent variables. The other commonly used metric for regression problems is RMSE, that measures the average magnitude of the residuals or error. We will be using both these metrics to evaluate the model performance.

Ideally, lower RMSE and higher R-squared values are indicative of a good model

# Steps:
In this notebook, we will follow the following steps:

Step 1 - Loading the required libraries and modules.

Step 2 - Loading the data and performing basic data checks.

Step 3 - Performing some exploratory data analysis

Step 4 - Creating dataframes for predictor and target variables.

Step 5 - Creating the training and test datasets by splitting.

Step 6 - Build, Predict and Evaluate the regression model. We will be repeating Step 5 for the various regression models.

Step 7 - Trying some usecases on regression models to test accuracy
