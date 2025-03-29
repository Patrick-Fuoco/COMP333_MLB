# COMP333_MLB

🧢 MLB Player Salary Prediction (2023)


📌 Project Overview

This project focuses on predicting the salaries of Major League Baseball (MLB) players based on their 2023 season performance statistics. The goal is to explore the relationship between player performance and salary, while applying various data preprocessing and regression techniques to build predictive models.

The project was developed as part of the COMP 333: Data Analytics course at Concordia University.

📊 Datasets Used
We collected and integrated data from three different sources:

MLB 2023 Salaries & Contracts
USA Today Salary Data

2023 Exit Velocity Statistics
Statcast Leaderboard

2023 Player Stats
Rotowire MLB Stats

🛠️ Data Cleaning & Integration
We performed extensive preprocessing, including:

Standardizing player names across datasets to merge using first and last names.

Handling null values using context-aware strategies:

Fill with mean values

Replace with league minimums

Drop records without sufficient data

Combining duplicates by aggregating stats or keeping top contract entries.

Normalization and encoding using MinMaxScaler and one-hot encoding.

📉 Outlier Detection
We applied multiple outlier detection methods to improve data quality:

Z-Score Analysis

IQR (Interquartile Range) Method

DBSCAN Clustering

Only players that passed all three filters were used for model training.

🧠 Models Trained
We experimented with several regression models for salary prediction:

Linear Regression

Polynomial Regression (Degree 2)

Decision Tree Regression

Each model was evaluated using:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R² Score (Coefficient of Determination)

Visualizations include histograms, correlation heatmaps, scatter plots of predictions vs. actuals, and decision trees.

📈 Key Features
Robust data pipeline for cleaning and merging multiple real-world datasets.

Insightful visual analytics to assess data distributions and correlations.

Comparison between cleaned vs. raw data to highlight impact of preprocessing.

Use of Google Colab for reproducible and collaborative research.

📦 Technologies Used
Python (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn)

Google Colab + Google Drive

ML models: Linear, Polynomial, Decision Tree

Data Cleaning: Unidecode, regex, aggregation functions

🔍 Future Work
Explore ensemble models (e.g., Random Forest, XGBoost).

Include pitching statistics and compare across player roles.

Predict future contract values instead of current salary.

Deploy as a lightweight web app using Streamlit or Flask.
