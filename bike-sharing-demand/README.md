# Bike Sharing Demand Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uom-aiml/workshops-2020/blob/main/bike-sharing-demand/bike_sharing_regression_analysis.ipynb)

This task deals with some regression principles applied to bike sharing demand forecasting.

The dataset is taken from the [Bike Sharing Demand](https://www.kaggle.com/c/bike-sharing-demand/data) Kaggle challenge, from which you can download the necessary `csv` files. The task is as follows:

>You are provided hourly rental data spanning two years. For this competition, the training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. You must predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period.

We will:
1. perform some exploratory data analysis of our training data
2. investigate the distribution of our data and perform some transformations and feature engineering
3. select our predictive features through recursive feature extraction
4. build a benchmark model
5. build some more complex models and discuss the improvements made
6. make our predictions and write them in the appropriate submission form

We will make reference throughout the notebook to some valuable sources used. These sources are cited within the code.

Please feel free to Slack me with any questions etc.

Lots of love, Yann
