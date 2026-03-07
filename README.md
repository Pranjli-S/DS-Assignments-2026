
# International T20 Cricket EDA & Scorecard Generator

## Overview

This project performs Exploratory Data Analysis (EDA) on an International T20 Cricket dataset. It cleans the data, answers specific analytical questions, visualizes trends, and includes a custom Python function to generate detailed match scorecards.

## Features

* **Data Analysis:**
* Identifies the top 3 venues hosting the most matches.
* Finds the most frequent head-to-head team matchup.
* Calculates and ranks the top 5 teams by overall win percentage.


* **Visualizations:** Uses Matplotlib and Seaborn to generate:
* Bar chart of top teams by total wins.
* Pie chart of match distribution by gender.
* Boxplot of win margins (by runs) across genders.
* Correlation heatmap for numeric variables.


* **Scorecard Generator:** A custom function that takes match innings data and generates a side-by-side dataframe scorecard. It accurately displays the top 4 batsmen (by runs) and the top 4 opponent bowlers (by wickets and runs conceded), filtering out run-outs from bowler stats.

## Libraries Used

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`

## How to Run

Download both the .ipynb notebook and the International_T20_Data.csv.zip file.

Open the notebook in Google Colab or Jupyter.

Important: Upload the .zip file to your environment.

Run the cells sequentially. The code is designed to automatically detect and extract the CSV from the ZIP folder before processing.
