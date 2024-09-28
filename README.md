# SALES-PERFORMANCE

#Overview
This sales dashboard was created to analyze the performance of various key metrics in sales, including revenue, profit, and order quantities across different dimensions such as customers, products, regions, channels, and warehouses. The interactive dashboard allows stakeholders to view top performers, understand geographic trends, and assess channel and warehouse efficiencies. The data was cleaned using Power Query, SQL was used for Q&A analysis, and Power BI was leveraged for data visualization.

#Objectives
The primary objective of this sales dashboard is to:
•	Monitor and analyze sales performance at various levels (e.g., customer, region, product, and channel).
•	Provide key insights into top revenue-generating customers and regions.
•	Track order quantity distribution and profit margins across channels and warehouses.
•	Identify performance bottlenecks and potential areas for improvement in sales and logistics.

#Aim
The dashboard aims to:
•	Present a clear and actionable visual overview of key sales metrics.
•	Enable decision-makers to identify high-revenue customers, products, and regions.
•	Assist in improving distribution strategies by analyzing channel and warehouse performance.
•	Offer trend-based insights to forecast future sales and improve decision-making.

#Data Processing 
  Refined and Transformed Data: Power Query was used to clean and prepare the dataset by removing duplicates, correcting data types. This foundational step ensured data relevance and accuracy for analysis.
•	Fact and Dimension Table Setup: Power Query was also utilized to handle the creation of fact and dimension tables, setting up complex data relationships. This enabled dynamic filtering across the dashboard, allowing users to interact with the data seamlessly.
•	SQL for Q&A: SQL was employed to run specific queries aimed at answering business questions, such as identifying top customers, regions, and products by revenue and order quantity. This step helped generate valuable insights, which were later visualized in the dashboard.
•	Advanced Data Modeling: By leveraging DAX and Power Query, advanced calculations and manipulations were applied. These sophisticated data modeling techniques provided deeper insights, such as calculating monthly trends, customer revenue contributions, and performance across multiple channels.

#Key Features
•	Revenue by Customers: The top customers contributing to the revenue are displayed, offering insights into the most profitable customer base.
•	Top 10 Cities: Key cities driving sales are visualized, helping businesses focus on high-performing regions.
•	Order Quantity by Currency: Provides an understanding of how different currencies contribute to the overall sales volume.
•	Revenue by Region: A geographical breakdown of revenue, providing a regional performance snapshot, particularly focusing on the highest sales in key cities.
•	Revenue & Profit by Product: Highlights the products contributing the most revenue and profit, aiding product-specific sales strategies.
•	Revenue & Profit by Channel: Shows performance across wholesale, distributor, and export channels, guiding channel-specific business strategies.
•	Warehouse Performance: Revenue generated by each warehouse is visualized, assisting in capacity planning and logistics management.

#Visualization
•	Bar Charts: Used to visualize top customers, products, and cities.
•	Donut Chart: Displays the share of order quantities across different currencies.
•	Map Visualization: Geographical revenue distribution by region, providing easy-to-digest insights into where sales are most concentrated.
•	KPI Indicators: Key metrics such as total revenue, order quantities, and profit are displayed prominently for quick interpretation.

#Tools Used
•	Power Query: For data cleaning and transformation.
•	SQL: For running queries and answering business questions.
•	Power BI: For data visualization and building interactive dashboard elements.

#Analysis-Based Recommendations
•	Focus on Top-Performing Regions: Based on the analysis, Christchurch, Hamilton, and Waitakere are the top revenue-generating cities. More marketing and sales efforts should be focused on these high-performing areas to maximize revenue.
•	Expand Export Channels: The dashboard shows a significantly lower contribution from export channels compared to wholesalers and distributors. Strategic initiatives, such as partnering with international distributors, could expand market reach.
•	Product Line Diversification: The dashboard highlights a few products that generate the bulk of revenue. It’s important to diversify the product line and focus on low-performing products (e.g., Product 11 and Product 5) to increase overall sales.
•	Warehouse Performance Improvement: There are notable disparities in revenue generation by warehouses, with AXW291 generating the most. Assessing the efficiency of underperforming warehouses (e.g., FLR025) could help optimize logistics.
•	Currency Risk Assessment: The reliance on specific currencies (NZD, AUD) shows concentrated sales in certain markets. To mitigate exchange rate risks, the company could explore increasing sales in more stable currencies or hedge against currency risks.
•	Customer Loyalty Programs: The top customers (Medline, Pure Group) should be targeted for retention strategies, to ensure sustained sales contributions. Additionally, identifying and nurturing smaller but promising customers could improve the customer base.
•	Channel Optimization: The revenue and profit by channel indicate that wholesalers drive the bulk of sales, while export and distributor channels lag behind. A deeper analysis into why these channels underperform could lead to better resource allocation or operational improvements.

#Conclusion
The analysis of the sales dashboard highlights several key areas of strength in the company’s sales strategy, such as strong performance from key customers, high-revenue cities, and dominant wholesale channels. However, there are opportunities for improvement, particularly in optimizing export channels, addressing the performance of certain underperforming products, and improving warehouse logistics.

#Key Findings:
•	High Performance in Specific Regions: Cities like Christchurch and Hamilton are strong revenue generators.
•	Product Mix Optimization: Some products are underperforming and may require better promotion or optimization.
•	Channel Imbalance: The company’s focus on wholesale channels has led to underperformance in export and distributor channels.
