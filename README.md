# Automobile Market Exploratory Analysis 🚗

This project performs a comprehensive Exploratory Data Analysis (EDA) on automobile data to identify the key characteristics that drive vehicle pricing and market presence.

## 📊 Overview
**Context:** Completed as part of the Stellenbosch University / HyperionDev Data Science Bootcamp.
**Goal:** To clean a raw dataset containing missing values and incorrect data types, and then visualize relationships between mechanical features (horsepower, engine size) and price.

## 🛠️ Technologies Used
* **Jupyter Notebook**
* **Pandas:** For replacing missing values (`?` -> `NaN`), type conversion, and handling duplicates.
* **Seaborn & Matplotlib:** For generating correlation heatmaps, price distributions, and categorical plots.

## 🔎 Key Analysis Steps
1.  **Data Sanitization:**
    * Identified and replaced placeholder characters ('?') with valid null values.
    * Converted object types to numeric formats for columns like `horsepower` and `price`.
    * Removed rows with missing target variables to ensure modeling accuracy.
2.  **Statistical Visualization:**
    * **Correlation Matrix:** Generated a heatmap to quantify relationships between numeric features.
    * **Price Analysis:** Plotted histograms to understand the skewness of car prices in the market.
    * **Feature Interaction:** Analyzed the linear relationship between Engine Size and Horsepower.

## 📈 Findings
* **Price Sensitivity:** The distribution of prices confirms that while most vehicles compete in the economy sector, luxury outliers significantly skew the market average.
* **Mechanical Correlation:** There is a distinct positive correlation between engine size and horsepower, validating that larger displacement engines reliably produce higher power output.

## 🚀 How to Run
1. Ensure `automobile.txt` is in the same directory as the notebook.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
