# CPI Market Impact Analysis (2020–2026)
SQL • BigQuery • Tableau • Financial Data Analysis

## Project Overview

This project analyzes how financial markets react to U.S. Consumer Price Index (CPI) announcements and inflation surprises.

The study focuses on three assets:

- VOO (S&P 500 ETF)
- SMH (VanEck Semiconductor ETF)
- PLTR (Palantir Technologies)

Using SQL, BigQuery and Tableau, the objective was to determine whether CPI announcement days behave differently from normal trading sessions and how inflation surprises influence market returns and volatility.

---

## Tools Used

- SQL (BigQuery)
- Tableau
- Google Sheets
- Yahoo Finance
- Investing.com

---

## Data Sources

### CPI Data
- Source: Investing.com
- Period: January 2020 – June 2026
- Variables:
  - Date
  - Actual CPI
  - Forecast CPI
  - Previous CPI

### Market Data
- Source: Yahoo Finance
- Assets:
  - VOO
  - SMH
  - PLTR

---

## Methodology

1. Collected CPI announcement data.
2. Downloaded historical price data from Yahoo Finance.
3. Cleaned and standardized datasets.
4. Imported data into BigQuery.
5. Performed SQL analysis.
6. Created Tableau dashboards.
7. Identified key market insights.

---

## Key Findings

- 76 CPI events were analyzed.
- High CPI surprises generated larger market moves.
- PLTR showed the strongest sensitivity to inflation announcements.
- CPI release days represented only 4.72% of trading sessions.
- However, CPI days appeared 33–45% more frequently among the market's most volatile sessions.
- SMH achieved the highest percentage of positive CPI trading days (52.6%).

---

## Business Insights

The analysis suggests that CPI announcements are not necessarily associated with significantly higher average returns. However, they are disproportionately represented among the market's most volatile trading sessions.

The results also indicate that larger inflation surprises tend to generate larger market reactions, particularly for growth-oriented assets such as PLTR.

These findings may help investors and analysts better understand how macroeconomic information impacts market behavior.

---

## Dashboards

### Dashboard 1 — Market Overview

![Dashboard 1](Dashboard%201%20-%20Reaction%20to%20CPI%20Releases.png)

Overview of asset performance during CPI announcement days, including average returns, volatility and percentage of positive sessions.

### Dashboard 2 — CPI Surprise Impact

![Dashboard 2](Dashboard%202%20-%20CPI%20Surprises.png)

Analysis of how low, medium and high inflation surprises affect market returns and volatility.

### Dashboard 3 — CPI vs Normal Trading Days

![Dashboard 3](Dashboard%203%20-%20CPI%20vs%20Normal.png)

Comparison between CPI announcement days and regular market sessions, highlighting volatility and return differences.

### Dashboard 4 — Executive Summary

![Dashboard 4](Dashboard%204%20-%20Executive%20Summary.png)

Executive overview of the most relevant insights obtained during the analysis.
---

## Skills Demonstrated

- SQL Querying
- Data Cleaning
- Data Analysis
- BigQuery
- Financial Data Analysis
- Data Visualization
- Dashboard Design
- Tableau
- Business Communication

---

## Author

Tomás Morales Aragon

Physics Student | Aspiring Data Analyst
