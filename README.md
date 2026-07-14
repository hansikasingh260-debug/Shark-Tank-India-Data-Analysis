# 🦈 Shark Tank India Data Analysis

## 📌 Project Overview

This project analyzes Shark Tank India data to explore patterns in startup pitches, investments, deal success rates, industries, and valuations across five seasons.

The analysis was performed using Python, Pandas, NumPy, and Matplotlib.

## 🎯 Objectives
- Analyze the overall performance of startup pitches
- Identify industries receiving the highest total investment
- Compare deal success rates across industries
- Analyze investment trends across seasons
- Identify the biggest deals
- Compare requested valuations with final deal valuations

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub

## 📊 Key Performance Indicators
- Total Pitches: 789
- Offers Received: 502
- Deals Accepted: 434
- Offer Rate: 63.62%
- Overall Deal Success Rate: 55.01%
- Offer Acceptance Rate: 86.45%

## 🔍 Key Insights

### 1. Industry Investment

Beauty/Fashion received the highest total investment, followed by Food and Beverage and Technology/Software.

### 2. Deal Success Rate

Among industries with at least 20 pitches, Medical/Health had the highest deal success rate at approximately 69.12%.

### 3. Seasonal Investment Trends

Season 4 recorded the highest total investment, while Season 2 had the highest overall deal success rate.

### 4. Average Deal Size

The average deal size increased across every season:
- Season 1: 57.49
- Season 2: 65.86
- Season 3: 73.15
- Season 4: 92.93
- Season 5: 115.38

### 5. Biggest Deal

NOOE recorded the largest individual deal amount in the dataset at 500.

### 6. Valuation Analysis

After excluding one extreme valuation outlier from the valuation comparison, the median valuation change among accepted deals was -50%. This suggests that startups typically secured deals at substantially lower valuations than initially requested.

## 📈 Visualizations

The project includes the following visualizations:

1. Top 10 Industries by Total Investment
2. Total Investment by Season
3. Deal Success Rate by Industry
4. Average Deal Size by Season
5. Top 10 Biggest Deals
6. Requested Valuation vs Deal Valuation

## 📁 Repository Contents

- `Shark_Tank_India_Data_Analysis.ipynb` — Complete Python analysis
- `shark_tank_india_raw.csv` — Original dataset
- `shark_tank_cleaned.csv` — Cleaned dataset used for analysis
- PNG files — Project visualizations

## 🧹 Data Cleaning

The dataset was cleaned by:

- Selecting relevant columns for analysis
- Checking for duplicate records
- Handling missing values based on their meaning
- Converting missing accepted-offer values to 0 when no offer was received
- Replacing missing city and state values with `Unknown`
- Preserving meaningful missing financial values rather than filling them arbitrarily
- Excluding an extreme valuation outlier only from the valuation comparison

## 📌 Conclusion

The analysis shows that Shark Tank India has experienced increasing average deal sizes across its seasons. Beauty/Fashion attracted the highest total investment, while Medical/Health achieved the highest deal success rate among industries with at least 20 pitches. The valuation analysis also indicates that successful startups often accepted deals at lower valuations than originally requested.

## 👩‍💻 Author

**Hansika Singh**

Aspiring Data Analyst | BCA Student | Learning SQL, Python & Excel
