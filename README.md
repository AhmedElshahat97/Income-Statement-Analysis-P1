## Project Title

### Income Statement Analysis—FP&A


[![PDF Preview](images/Preview.png)](PDF/Income-Statement-Analysis-FP&A-P1.pdf) 


## Project Objectives

1. Provide a comprehensive analysis of income statement trends from 2018 to 2020.
2. Evaluate key financial metrics such as Sales Revenue, Gross Profit Margin, Net Profit Margin, and Expenses.
3. Identify performance trends by country and region.
4. Support strategic decision-making by visualizing correlations between cost elements and revenue changes.

## Key Insights or Findings
### 1. Revenue Growth:

- Total Sales Revenue increased by 14.62%, from $11.58M in the previous year to $13.27M in the current period.
- The USA contributed the highest Sales Revenue ($2.4M), accounting for 30.73% of total revenue.
- Significant variance across regions:
North America had the highest revenue ($2.89M), followed by Europe ($2.54M) and Oceania ($2.41M).

### 2. Profitability Metrics:

- Gross Profit Margin: 68.2%, showing strong cost management.
- Net Profit Margin: 16.5%, indicating solid profitability after expenses.
- Operating Profit: Increased from $2.22M to $3.73M, marking a 68% improvement.

### 3. Cost Analysis:

- Administration and Marketing Costs showed a negative correlation.
- Q3 accounted for 14.71% of Administration Costs, peaking in July.
- Total Operating Expenses increased by 96.97%, from $3.19M to $6.3M.

### 4. Regional Performance:

- Highest Revenue: USA with $2.4M (470.83% higher than the UK’s lowest revenue of $0.42M).
- Sales Divergence: USA showed the largest discrepancy between previous and current revenue, with previous revenue $3.92M higher.

### 5. Balance Sheet Highlights:

- Current Ratio: 7.49, indicating robust liquidity.
- Quick Ratio: 3.03, showing effective short-term asset management.
- Shareholder Equity declined from $4.78M to $2.54M, primarily due to reduced share capital and dividends paid.

### 6. Reporting and Insights
- Created a final presentation using Canva and PowerPoint to highlight findings.


## Key Questions Explored
1. How have Sales Revenue and Net Profit trended across 2018–2020?
2. Which regions and countries contribute the most to profitability?
3. What are the implications of rising operational costs on EBITDA?
4. How do liquidity ratios compare with industry benchmarks?
5. What are the major variances between regions in revenue and costs?

## Challenges or Limitations
1. Lack of granular data for deeper country-specific operational expenses.
2. Absence of external benchmarking data for financial ratios.
3. Currency exchange impacts and inflation-adjusted metrics were not considered.


## Technical Overview

### Data Model:

- Included tables for Sales, Costs, Regions, and Time Hierarchies.
- Relationships established between date fields and transactional data for drill-downs.

## Measures and Calculations
DAX Measures:

Revenue Metrics:
Total Revenue = SUM(Sales[Revenue])
YoY Growth = ([Current Revenue] - [Previous Revenue]) / [Previous Revenue] * 100
Profitability Metrics:

Gross Profit = [Sales Revenue] - [Cost of Sales]
Net Profit = [Gross Profit] - [Operating Expenses]
Ratios:

Gross Profit Margin = DIVIDE([Gross Profit], [Sales Revenue], 0)
Quick Ratio = (Current Assets - Inventory) / Current Liabilities

## Visualizations:

- Time Series: Line charts showing trends for Revenue, Operating Profit, and Net Profit from 2018–2020.
- Region Performance: Stacked bar charts comparing contributions across North America, Europe, and Oceania.
- Expense Breakdown: Pie chart for the composition of Administration, Marketing, and Sales & Distribution costs.
- Balance Sheet Metrics: KPI cards for Current Ratio, Quick Ratio, and Working Capital.

Conclusion
The analysis highlighted key revenue drivers and cost trends, providing actionable insights into regional and operational performance. The financial ratios underscored strong liquidity but signaled potential risks in declining equity and rising operational costs.

