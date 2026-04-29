# U.S. Trade and Macroeconomic Trends (2000-2023)

## Team Members
- Kyle Tabong
- Taylor Hardesty
- Ashrutha Lingampalli

## Project Overview
This project examines how shifts in U.S. imports and exports have corresponded with changes in GDP growth and inflation from 2000 to 2023. We are building an end-to-end data pipeline that pulls, cleans, merges, and analyzes trade and economic data to produce meaningful insights about U.S. macroeconomic conditions.

## Research Question
What economic trends were observed from 2000 to 2023 and how did changes in U.S. trade impact broader macroeconomic conditions?

## Data Sources
- **FRED API** (Federal Reserve Bank of St. Louis) - GDP, CPI, and Trade Balance data
- **World Bank API** - U.S. trade as a share of GDP

## Current Project Status
- [x] Environment set up
- [x] Data pulled from FRED and World Bank APIs
- [x] Raw CSVs saved
- [x] Data cleaning and merging
- [x] Correlation analysis
- [x] Visualizations
- [x] Quarto manuscript

## How to Run
1. Clone this repository
2. Install dependencies:
```
pip install fredapi wbgapi pandas
```
3. Add your FRED API key to the notebook
4. Run `data_ingestion.ipynb` cell by cell

## Dependencies
- Python 3.8+
- fredapi
- wbgapi
- pandas
- Quarto

## File Structure
```
project/
├── README.md
├── data_ingestion.ipynb
├── data/
│   ├── gdp_data.csv
│   ├── cpi_data.csv
│   ├── trade_balance_data.csv
│   └── world_bank_trade.csv
└── output/
    └── manuscript.qmd
```

## Track
This project follows **Track B: End-to-End Pipeline** for INST447.
