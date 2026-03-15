# CPU Price Prediction and Analysis

## Project Overview

This project analyzes CPU data using both **supervised and unsupervised machine learning techniques**. The goal is to understand CPU characteristics, predict their prices, classify performance levels, and group similar processors based on their specifications.

Several machine learning models were applied and evaluated to determine which methods perform best for different tasks.

## Main Steps

* Data preprocessing and feature analysis
* CPU price prediction using regression models
* CPU performance classification
* Clustering CPUs based on similar characteristics
* Model evaluation and comparison

## Models Used

* **Polynomial Ridge Regression** – used for predicting CPU prices and achieved the best performance among the regression models.
* **Decision Tree Classifier** – used to categorize CPUs into performance classes.
* **K-Means Clustering** – used to group CPUs with similar specifications.

Each model served a different analytical purpose, providing insights into CPU pricing, performance segmentation, and hardware similarity patterns.

## Important Note

GitHub sometimes displays **rendering artifacts when previewing `.ipynb` notebooks**. The notebook itself works correctly, but the online viewer may show formatting issues.

If the notebook does not render properly on GitHub, you can open and run the full interactive version using Google Colab:

https://colab.research.google.com/drive/1LxsVEzi7o8Xd7Hbx4j1PN05iS_XgZ6I0?usp=sharing

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
