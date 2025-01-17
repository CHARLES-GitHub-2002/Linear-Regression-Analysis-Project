# Linear Regression Analysis  Project

## Overview
The goal of this project is to help the company make a data-driven decision on whether to prioritize enhancing their mobile app experience or improving their website. Using the data, I will analyze customer behavior, uncover insights, and provide recommendations to support their decision-making process.
## Dataset
- **Source:** [Kaggle](https://kaggle.com/dataset)
- **Features:**
  - `Avg. Session Length`: The average duration of in-store style advice sessions.
  - `Time on App`:he average time customers spend on the mobile app, measured in minutes.
  - `Time on Website`: The average time customers spend on the website, measured in minutes.
  - `Length of Membership`: The number of years the customer has been a member.
## Problem Statement
The e-commerce company is seeking to optimize its customer engagement and revenue generation by deciding whether to prioritize improvements in their mobile app experience or website functionality. The dataset includes key metrics such as average session length, time spent on the app, time spent on the website, and length of customer membership.

Our goal is to analyze these metrics to identify which platform—mobile app or website—has a greater impact on customer engagement and overall value to the company. This analysis will provide data-driven insights to guide the company in allocating resources effectively and enhancing the customer experience.
## Methodology
1.Getting the data.

2.Exploratory Data Analysis (EDA) to uncover patterns.

3.Splitting the data

4.Training the Model with multivariable regression using Scikit Learn.

5.Training the model with multivariable regression using OLS(Ordinary Least Squares).

6.Predicting Test Data.

7.Evaluation of the model.

8.Evaluation of the model.

9.Conclusion.

## Results
It can be tricky to interpret the information in this analysis. According to the model, the most significant factor for clients is not the time spent on the app or website, but their length of membership. However, of the two predictors (desktop vs app), the app has the strongest influence by far. In fact, the time spent on the desktop website does not seem to have any correlation at all! In other words, according to the data, the amount of time that the customer spends on the desktop website has almost nothing to do with the amount of money they will spend.

We could interpret this in two different ways. Firstly, this could mean that the desktop website needs more work to make its visitors buy more. Secondly, it could mean that people tend to be more influenced by mobile applications of online stores than by desktop websites. So maybe efforts should be directed towards taking advantage of this fact. Indeed, the interpretation of this information requires expertise in the online marketing sphere. Our analysis and our model, however, does a very good job in weighting the predictors importance.
