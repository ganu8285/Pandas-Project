# My Project

# 🐼 Anime Data Analysis Project

This project uses Python and the **Pandas** library to analyze a dataset of top-rated Anime. It demonstrates data cleaning, string manipulation, and time-series calculations to extract meaningful insights from raw text data.

## 📂 Project Overview
The goal of this notebook is to process the `anime.csv` file and answer specific questions about rankings, episode counts, and broadcast duration.

## 🛠️ Key Features & Analysis
* **Data Loading:** Loaded raw anime ranking data using `pd.read_csv`.
* **Data Cleaning:**
    * Extracted the number of **episodes** from the combined `Title` string.
    * Converted episode counts from strings to integers for analysis.
* **Feature Engineering:**
    * Extracted the **broadcast time period** (e.g., "Apr 2009 - Jul 2010").
    * Calculated the **Total Duration in Months** using the `dateutil` library.
* **Insights:**
    * Identified the Anime with the **Maximum Score** (Fullmetal Alchemist: Brotherhood).
    * Identified the Anime with the **Maximum Number of Episodes** (Gintama).

## 💻 Libraries Used
* `pandas`
* `datetime`
* `dateutil`

## 🚀 How to Run
1.  Ensure you have Python installed.
2.  Install the required libraries:
    ```bash
    pip install pandas python-dateutil
    ```
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook pandas-project.ipynb
    ```
