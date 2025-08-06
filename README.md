# 📊 Sector Index and Return Analysis

This is a group project for the course **Financial Asset Valuation and Modeling I**.  
I was a member of **Group 6**, responsible for **coding all data visualizations** in this project using R.

---

## 🎯 Project Overview

The project focuses on analyzing stock market data from **3 sectors** on the Ho Chi Minh Stock Exchange:

- **Real Estate**
- **Industry**
- **Finance**

We conducted two main analyses:

1. **Rate of Return (RoR) Analysis**
   - Calculated logarithmic returns of 45 individual stocks.
   - Visualized RoR time series to observe price fluctuations.
   - Found that returns fluctuate around a mean close to zero.

2. **Sector Index Calculation**
   - Calculated and compared sector indices using **three methods**:
     - Price-weighted Average
     - Market-value-weighted Index
     - Equally-weighted Index
   - Adjusted for stock splits where needed.
   - Visualized trends and compared sector performance across methods.

---

## 🧩 Personal Contribution

I was fully responsible for **data visualization**, including:

- Plotting individual stock return series
- Visualizing sector indices by method
- Comparing methods within each sector
- Ensuring the visuals support clear interpretation

---

## 📁 Files in Repository

- `sector_index_and_return_analysis.Rmd`: R file with code, analysis, and visualizations
- `sector_index_and_return_analysis.html`: Rendered HTML output
- `data/`
  - `closing_price.csv`: Daily closing prices for 45 stocks across 3 sectors
  - `market_cap.csv`: Market capitalization data for the same stocks and period
- `slide/`
  - `group6_presentation.pdf`: Slide deck summarizing the methodology and results

---

## 🛠️ Tools

- **R**
- `ggplot2` for visualization
- `dplyr`, `tidyr` for data processing

---

## 📌 Project Info

- **Data source**: [Vietstock.vn](https://vietstock.vn)
- **Period**: Oct 23, 2023 – Sep 23, 2024 (229 observations)
- **Sectors**: Real Estate, Industry, Finance (15 stocks each)

---

## 📎 License

For academic demonstration purposes only.
