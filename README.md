# Visualizations-in-Tableau-and-Power-BI

## Overview
The purpose of this repository is to show the use of Tableau and Power BI for data visualization projects. There are two completed projects contained within: one in Tableau and the other in Power BI. Both dashboards show various charts such as bar charts, columns charts, donut charts, line charts, scatter-plots, and map charts.

## Tornado Analysis in Tableau
This dashboard completed in Tableau provides info on data collected for tornados that occurred in the US from 1950 to 2022. The original dataset contains info on the number of tornados each year, date and time, state, number of injuries and fatalities, estimated resulting property loss, length in miles, and more. I added a month column going off of the date column to gather insights on the number of tornados occurring by month.

The dashboard contains several graphs/charts providing info on various tornado statistics. See below:
- Tornados by Year - Line chart showing the number of tornados that occurred each year.
- Tornados by Month - Column chart showing the number of tornados that occurred each month as a total for the entire dataset.
- State Map - Map chart that shows the number of tornados totaled for the dataset that occurred in each state. Texas had the highest count of tornados.
- Property Loss vs Tornado Length - Scatter plot showing the correlation between how far each tornado traveled and the resulting property loss.
- Fatalities vs Tornado Length - Scatter plot showing the correlation between how far each tornado traveled and the resulting fatalities.
- Cards - Total tornados, property loss, fatalities, and injuries.

Review the dashboard *[HERE](https://public.tableau.com/app/profile/matthew.sanders1757/viz/TornadoDashboard_17221868410840/SummaryDashboard)*

The original dataset can be found at this link *[kaggle.com](https://www.kaggle.com/datasets/sujaykapadnis/tornados)*

The main takeaways or insights gathered from this analysis are that most tornados occur around the mid-west region of the US. Additionally, the summer months from April to August experienced the most tornados with May having just over 15k tornados total for that month based on the entire dataset.

## Sales Data Analysis in Power BI
This dashboard created in Power BI provides sales performance reports for a fictitious online retail company for the first half of 2015. The original data contains info for a list of orders. The details include region, state, city, postal code, order date, profit, quantity, sales, ship mode, customer segment, product category, and more. I added a month column to calculate sales and profit by month. I chose this dataset because it presented a good opportunity to show the use of Power BI to create informative dashboards on important KPIs that a business would use to make decisions such as where and when to focus marketing and resources for revenue growth.

The dashboard contains several graphs/charts providing info on various sale KPIs. See below:
- Sales by Month - Line chart showing total sales by month.
- Profit by Month - Line chart showing total profit by month.
- Sales by Region - Donut chart showing total sales by region.
- Sales by Customer - Stacked column chart showing total sales by customer segment and the type of products those customers frequently purchased.
- Sales by Product - Stacked column chart showing total sales by product and how much of each product was shipped using various methods.
- Sales by Product Container - Bar chart showing total sales by product container.
- Sales by State - Bar chart showing the top 10 states that had the highest sales.
- Cards - Total sales and profit.

Review the dashboard *[HERE](https://github.com/msanders25/Visualizations-in-Tableau-and-Power-BI/blob/main/Sales%20Dashboard.pbix)*

The original dataset can be found at this link *[powerbidocs.com](https://powerbidocs.com/2019/11/28/power-bi-sample-data-set-for-practice/)*

The main insights that can be gathered for this company are that for the first half of the year, they are most profitable during the summer months of April to June and most of their sales are derived from the East region. Additionally, their corporate customers purchased the most mainly purchasing technology and furniture products so marketing efforts and product availability can be increased in those areas.
