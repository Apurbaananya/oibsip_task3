# Car Price Prediction with Machine Learning
Oasis Infobyte Internship Project
![dataset-cover](https://github.com/Apurbaananya/oibsip_task3/assets/142817867/f8551d65-1feb-4e25-b7c9-7031581e2fc7)

## Problem Statement

**Project Overview:**

Determining car prices in the automotive industry involves various factors such as brand reputation, car features, horsepower, and fuel efficiency. Car price prediction is a key application of machine learning. This project aims to teach you how to build a car price prediction model.

**Key Objectives:**

- Explore the factors influencing car prices.
- Develop a machine learning model to predict car prices.
- Gain valuable experience in machine learning and automotive pricing.

## Project Summary

Objective: Develop a machine learning model to predict car prices based on various influencing factors.

Why Car Price Prediction? Car prices are influenced by numerous variables, including brand reputation, features, horsepower, and fuel efficiency. Machine learning models can provide accurate price predictions.

Key Tasks:

- Data Collection: Gather data on various car attributes and their corresponding prices.
- Data Preprocessing: Clean, transform, and prepare the data for modeling.
- Feature Engineering: Identify the most important features for price prediction.
- Model Building: Create a machine learning model capable of predicting car prices.
- Model Evaluation: Assess the model's accuracy and performance using appropriate metrics.
- Deployment: Make the trained model available for car price predictions.
- Benefits: By completing this project, we'll gain valuable insights into machine learning, data analysis, and the automotive industry. We'll also have a functional car price prediction model that can be useful for future car pricing decisions.

## Results

I have chosen the R2 score as the primary evaluation metric for the Car Price Prediction model. After eliminating overfitted models with 100% MSE, R2 score, and Adjusted R² score on the training set, as well as models with negative accuracy values, the final list is as follows:
|Sl. no.| Regression Model         | R2 Train(%) | R2 Test(%) |
| ----- | ------------------------ | ----------- | ---------- |
|   1   | Linear Regression|       | 0.618375	   | 0.635721   |
|   2   | Tuned Linear Regression  | 0.618375    | 0.635721   |
|   3   | Lasso Regression         | -0.102212	 | -0.076025  |
|   4   | Lasso Regression Tuned   | 0.612290    | 0.633115   |
|   5   | Ridge Regression         | 0.617775    | 0.635095   |
|   6   | Ridge Regression Tuned   | 0.586009    | 0.603682   |
|   7   | Decision Tree            | 1.000000    | 0.817404   |
|   8   | Decision Tree Tuned      | 0.756994    | 0.724694   |
|   9   | Random Forest            | 0.756994    | 0.916997   |
|  10   | Random Forest Tuned      | 0.758992    | 0.748617   |
|  11   | XGB                      | 0.999983    | 0.924279   |
|  12   | XGB Tuned                | 0.999983    | 0.924279   |

## Conclusion

This project delves into the complex dynamics of the automotive industry, using machine learning to predict car prices. By analyzing factors like fuel type, seller type, and transmission, we uncover crucial insights and select a robust model for accurate price prediction.

**Key Insights:**

- The top-selling car model is 'city,' followed by 'corolla altis,' 'verna,' 'fortuner,' and 'brio,' providing an overview of popular models in the market.
- The year 2015 witnessed the highest number of car purchases, making it the most favored year, followed by 2016 and 2014.
- 'Petrol' is the predominant fuel type in the dataset, surpassing 'Diesel' and 'CNG,' indicating buyer fuel preferences.
- Dealerships handle the majority of car sales, highlighting their significant role in the automotive market.
- 'Manual' transmission cars outnumber 'Automatic' transmission cars, reflecting consumer transmission preferences.
- Cars with 'First Owner' generally command higher 'Selling_Price,' while 'Second' or 'Third Owner' cars often have lower prices.
- 'Diesel' cars tend to fetch higher 'Selling_Price' compared to 'Petrol' or 'CNG' vehicles, influencing car pricing.
- Dealers typically list cars at higher prices compared to individual sellers, affecting pricing dynamics.
- 'Automatic' transmission cars generally have higher prices than 'Manual' counterparts, aligning with consumer preferences.
- The number of owners impacts car pricing, with 'First Owner' cars typically priced higher than subsequent owners.
- There's a negative correlation between driven kilometers and 'Selling_Price,' indicating higher prices for lower mileage cars.

Various machine learning models were evaluated, with the Random Forest model chosen for its robust performance in predicting car prices.

The project utilized the R2 score as the primary evaluation metric, with the XGB model achieving impressive results: 99% training accuracy and 92% testing accuracy, solidifying its suitability for practical applications in the automotive market.

These insights deepen our understanding of car pricing dynamics, combining exploratory data analysis with machine learning to enhance our data science skills significantly.
