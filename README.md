# Model Representation | Linear Regression

This repository contains the implementation of a simple linear regression model representation, as part of the **Machine Learning Specialization** offered by DeepLearning.AI and Stanford University.

## 📌 Project Overview
We explore the fundamentals of supervised learning by implementing the model function $f_{w,b}(x) = wx + b$ for linear regression with one variable. 

The goal is to understand how the parameters $w$ (weight) and $b$ (bias) define a straight line that fits a set of data points, allowing us to make predictions for new data.

## 🛠️ Tools Used
- **Python**: The core programming language.
- **NumPy**: For scientific computing and handling data as arrays.
- **Matplotlib**: For visualizing the training data and the linear regression model.
- **Jupyter Notebook**: The interactive environment used for the lab.

## 📊 Problem Statement
The lab uses a motivating example of **housing price prediction**. 
- **Features ($x$):** House size (in 1000s of sqft).
- **Target ($y$):** House price (in 1000s of dollars).
- **Goal:** Fit a linear model through the data points to predict the price of a house given its size.

## 🚀 Key Concepts Covered
1. **Training Set:** Working with a simple dataset of house sizes and prices.
2. **Model Function:** Implementing $f_{w,b}(x^{(i)}) = w x^{(i)} + b$.
3. **Parameter Tuning:** Manually adjusting $w$ and $b$ to see how the line changes relative to the data points.
4. **Data Visualization:** Plotting the "best fit" line over a scatter plot of training examples.
