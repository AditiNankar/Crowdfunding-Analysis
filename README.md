# 📊 Crowdfunding Campaign Analysis — Excel Challenge

## 🚀 Overview

This project explores the dynamics of crowdfunding platforms like **Kickstarter** and **Indiegogo**, which have surged in popularity over the past decade. With only campaigns that meet or exceed their funding goals receiving financial backing, understanding the factors behind successful crowdfunding efforts has become essential.

In this challenge, we analyze a dataset of **1,000 sample projects** using Microsoft Excel to uncover trends and insights that may influence campaign outcomes. This analysis includes data cleaning, transformation, visualization, and statistical exploration.

---

## 📌 Objectives

- Clean and enrich a dataset of crowdfunding projects
- Use Excel formulas and conditional formatting for key metrics
- Create pivot tables and charts for categorical and temporal analysis
- Perform a statistical breakdown of campaign backers
- Generate actionable insights and identify dataset limitations

---

## 🧪 Analysis Highlights

### ✅ Conditional Formatting

- Outcome-based cell coloring (`successful`, `failed`, `canceled`, `live`)
- A `Percent Funded` column using a 3-color scale (red–green–blue)

### 🧮 Custom Columns Created

- `Percent Funded`: Funding received ÷ Goal × 100  
- `Average Donation`: Pledged amount ÷ Number of backers  
- `Parent Category` & `Sub-Category`: Split from category column  
- `Date Created Conversion` & `Date Ended Conversion`: Converted Unix timestamps

### 📊 Category and Subcategory Insights

- Pivot tables show counts of outcomes (`successful`, `failed`, etc.) per **category** and **subcategory**
- Stacked column charts with **filtering by country** and **parent category**

### 📈 Time Series Analysis

- Created pivot table grouped by `Date Created`
- Line graph visualizing campaign outcomes over time, filtered by year and category

### 🎯 Goal-Based Outcome Trends

- Projects grouped into 12 goal ranges (e.g. `<1000`, `1000–4999`, `≥50000`)
- Used `COUNTIFS()` to measure success/failure rates by funding goal
- Line chart comparing success percentages across goal ranges

### 📐 Statistical Summary

- Compared `number of backers` for successful vs unsuccessful campaigns
- Calculated **mean, median, min, max, variance**, and **standard deviation**
- Interpreted central tendency and variability in backer behavior

---

## 📄 Written Report: Key Insights

- **Top 3 Conclusions:**
  1. Campaigns with moderate funding goals ($5,000–$15,000) are most likely to succeed.
  2. Tech and creative categories dominate success rates, especially in the U.S.
  3. Projects launched in Q2 and Q3 show better performance than those in Q1/Q4.

- **Limitations of the Dataset:**
  - Synthetic data limits real-world generalization
  - No data on marketing, team size, or social media impact
  - Limited insight into live campaigns or user demographics

- **Suggestions for Further Analysis:**
  - Compare pledged amount vs campaign duration
  - Analyze geographic performance by continent or city
  - Add regression to predict likelihood of success

---

## 📎 Tools Used

| Tool              | Purpose                               |
|-------------------|----------------------------------------|
| Microsoft Excel   | Data cleaning, analysis, visualization |
| Excel Pivot Tables| Aggregation and grouping               |
| Excel Charts      | Visual storytelling                    |
| Word / Google Docs| Written report & summary               |

---

## ✅ Requirements Checklist

| Feature                                             | Status |
|-----------------------------------------------------|--------|
| Conditional Formatting for Outcome                  | ✅     |
| Conditional Formatting for Percent Funded           | ✅     |
| Calculated Columns (6 total)                        | ✅     |
| Pivot Tables & Stacked Charts by Category           | ✅     |
| Pivot Tables & Line Charts by Date                  | ✅     |
| Written Report with Analysis                        | ✅     |
| Goal-Based Outcome Analysis                         | ✅     |
| Statistical Summary of Backers                      | ✅     |

---

## 📚 Acknowledgments

This project is part of a data analytics course by [edX Boot Camps LLC], designed to provide practical experience in analyzing real-world-style datasets using Excel.

---

## 🧠 Author

**Aditi Nankar**  
Aspiring Data Analyst | Background in Healthcare  
