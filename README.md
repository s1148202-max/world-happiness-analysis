# World Happiness Report 2021 Data Analysis

## Project Overview
This project uses Python to perform Exploratory Data Analysis (EDA) and linear regression modeling on the World Happiness Report 2021 dataset. The goal is to investigate how economic factors, social support, and health contribute to national happiness scores across the globe.

## Dataset
- **Source:** Kaggle - World Happiness Report 2021 (Gallup World Poll)
- **Sample Size:** 149 countries
- **Variables:** 20 variables, including Country name, Regional indicator, Ladder score, Logged GDP per capita, Social support, Healthy life expectancy, and more.

## Analysis Performed
- **Data Cleaning:** Checked for missing values (none found).
- **Descriptive Statistics:** Summarized global happiness distributions.
- **Visualization:** Boxplot (regional differences), Scatter plot (GDP vs. Happiness), Correlation Heatmap (variable relationships).
- **Linear Regression:** Used Logged GDP per capita, Social support, and Healthy life expectancy to predict Ladder score.

## Key Findings
1. **Significant Regional Differences:** Western Europe and North American regions have the highest happiness scores, while Sub-Saharan African countries score lower.
2. **Strong Predictive Model:** The regression model explains **69.3%** of the variance in national happiness (R-squared = 0.693).
3. **Social Support is the Dominant Factor:** The coefficient for Social support is **3.0005**, indicating a much stronger impact on happiness compared to economic growth (GDP coefficient 0.2733) and health (coefficient 0.0449).

## Tools Used
- Python 3
- pandas, numpy
- matplotlib, seaborn (Visualization)
- statsmodels (Linear Regression)

## How to Run
1. Download the `world-happiness-report-2021.csv` file from Kaggle.
2. Rename the file to `data.csv` (to match the notebook code).
3. Open the `world_happiness_analysis.ipynb` notebook in Google Colab.
4. Upload the `data.csv` file to the session.
5. Click "Run All" to execute the analysis.

## Author
Deng Sichen (s1148202-max)
