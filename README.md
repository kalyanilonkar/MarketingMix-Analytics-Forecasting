
#  MarketingMix-Analytics-Forecasting-SALES
# Marketing Mix Analytics & Sales Forecasting

![R](https://img.shields.io/badge/R-4.2.0-blue)
![RMarkdown](https://img.shields.io/badge/RMarkdown-Document-lightgrey)
![License](https://img.shields.io/badge/License-Academic-informational)
![Data](https://img.shields.io/badge/Data-CSV%20%7C%20Excel-brightgreen)
![Model](https://img.shields.io/badge/Models-ARIMA%20%7C%20PCA%20%7C%20Regression-orange)
![Marketing](https://img.shields.io/badge/Focus-Marketing%20Mix%20Analytics-red)

## 🔍 Topics
- marketing-analytics
- forecasting
- time-series-analysis
- rstats
- rmarkdown
- data-visualization
- business-intelligence
- statistical-modeling
- marketing-mix
- regression-analysis
- pca
- arima
- stepwise-regression

This repository contains an end-to-end data analytics project analyzing the impact of marketing activities (TV ads, online banners, and in-store promotions) on chocolate sales across multiple countries. It includes extensive data preprocessing, exploratory data analysis, feature engineering, time series forecasting, PCA, multiple regression models, and marketing effectiveness evaluation.

---

##  Project Objectives

- **Assess** the contribution of marketing activities on sales across Mexico, Spain, US, UK, and Singapore.
- **Build forecasting models** (Linear Trend, Naive Seasonal, ARIMA) to predict future sales.
- **Apply PCA** to reduce dimensionality and analyze key drivers of sales.
- **Develop regression models** to understand and quantify the impact of marketing activities.
- **Calculate ROI & cost-effectiveness** of different marketing channels.

---

## Project Structure

```
 MarketingMix-Analytics-Forecasting/
├── analysis.Rmd       # Main RMarkdown file with full analysis
├── Book2FINALfinal.xlsx # Raw or cleaned data used for analysis
├── data_output.xlsx   # Outputs or processed data
├── README.md          # This file
└── plots/             # Folder for storing generated plots (optional)
```

---

##  Methods & Tools

| Area                     | Techniques Used                              |
|---------------------------|--------------------------------------------|
| **EDA**                  | Descriptive stats, missing value checks, histograms, boxplots |
| **Feature Engineering**  | Log transformations, interaction terms, scaling |
| **PCA**                  | Scree plots, cumulative variance, biplots   |
| **Time Series Models**   | Linear trend, STL decomposition, Naive Seasonal, ARIMA |
| **Regression Models**    | Multiple regression, stepwise selection (AIC), assumptions diagnostics |
| **ROI & MMM**            | Calculating contribution of TV, banners, promotions; cost-effectiveness |

---

## Data Overview

- Data from **5 countries**: Mexico, Spain, US, UK, Singapore.
- Monthly sales data from **2010-2014** with variables:
  - Sales, Price, Ad1 (TV ads), Ad2 (Online banners), No_of_stores (promotions)
  - Wage (employee compensation), plus engineered features (log, squares, interactions).

---

## 🚀 How to Run

> Ensure you have R and RStudio installed, along with required packages (listed inside the RMarkdown).

1️⃣ Clone this repository:
```bash
git clone https://github.com/yourusername/MarketingMix-Analytics-Forecasting.git
```

2️⃣ Open `analysis.Rmd` in RStudio.

3️⃣ Click **Knit** to render the full report (HTML / PDF).

---

## Example Insights

- **TV advertising** contributed the highest units sold across most regions.
- **Singapore** showed strong seasonality captured by STL, while Mexico had a clearer upward trend.
- PCA reduced dimensionality to 3-4 components explaining ~80% variance.
- Regression models found **TV ads, online banners, and promotions significant**, with positive ROI on TV ads but much higher cost-effectiveness on banners.

---

## ✍️ Author

 Kalyani Rajesh Lonkar  
 MSc Business Analytics - University of Manchester  
 Focus on Data Analytics, Marketing Mix Modelling, Forecasting & BI

---


