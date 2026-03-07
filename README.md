
# International T20 Cricket EDA & Scorecard Generator

## Overview

This project performs Exploratory Data Analysis (EDA) on an International T20 Cricket dataset. It cleans the data, answers specific analytical questions, visualizes trends, and includes a custom Python function to generate detailed match scorecards.

## Features

* **Data Cleaning:** Dynamically renames and formats messy column names for easier analysis.
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
* `ast`

## How to Run

1. Ensure the `International_T20_Data.csv` file is in the same directory as the notebook.
2. Open the `.ipynb` notebook in Google Colab or Jupyter.
3. Run the cells sequentially to output the analysis, charts, and scorecard data frames.

---


Would you like me to review the final GitHub link to make sure everything looks perfect before you email it to your professor? 
