# Stock Data Analysis: Tesla & GameStop

## Project Overview
This project uses Python to collect, clean, and visualize historical stock-price data and annual revenue data for Tesla (TSLA) and GameStop (GME).

## Objectives
- Retrieve historical stock data using `yfinance`.
- Extract annual revenue tables from HTML pages.
- Clean financial values using Pandas.
- Visualize stock prices and revenue using Matplotlib.

## Tools & Libraries
- Python
- Pandas
- yfinance
- Requests
- BeautifulSoup
- Matplotlib
- Jupyter Notebook

## Workflow
1. Import libraries and define a reusable graphing function.
2. Download Tesla and GameStop historical stock data.
3. Scrape annual revenue tables from the provided IBM Skills Network pages.
4. Clean revenue values and handle missing records.
5. Visualize stock prices and revenue for each company.

## Key Notes
- The revenue tables are static educational sample data and contain records only through 2021.
- Yahoo Finance stock history may contain more recent dates than the revenue tables.
- The `tail()` output can show the oldest years because the source revenue table is ordered newest-to-oldest.
- Charts retain the assignment's historical cutoffs.

## How to Run
1. Download or clone this repository.
2. Install dependencies:
   ```bash
   pip install yfinance pandas requests beautifulsoup4 matplotlib lxml
   ```
3. Open `Stock_Data_Analysis_Portfolio.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook cells from top to bottom.

## Data Sources
- Yahoo Finance via the `yfinance` Python library.
- IBM Skills Network Tesla revenue sample:  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm
- IBM Skills Network GameStop revenue sample:  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html

## Skills Demonstrated
Data extraction · Web scraping · Data cleaning · Pandas · Data visualization · Python

## Disclaimer
This is an educational data-analysis project, not investment advice.
