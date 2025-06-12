
# GDP and Well-being: EU vs USA

This repository contains data and code based on the final dissertation of my Bachelor’s Degree in Economics:  
"Limits of GDP as a measure of welfare: A comparison between Europe and the United States".

## Project goals

- Clean and transform raw macroeconomic data (GDP per capita, public and private expenditure, productivity and labour market, well-being indexes)
- Calculate key indicators: levels, ratios, annual growth rates, cumulative growth rates
- Visualize data using Power BI, R and Python
- Showcase dashboard and scripts used in the dissertation

## Structure

-Excel file organization

Raw and processed Excel files are organized by chapter:

- `data/raw/CHAPTER 1/`: GDP per capita, productivity, decomposition of GDP from Output side
- `data/raw/CHAPTER 2/`: Public and private spending analysis
- `data/raw/CHAPTER 3/`: Labour market indicators and key categories of expenditure, well-being indexes

Some Excel files include:
- Pivot tables
- Charts and dashboards
- Formula-driven calculations

Temporary Excel files (starting with `~$`) are excluded from the analysis.

- `src`: Python scripts (ETL, KPI calculations)
- `reports`: final dashboards, visuals, documentation

## Technologies

- Python (pandas, matplotlib)
- Power BI
- R (ggplot2)
- SQL (SQLite)
