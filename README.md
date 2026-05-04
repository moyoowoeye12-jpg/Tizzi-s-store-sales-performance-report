
<img width="1891" height="862" alt="Tableau Task 50_Screenshot" src="https://github.com/user-attachments/assets/0a87002b-564c-4e51-8639-3432ba32a25f" />


Technical Report: Sales Performance Analysis for Tizzie's Store (2020)


1. Introduction


•	Objective of the Project: The primary goal of this analysis is to evaluate the sales performance of Tizzie's Store for the fiscal year 2020 to 	identify key revenue drivers across regions, customer segments, and product categories. 

•	Problem Being Addressed: This report seeks to identify which specific segments and regions are performing optimally and which operational areas 	(such as shipping modes) are most utilized, providing a data-driven foundation for 2021 strategic planning. 

•	Key Datasets and Methodologies: The analysis utilizes the train[1].csv dataset. Methodologies include data cleaning, pivot table aggregation for 	metric calculation, and the development of a centralized Excel dashboard to visualize KPIs. 



2. Story of Data


•	Data Source: The data is derived from the "train[1].csv" file, representing internal transactional records for Tizzie's Store.
 
•	Data Collection Process: Data was recorded through the store's point-of-sale and order management systems throughout the year 2020. 

•	Data Structure: The dataset is organized by transactions, featuring variables such as Order Date, Region, Customer Name, Segment, Product Sub-	Category, and Sales Volume. 

•	Important Features: Key features include Segment (Consumer, Corporate, Home Office), Region (West, East, Central, South), and Shipping Mode, all of 	which are critical for understanding logistical and marketing efficiency. 


3. Data Splitting and Preprocessing


•	Data Cleaning: Procedures involved removing duplicate entries and ensuring all currency values were standardized for accurate summation.
 
•	Data Transformations: Dates were grouped into the "2020" fiscal year to focus the analysis on the specific reporting period.
 
•	Data Splitting: The "Sales" column served as the dependent variable, while "Region," "Segment," and "Sub-Category" were treated as independent 	variables to determine their impact on total revenue. 

•	Industry Context & Stakeholders: This analysis falls within the Retail Industry. Key stakeholders include the Sales Operations team, Supply Chain 	managers, and Senior Management. 



4. Pre-Analysis

•	Key Trends: Initial observation indicated a heavy lean toward the Western region and a massive preference for "Standard Class" shipping.
	
•	Initial Insights: Preliminary views suggested that the "Consumer" segment contributes more than 50% of the store's total revenue, signaling a 	potential area for loyalty program expansion. 


5. In-Analysis

•	Analysis Techniques: Advanced Excel functions and Pivot Tables were used to categorize the top 4 performing states and identify the highest-spending 	customers. 

•	Discovered Insights:

•	The West Region is the powerhouse of the store, generating $710,219.68.
 
•	Phones and Chairs are the dominant product drivers, both exceeding $320,000 in sales.
 
•	Recommendations: Based on the dominance of the Consumer segment ($1,148,060.53), marketing efforts should be concentrated here to maximize ROI. 


6. Post-Analysis and Insights

•	Key Findings: The analysis confirms that Tizzie's Store is highly reliant on the California market ($446,306.46) and the Consumer segment. 

•	Comparison: Initial expectations of a balanced regional spread were disproven; the West and East regions combined significantly outperform the 	Central and South regions. 


7. Data Visualizations & Charts

•	Top Performing Region: A pie chart illustrates the West leading with $710,219.68, followed by the East.
 
•	Top Performing Segment: A column chart highlights the Consumer segment as the largest revenue contributor at over $1.1M.
 
•	Best Shipping Mode: A bar chart shows Standard Class ($1,340,831.31) far exceeding all other modes combined. 


8. Recommendations and Observations

•	Actionable Insights: Invest in inventory for Phones and Chairs, as these are the high-velocity sub-categories.
 
•	Business Decisions: Evaluate the cost-efficiency of "Standard Class" shipping; since it is the primary choice, any small reduction in per-unit 	shipping costs will lead to significant bottom-line savings. 

•	Unexpected Outcomes: The "Same Day" shipping mode is underutilized ($125,219.04), suggesting either a high price barrier or a lack of customer 	urgency. 


9. Conclusion

•	Key Learnings: California and New York remain the critical hubs for the business. The Consumer segment is the primary engine of growth.
 
•	Limitations: The analysis is limited to the year 2020; year-over-year growth comparisons were not conducted in this specific scope. 

•	Future Research: Further investigation into the South region's lower performance ($389,151.46) is needed to identify barriers to entry or 	competition. 


References & Appendices

•	Source 1: Technical Report Template for Analytical Projects in Tableau.

•	Source 2: Tizzie's Store Sales Dashboard 2020 / train[1].csv dataset.



