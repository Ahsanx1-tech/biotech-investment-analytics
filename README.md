# biotech-investment-analytics
A comprehensive Exploratory Data Analysis (EDA) project examining the biotech funding landscape from 2009 to 2026. This project leverages Python (Pandas, Seaborn, Matplotlib) to analyze a diverse dataset of M&amp;A, VC, IPO, and Crossover deals.

# Biotech Investment Landscape: 17-Year Funding Analysis (2009-2026)

## 📌 Project Overview
This project provides a deep-dive analysis into the financial ecosystem of the biotechnology and pharmaceutical industries. Using a dataset covering nearly two decades of deal flow, I performed Exploratory Data Analysis (EDA) to understand how capital is distributed between early-stage innovation (VC/Series B) and massive industry consolidation (M&A).

## ❓ Problem Statement
Traditional financial analysis tools often struggle with the extreme scale and variance found in pharmaceutical investment cycles, where deal values range from $10M venture rounds to $70B strategic acquisitions. Standard spreadsheets encounter bottlenecks when processing these high-variance datasets. This project demonstrates the efficiency of **Python** in automating unit conversions, statistical aggregations, and complex outlier detection.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** 
  - `Pandas` (Data Manipulation)
  - `Seaborn` (Statistical Visualization)
  - `Matplotlib` (Custom Plotting)
- **Environment:** Google Colab / Jupyter Notebooks

## 📊 Key Visualizations & Analyses

### 1. Annual Funding Velocity (Line Chart)
Tracks the total capital flow into the biotech sector, identifying market peaks and historical shocks.

### 2. Deal Composition (Bar Chart)
Analyzes the frequency of M&A vs. VC deals to determine market maturity and the innovation pipeline.

### 3. Top Investors (Horizontal Bar Chart)
Identifies the primary movers and strategic acquirers deploying the most capital in the sector.

### 4. Capital Distribution (Box Plot)
Statistically maps the spread of deal values. This visualization is crucial for identifying "Megadeal" outliers that define industry-wide consolidation events.

## 💡 Key Insights
- **Capital Skewness:** The biotech market is heavily skewed toward a small number of massive M&A deals, while the volume of deals is driven by consistent, smaller VC investments.
- **Market Resilience:** Despite volatility, the data shows a clear upward trend in capital deployment, indicating a robust long-term outlook for biotech innovation.
- **Outlier Impact:** Individual "Megamergers" ($40B+) significantly alter the market landscape and happen in predictable cycles.

## 📂 Repository Structure
- `biotech_funding.csv`: The primary dataset.
- `biotech_analysis.ipynb`: The Google Colab/Jupyter notebook containing the analysis code.

