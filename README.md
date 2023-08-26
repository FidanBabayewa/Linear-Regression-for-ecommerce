# Linear-Regression-for-ecommerce


Welcome to the Ecommerce Customer Analysis project! In this project, we work with an Ecommerce company based in New York City that sells clothing online and offers in-store style and clothing advice sessions. The company is at a crossroads and wants to determine whether to focus on improving their mobile app experience or their website. As a contracted data analyst, we're here to help them make an informed decision.



## Introduction

The objective of this project is to analyze the provided Ecommerce Customers dataset and extract insights that will guide the company's decision-making process. We will explore the relationships between various customer attributes and their yearly amount spent on the platform. The dataset contains both numerical and categorical features, and we will employ linear regression to model the relationship between predictors and the target variable.

## Dataset

The dataset, named "Ecommerce Customers," includes various customer attributes and numerical value columns:

- Avg. Session Length: Average session duration of in-store style advice sessions.
- Time on App: Average time spent on the mobile app in minutes.
- Time on Website: Average time spent on the website in minutes.
- Length of Membership: Number of years the customer has been a member.
- Yearly Amount Spent: The target variable representing the total amount spent by the customer yearly.

## Training and Testing Data

To train and evaluate our model, we split the data into training and testing sets. We use the numerical features (`X`) to predict the "Yearly Amount Spent" (`y`).

## Training the Model

We utilize linear regression from the `sklearn` library to train our model. We fit the linear regression model to the training data and explore its performance.

## Predicting Test Data

We predict the target variable on the test data using the trained linear regression model. We visualize the real test values against the predicted values.

## Evaluating the Model

We evaluate the model's performance using various metrics such as Mean Absolute Error, Mean Squared Error, and Root Mean Squared Error. These metrics help us understand the accuracy of our predictions.

## Residuals

We examine the residuals of our model and plot a histogram to ensure that they follow a normal distribution.

## Conclusion

Through our analysis, we aim to provide insights that will assist the company in deciding whether to focus on the mobile app, website, or other factors like length of membership. We interpret the coefficients of the model to understand the relationship between different attributes and the yearly amount spent.

