This dashboard is designed for high-impact visualization, allowing users to quickly segment and analyze sales performance across critical dimensions:

• Core KPIs (Key Performance Indicators): Prominent display of essential metrics for an at-a-glance performance check:

• Total Sales

• Average Sales

• Total Number of Items Sold

• Average Product Rating

• Sales Trend Analysis: Deep-dive segmentation to understand performance drivers:

• Sales trends segmented by Outlet Type (e.g., Supermarket, Grocery Store).

• Performance segmented by Store Size and Location.

• Contribution Analysis: Visualizing which product characteristics drive the most value:

• Sales contribution analysis by Fat Content (e.g., Low Fat, Regular).

• Breakdown of sales and item numbers by Item Type (e.g., Snacks, Dairy).

• Interactive Design: Features dynamic filters and slicers for flexible data exploration, enabling users to drill down into specific segments and time periods.


Power BI DAX Measures Used in the Dashboard

1. Core Key Performance Indicators (KPIs)

These measures use simple aggregation functions (SUM, AVERAGE, DISTINCTCOUNT, COUNTROWS) to populate the large cards at the top of the dashboard.

Measures for Visualization (Charts and Tables)

2.1 Outlet Establishment Trend

This visual is likely using the No of Items or Total Sales measure and splitting it by the year of the outlet establishment (derived from a date column in the data model).

2.2 Fat Content & Item Type Analysis

These visuals use the core KPI measures (e.g., Total Sales and No of Items) and display them against the respective categorical columns (Fat Content, Item Type).

2.3 Sales Achieved (Gauge Visual)

This is a critical KPI measure that requires defining both the actual sales and the target


Project Goal and Value Proposition

The primary goal of this dashboard is to enable clear, actionable insights and support the retail management team in optimizing operations and inventory.


