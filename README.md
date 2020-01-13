# Project 2: Ames, IA Housing Data

## Problem Statement

I am a acting as a consultant that just recently gained a client in Ames, Iowa. They have heard of my work and have asked me to help them predict housing prices in the area so that they can have a leg up on the market! 

---

## Executive Summary

The goal of this project is to take data and information collected from the Ames Assessor’s Office about residential units sold from 2006 - 2010 and build a linear regression model to predict unknown sales prices. 

This data set includes 81 characteristics & 2051 observations (or rows of home sales). Within these data, the observations can be categorized as either: Continuous, Ordinal, or Categorical. From these charateristics it's important to select columns of interest and transform/manipulate the data so it can  be useful to create the productive model.   

I used a heatmap & correlation coeficients to help determine the which variables ultimately makes a impact on predicting sales prices. I used techniques like feature engineering and log transformations to create the model variables.

The goal is for our model to predict the price of a home with specific characteristics with little error. In order to know the performance of our model, it was evaluated against 2 different metrics. R-squared & RMSE (Root Mean Squared Error). R-squared is on a scale of 0 to 1, with 1 being the best score. RMSE measures how for our predictions are from the correct value, on average. The closer we get to 0 (No difference in value) the better.

---

## Conclusions and Recommendations

I generated several different models and measured them against the 2 metrics. Two examples of results I yielded from my models is as follows:

Model 1: R-squared - 0.81; RMSE - $34,072. This model did not generalize well to unseen data.

Model 2: R-squared - 0.91; RMSE - $21,166. Generalizes well to unseen data.

I believe two next steps from these results include. More feature engineering and tuning of my model. Also, collect more Data! The data set I have based this model off of, is slightly outdated. Obtaining up to date data can potentially improve the model greatly.

### Additional data collection

The data collected was from 2006 to 2010. We are now in the year 2019, so that's 9 years of additional data that can be collected. If this data is collected, our models can be modified and improved to include market changes and trends that have occurred during this time.

---

