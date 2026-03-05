### Supply Chain Analytics & Demand Insights

## Project Overview
In this project, I analyzed supply chain data to understand sales performance, customer behavior, delivery efficiency, and product demand. The goal was to extract useful insights that can help businesses improve their supply chain operations.

The analysis was done using Python for data exploration and demand forecasting and Power BI to build an interactive dashboard for visualization.

---

## Tools Used
- Python
- Pandas
- Matplotlib
- Stats models (ARIMA Forecasting)
- Power BI

---

## Data Analysis Using Python
Python was used to clean and explore the dataset before building the dashboard.

## Steps

- Cleaned the dataset and handled missing values
- Converted date columns into proper datetime format
- Created additional features such as delivery delay
- Aggregated sales data over time to analyze trends
- Built a time series forecasting model (ARIMA) to predict future demand

## Key Insights from Python Analysis

- Sales demand stayed relatively stable across most months.
- Some product categories contribute significantly more revenue than others.
- Delivery delays occur when the actual shipping time exceeds the scheduled shipping time.
- Late delivery risk indicates potential inefficiencies in the logistics process.

---

## Demand Forecasting
To understand future demand, time series forecasting model (ARIMA) was applied to the sales data.

## Predicted Sales
| Month      | Predicted Sales |

| Feb 2018   | ~335K           |
| Mar 2018   | ~319K           |
| Apr 2018   | ~324K           |

## Why This Is Useful

Forecasting helps businesses:
- Plan inventory levels
- Prepare for demand changes
- Improve supply chain planning and logistics operations

---

## Power BI Dashboard
A Power BI dashboard was created to visualize key supply chain metrics and insights.

## Dashboard Preview

![Supply Chain Dashboard](dashboard.png)

## Key Metrics

- Total Sales
- Total Profit
- Total Orders

## Dashboard Insights

- The Consumer segment generates the highest sales revenue.
- Western Europe and Central America contribute the most sales.
- Standard shipping mode is the most commonly used delivery option.
- Some orders show late delivery risk, which could indicate logistics issues.
- A few product categories drive a large portion of total revenue.

---

## Conclusion
This project shows how data analysis and visualization can be used to understand supply chain performance. By identifying sales trends, customer behavior, and delivery risks, businesses can make better decisions about inventory, logistics, and demand planning.