# TCS-stock-market-dashboard
The TCS Stock Trend Analysis & Visualization (2018–2023) project involved a comprehensive examination of Tata Consultancy Services’ stock performance over a five-year period, with the objective of identifying patterns, seasonal fluctuations, and growth trends across multiple timeframes — daily, monthly, quarterly, and yearly. Historical market data, including open, close, high, and low prices for over 1,500 trading days, was sourced through the Yahoo Finance API and stored in CSV format. The dataset underwent rigorous preprocessing in Excel and Python (Pandas, NumPy) to remove missing values, eliminate duplicates, and derive time-based fields such as day, month, quarter, and year. Further calculations and key performance indicators (KPIs) were created in Power BI using DAX to aggregate totals, measure year-on-year percentage changes, and ensure accuracy. 

First page of my dashboard gives an overall picture of TCS’s stock performance from 2018 to 2023.
At the top, I have four KPI cards: ₹3.28M for both Open and Close totals, ₹3.32M for High, and ₹3.25M for Low. The fact that Open and Close are almost equal shows that over the years, the net change between market open and close prices has been minimal, reflecting stability.
The two charts in the middle summarize yearly trends:
On the left, the vertical stacked bar chart compares yearly Open and Close totals. We can see a steady rise from 2018 to 2022, peaking in 2021–2022, and then a drop in 2023, which is mainly due to partial-year data.
On the right, the horizontal stacked bar chart shows yearly High and Low totals. The gap between High and Low is fairly consistent, indicating moderate volatility, and the highest values appear in 2021 and 2022.
Below that, I’ve included time-based breakdowns:
Day-wise: Prices stay within a narrow daily range of around ₹60K–₹120K, with small dips at the month’s end.
Month-wise: Highs in January and December, and lows in April, showing seasonal patterns.
Quarter-wise: Q2 dips followed by Q3–Q4 recoveries, matching business cycles.
Year-wise: Steady growth until 2022, then a 2023 dip from incomplete data.

The second page has interactive dashboard that featured four primary visualizations: a day-wise line chart illustrating intra-month volatility, a month-wise chart revealing seasonal highs in January and December with lows around April, a quarter-wise trend showing mid-year dips in Q2 followed by recovery in Q3 and Q4, and a year-wise analysis highlighting steady growth until 2022 with a 2023 decline attributed to partial-year data. KPI cards summarizing cumulative open, close, high, and low values were positioned at the top for quick reference. Insights from the project included the identification of three major seasonal patterns, a 45% growth phase between 2020 and 2022 driven by post-pandemic IT demand, and a consistent alignment of open and close values over time, indicating market stability. This project not only demonstrates proficiency in data acquisition, cleaning, and visualization but also reflects the ability to contextualize financial data for strategic investment decision-making.

In last page,each row represents a specific trading day between 2019 and 2023, with exact price values.
The Total row aggregates the entire dataset:
Total Open: ₹32,82,408.75
Total Close: ₹32,80,687.32
Total High: ₹33,15,146.94
Total Low: ₹32,46,703.48
These totals match the KPI figures from the first page, ensuring consistency between the raw data and the dashboard visuals.
This page serves as the source verification for the analysis, showing that all visual insights are backed by accurate, complete underlying data.
