# 📊 Facebook Ads Data Analysis

## Overview
This project focuses on analyzing Facebook Ads data to gain insights into ad spend and Return on Marketing Investment (ROMI). The analysis includes daily trends, campaign-level insights, and statistical correlations. The project utilizes Python for data processing and visualization.

## Project Steps

### 1. Daily Data Grouping and Visualization
- **Objective:** Group the data by day to analyze trends over time.
- **Visualizations:**
  - **Daily Ad Spend in 2021:**
    ![Daily Ad Spend 2021](Facebook-Ads-Campaign-Analysis/Daily Ad Spend in 2021.png)
  - **Daily ROMI in 2021:**
    ![Daily ROMI 2021](Facebook-Ads-Campaign-Analysis/Daily ROMI in 2021.png)

### 2. Campaign-Level Grouping and Visualization
- **Objective:** Group the data by campaign name to compare performance across campaigns.
- **Visualizations:**
  - **Total Ad Spend by Campaign:**
    ![Total Ad Spend by Campaign](images/total_ad_spend_by_campaign.png)
  - **Total ROMI by Campaign:**
    ![Total ROMI by Campaign](images/total_romi_by_campaign.png)

### 3. ROMI Distribution by Campaign
- **Objective:** Use a box plot to examine the daily distribution of ROMI for each campaign.
- **Visualization:**
  ![ROMI Distribution by Campaign](Facebook-Ads-Campaign-Analysis/Daily ROMI Distribution for Each Campaign.png)

### 4. ROMI Value Distribution Histogram
- **Objective:** Create a histogram to analyze the distribution of ROMI values in the dataset.
- **Visualization:**
  ![ROMI Distribution Histogram](Facebook-Ads-Campaign-Analysis/ROMI Distribution.png)


### 5. Heat Map of Correlations
- **Objective:** Plot a heat map to visualize correlations between numerical values in the dataset.
- **Analysis:**
  - Highest Correlation: [Identify highest correlated values]
  - Lowest Correlation: [Identify lowest correlated values]
  - Correlation with "total_value": [Describe correlation]
- **Visualization:**
  ![Correlation Heat Map](images/correlation_heatmap.png)

### 6. Scatter Plot with Linear Regression
- **Objective:** Visualize the relationship between "total_spend" and "total_value" using a scatter plot with linear regression.
- **Visualization:**
  ![Total Spend vs. Total Value Scatter Plot](images/total_spend_vs_total_value.png)

## 🚀 Results
- **Daily Trends:** Analysis of daily ad spend and ROMI trends provided insights into the most and least effective days for ad performance.
- **Campaign-Level Insights:** Comparing total spend and ROMI by campaign helped identify the most cost-effective campaigns.
- **ROMI Distribution:** The box plot and histogram provided a clear view of the distribution and variability of ROMI across campaigns and the entire dataset.
- **Correlations:** The heat map highlighted key correlations between variables, with particular attention to the relationship between total spend and total value.
- **Spend vs. Value Relationship:** The scatter plot with linear regression revealed the nature of the relationship between ad spend and the resulting value.

## 📂 Project Files
- **Jupyter Notebook:** [Facebook_Ads_Analysis.ipynb](Facebook.ipynb)
- **Visualizations Folder:** Contains all the image files used in this analysis.

## 🛠️ Tools Used
- **Python:** For data processing and visualization.
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy.
