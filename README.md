# Retail Sales Analytics Dashboard

This project explores a retail sales dataset end to end, from data cleaning and exploratory analysis to business insight generation and dashboard planning. The analysis focuses on regional performance, profitability, discount effects, product mix, customer segments, and state-level sales distribution.

## Project Objectives

- Clean and prepare raw sales data
- Perform exploratory data analysis (EDA)
- Identify key drivers of sales and profit
- Support decision-making with clear data visualizations
- Build the foundation for an interactive Power BI dashboard

## EDA Findings

The exploratory analysis uncovered several important business insights:

- The West region generated the highest total sales, exceeding $700,000, while the South recorded the lowest sales among the regions.
- California, New York, Washington, Michigan, and Virginia appeared among the top states by total profit, but several states also showed negative profitability, revealing that strong sales do not always translate into healthy margins.
- Technology was a major driver of sales activity, while the analysis also showed that high sales volume does not necessarily mean high profitability.
- Higher discounts were associated with lower profit, suggesting that discounting strategy should be reviewed, especially for low-margin products and categories.
- States with strong sales but weak or negative profit margins highlight the need to monitor profitability alongside revenue growth.
- Technology-related sub-categories and products made a strong contribution to overall sales, making product-level analysis essential for growth planning.
- Sales and profit patterns were also reviewed by customer segment and ship mode to identify additional operational and customer-based opportunities.

## Visuals and Analysis Notebook

The full EDA workflow is documented in [notebooks/data_exploration.ipynb](notebooks/data_exploration.ipynb).

Key visuals included in the analysis:

- [notebooks/total_sales_by_state.html](notebooks/total_sales_by_state.html) – interactive map of total sales by state
- Bar charts for total sales by region
- Bar charts for total profit by state
- Category and sub-category sales/profit analysis
- Scatter plot showing profit versus discount
- Sales and profit comparison by customer segment
- Sales analysis by ship mode

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Power BI
- Jupyter Notebook
- Git & GitHub

## Repository Structure

```text
Retail-Sales-Analytics-Dashboard/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── reports/
├── src/
├── powerbi/
├── images/
├── requirements.txt
└── README.md
```

This project is part of a growing data science portfolio focused on turning raw business data into actionable insights.