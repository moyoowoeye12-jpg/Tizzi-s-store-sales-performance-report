
<img width="1545" height="868" alt="Phase_Project_Task_Screenshot_OwoeyeMoyosre" src="https://github.com/user-attachments/assets/e43b5a08-3ea7-402b-9a74-73aa031d53b8" />



Important Features and Their Significance:

Sales Trend (2011–2015): Crucial for measuring historical growth.
Top Customer Segment: Identifies the most profitable customer groups (Consumer, Corporate, Home Office).
Top Product Department: Shows which departments (Technology, Furniture, Office Supplies) contribute the most to revenue.
Data Limitations or Biases: As the dashboard focuses primarily on 2015, analysis of long-term seasonal trends is limited. Potential data quality issues (e.g., inconsistencies in store naming) would have been addressed during preprocessing.

Data Splitting and Preprocessing
Data Cleaning & Handling Missing Values: Standard steps like removing duplicates and ensuring consistent data types were performed. Missing values (e.g., if a store location was empty) were likely imputed or the corresponding rows excluded.

Data Transformations: New variables like “Year” were created from the “Order Date” column to facilitate the Sales Trend Report (2011–2015 comparison). Sales figures were aggregated by year, department, and store.

Industry Context: This analysis belongs to the Retail Industry, specifically the supermarket/general goods sector, which relies heavily on sales and inventory optimization.

Stakeholders: Senior Management, Department Heads (e.g., Category Managers), and Store Managers will directly benefit from these insights.

Value to the Industry: Provides a quick and effective method for business intelligence, enabling rapid decision-making regarding inventory stocking, promotional strategies, and customer targeting.

Pre-Analysis
Initial Insights: The data showed a significant upward sales trend, with 2014 being the highest sales year on record (before 2015’s final count) and a clear dominance by the Consumer customer segment.

Potential Correlations: Initial review suggested a strong correlation between the Office Supplies department and specific low-cost/high-volume products like Staples.

In-Analysis
Unconfirmed Insights: The Office Supplies department contributes 30% of sales, yet the Top Selling Products list is dominated by Office Supplies items (Staples, Binders). This suggests high unit volume but potentially lower price points compared to the 35% revenue from Technology (likely fewer, more expensive items).

Analysis Techniques Used in Excel: Heavy use of Pivot Tables to segment sales by customer, department, and store, and Slicers to dynamically filter the underlying data for different views.

Post-Analysis and Insights
Key Findings:

Write on Medium
Sales Trend: The sales show a strong growth trend, peaking at $43,901 in 2014.

Top Customer: The Consumer segment is the most valuable, driving $57,450.60 in sales and accounting for 50% of total customer sales in the main pie chart.

Top Store: Los Angeles is the runaway top-performing store with $175,851 in sales.

Top Product: Staples are the clear winner, accounting for 69.90% of the Top Selling Products group.

Comparison with Initial Findings: The initial assumption of a positive sales trend was confirmed, but the sheer dominance of the Los Angeles store and the high percentage of sales attributed to Staples were surprising outcomes.

Data Visualizations & Charts
Dashboards: The consolidated dashboard effectively brings together sales trends, top customer segments, departmental contributions, shipping mode, top stores, and top products into a single, digestible view. Explanation of Visualizations:

Bar Chart (Sales Trend Report): Clearly shows the YoY sales growth and the peak sales years.
Pie Chart (Top Product Department): Highlights the nearly equal revenue split between Technology (35%) and Furniture (35%), with Office Supplies (30%) close behind.
Bar Chart (Top 5 Performing Stores): Visually emphasizes the Los Angeles store’s significant lead over other locations.
Recommendations and Observations
Actionable Insights:

Store Focus: Investigate the operational excellence of the Los Angeles store to replicate its success model in lower-performing stores like Denver ($12,199).
Product Strategy: Leverage the high-volume demand for Staples (70%) to cross-sell other Office Supplies or promote high-margin items.
Customer Segmentation: Direct marketing efforts should continue to be prioritized toward the Consumer (50%) segment, while strategies for boosting the Corporate (31%) and Home Office (19%) segments should be developed.
Unexpected Outcomes: The dominance of Staples in the top-selling products suggests an opportunity to analyze its profitability vs. high-value items in the Technology/Furniture categories.

Conclusion
Key Learnings: Data visualization is crucial for instantly identifying performance extremes (like the Los Angeles store) and category proportions. Grace Supermarket is a growing business with a strong core consumer base.

Limitations: The dashboard doesn’t show profit or cost, which is essential for a complete profitability analysis. Future work would include this financial dimension.

Future Research:

Analyze Profitability by Product and Store.

Perform a deep-dive analysis into the Denver store’s performance issues.

Investigate the low usage of the Second Class (21%) and Same Day (8%) shipping modes.

