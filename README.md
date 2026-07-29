# Retail Sales Analytics Dashboard

## Business Problem / Description
This project focuses on a retail sales analysis challenge: understanding how sales, profit, discounts, and customer behavior vary across regions, states, categories, and segments. The goal was to turn raw transactional data into a clear, decision-ready Power BI dashboard that helps stakeholders identify profitable opportunities, spot underperforming areas, and improve business strategy.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook
- Power BI
- Git & GitHub

## Workflow
1. Data collection: Imported retail sales data from the provided CSV dataset and organized it for analysis.
2. Data cleaning: Prepared the data by handling inconsistencies, validating fields, and ensuring it was suitable for analysis.
3. Exploratory data analysis (EDA): Investigated sales and profit patterns by region, state, category, sub-category, customer segment, and ship mode.
4. Business analysis: Examined the relationship between discounting and profitability to uncover operational and pricing insights.
5. Power BI dashboard: Built an interactive dashboard to summarize key metrics and support business decision-making.
6. Insights and recommendations: Highlighted areas of growth, risk, and opportunities for improved profitability.

## Dashboard Preview
The dashboard presents a business-focused overview of sales performance, profitability, and key drivers across the retail operation.

![Power BI Dashboard Preview](images/Screenshot%20(933).png)

## Key Insights
- The West region generated the highest total sales, while the South recorded the lowest sales among the regions.
- Strong sales did not always translate into strong profits, revealing that profitability must be monitored alongside revenue growth.
- Technology was a major contributor to sales volume, but the analysis showed that high sales do not always mean healthy margins.
- Higher discounts were associated with lower profit, suggesting that pricing and discount strategies should be reviewed.
- State-level performance showed that some locations were strong revenue generators but weak profit contributors, signaling the need for deeper profitability analysis.

## Recommendations
Based on the analysis, the following recommendations are proposed:

- Continue investing in Technology products, as they generate both strong revenue and high profitability.
- Investigate the profitability of Furniture products to determine whether production costs or discount levels are reducing margins.
- Develop targeted marketing campaigns to improve sales performance in the South region.
- Strengthen customer retention strategies within the Consumer segment while exploring opportunities to grow Corporate and Home Office customers.
- Review the current discount policy to ensure discounts are increasing sales without unnecessarily reducing profits.
- Monitor high-performing sub-categories such as Phones and Chairs to ensure adequate inventory levels and prevent stock shortages.

## Lessons Learned
- Revenue and profit should be evaluated together, since they do not always move in the same direction.
- Discount strategies can significantly affect margin, especially for low-profit products or categories.
- Clear visual storytelling is essential for turning analytics into business action.
- A well-designed dashboard helps non-technical stakeholders quickly understand performance and make better decisions.

## Analysis Notebook
The full exploratory workflow is documented in [notebooks/data_exploration.ipynb](notebooks/data_exploration.ipynb), and an interactive map of state-level sales is available in [notebooks/total_sales_by_state.html](notebooks/total_sales_by_state.html).