# 🧢 MLB Player Salary Prediction (2023)


📌 Project Overview

This project focuses on predicting the salaries of Major League Baseball (MLB) players based on their 2023 season performance statistics. The goal is to explore the relationship between player performance and salary, while applying various data preprocessing and regression techniques to build predictive models.

The project was developed as part of the COMP 333: Data Analytics course at Concordia University.

📊 Datasets Used
We collected and integrated data from three different sources:

[MLB 2023 Salaries & Contracts
](https://databases.usatoday.com/major-league-baseball-salaries-2023/)

[2023 Exit Velocity Statistics](https://baseballsavant.mlb.com/leaderboard/statcast?type=batter&year=2023)

[2023 Player Stats](https://www.rotowire.com/baseball/stats.php?season=2023)


🛠️ Data Cleaning & Integration
We performed extensive preprocessing, including:

—Standardizing player names across datasets to merge using first and last names. <br>
—Handling null values using context-aware strategies <br>
—Fill with mean values <br>
—Replace with league minimums  <br>
—Drop records without sufficient data  <br>
—Combining duplicates by aggregating stats or keeping top contract entries.  <br>
—Normalization and encoding using MinMaxScaler and one-hot encoding.  <br>


📉 Outlier Detection
We applied multiple outlier detection methods to improve data quality:

—Z-Score Analysis  <br>
—IQR (Interquartile Range) Method <br>
—DBSCAN Clustering <br>

Only players that passed all three filters were used for model training.

📈 Key Features

—Robust data pipeline for cleaning and merging multiple real-world datasets. <br>
—Insightful visual analytics to assess data distributions and correlations. <br>
—Comparison between cleaned vs. raw data to highlight impact of preprocessing. <br>
—Use of Google Colab for reproducible and collaborative research. <br>


📦 Technologies Used

—Python (Pandas, NumPy, scikit-learn, Matplotlib, Seaborn) <br>
—Google Colab + Google Drive <br>
—ML models: Linear, Polynomial, Decision Tree <br>
—Data Cleaning: Unidecode, regex, aggregation functions <br>

