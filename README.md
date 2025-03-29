🧢 MLB Player Salary Prediction (2023)


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

Standardizing player names across datasets to merge using first and last names.

Handling null values using context-aware strategies:

Fill with mean values

Replace with league minimums

Drop records without sufficient data

Combining duplicates by aggregating stats or keeping top contract entries.

Normalization and encoding using MinMaxScaler and one-hot encoding.

