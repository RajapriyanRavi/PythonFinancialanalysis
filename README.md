 README: Financial Data Analysis of Procter & Gamble (P&G)

 Project Overview:
This project analyzes the financial performance of Procter & Gamble (P&G) from 2014 to 2018, focusing on key financial metrics such as liquidity ratios, debt ratios, asset analysis, and liabilities. The analysis aims to provide insights into the company's financial health and trends over the fiveyear period.

 Key Features:
 Data Cleaning and Preprocessing:
   Filled missing values with zero (`NaN` → 0).
   Filtered the dataset to focus exclusively on P&G (ticker symbol: `PG`).
  
 Financial Ratios Analysis:
   Quick Ratio: Evaluates the company’s short-term liquidity without relying on inventory.
   Current Ratio: Measures the company's ability to pay off its shortterm liabilities.
   DebttoEquity Ratio: Assesses the company’s financial leverage.

 Asset Analysis:
   Inventory Turnover: Analyzed inventory turnover to evaluate how efficiently inventory is managed.
   Shortterm and Longterm Assets: Compared shortterm assets, liquid cash, and longterm assets over time.

 Liabilities Analysis:
   Short Term Liabilities: Included total current liabilities.
   Short Term Debt: Focused on shortterm financial obligations.
   Dividend Payable & Accounts Payable: Analyzed key obligations the company has toward shareholders and suppliers.

 Libraries Used:
 `pandas`: For data manipulation and analysis.
 `matplotlib`: For visualizing financial trends.
 `numpy`: For numerical computations.

 Data Sources:
The dataset consists of financial data from 2014 to 2018, which is assumed to be in CSV format (`2014_Financial_Data.csv`, `2015_Financial_Data.csv`, etc.).

 How to Run:
1. Ensure the CSV files for the years 2014 to 2018 are available in your project directory.
2. Install necessary libraries:
   ```bash
   pip install pandas matplotlib numpy
   ```
3. Run the Python script in a Jupyter Notebook or any Python environment to see the analysis and visualizations.

 Visualizations:
The project includes bar charts that visualize:
 Liquidity ratios (Quick and Current Ratios).
 Debt to equity ratio.
 Inventory turnover.
 Shortterm and longterm assets.
 Shortterm liabilities, debt, dividends payable, and accounts payable.

 Conclusion:
This analysis provides a detailed look at P&G's financial status over the years, highlighting key metrics that are essential for investors, financial analysts, and stakeholders to make informed decisions.



Feel free to update the project description and usage instructions as per the actual implementation.
