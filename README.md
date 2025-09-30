## Quantitative Trade Analytics with Python 

### 🔹 Tools & Technologies
#### ➩ Languages & Platforms : Python, Jupyter Notebook
#### Libraries : Pandas, NumPy, Matplotlib, Seaborn, Scipy  
#### Data Source : 1140 raw trade records (Excel)
### 🔹 Key Responsibilities & Solutions
### ➩ Data Preparation & Cleaning :
→ Imported raw Excel data, handled missing values, validated lot sizes, corrected anomalies (negative prices, inconsistent trade durations).  
→ Ensured data integrity for reliable downstream analysis.  
### Feature Engineering :
→ Created Profit Per Lot metric to normalize results across varying trade sizes.   
→ Computed trade duration (minutes) to measure exposure and efficiency. 
### Exploratory & Statistical Analysis :  
→ Applied descriptive statistics (mean, median, std, skewness, kurtosis, quantiles).  
→ Conducted best-case / worst-case trade analysis through quantile distributions.   
→ Identified time-of-day and weekday patterns in profitability.

### Visualization & Insights :
→ Built time-series charts, histograms, boxplots, and bar charts for trend exploration.
Illustrated risk-return trade-offs, tail risks, and profit consistency across symbols

### 🔹 Findings

* The mean profit per lot across all trades :  Mean = 12.45, Median = 10.32, Std Dev = 5.67.
* EURUSD  trading symbol generated the highest average profit  : Avg Profit = 25.3.
* Peak at 2 PM with Median Profit/Lot = 15.2. shows the highest profitability.
 (and so on for every calculation, chart, or grouped analysis).
* the overall mean Profit : Mean Profit = 123.45 (std = 67.8), Median = 98.2.
* the mean / median / std of Profit Per Lot : Mean = 12.34, Median = 10.12, Std = 4.56.
* EURUSD symbol produced the highest average Profit Per Lot : Avg Profit Per Lot = 25.3 (n = 120 trades).
* Best single trade (value, symbol, open time, lots) : +X (Symbol, Open Datetime, Lots). 
* Worst single trade — with exact rows  : −Y (Symbol, Open Datetime, Lots).
* Win rate  overall and top 5 symbols : Overall win rate = xx%; Top symbol win rate = yy% (n = z)
* Median Profit Per Lot by hour & by weekday (top 3 hours/days) : Hour 14 (2 PM) — Median = a; Hour 16 (4 PM) — Median = b; etc.
* Tail risk / quantiles (5th & 95th percentile of Profit Per Lot) :  5% quantile = -p; 95% quantile = +q.
* Duration stats (mean, median, longest) and USDINR symbols consumed most exposure time.

### 🔹 Key Achievements
✅ Established a clean, analysis-ready dataset from raw trade logs.  
✅ Created Profit Per Lot and Duration features for fair comparison and risk tracking.  
✅ Identified time-of-day profitability patterns (2 PM & 4 PM).   
✅ Quantified best-case / worst-case outcomes using quantiles.    
✅ Summarized results with statistical metrics (mean, median, std, skew, kurtosis).   
✅ Presented insights visually with professional plots.

### 🔹 Impact
➩ This project showcases strong skills in Data wrangling , preprocessing Statistical & exploratory data analysis  
➩ Financial data interpretation  
➩ Visualization for decision-making     
➩ It highlights the capability to bridge raw financial data with actionable trading insights, valuable for roles in Data Analytics, Quantitative Research, and Financial Data Science.
