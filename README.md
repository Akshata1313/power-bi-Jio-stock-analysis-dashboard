# JIO Financial Services Ltd. - Stock Data Analysis Dashboard

This Power BI dashboard provides a comprehensive analysis of stock price movements, trading volume, volatility, and technical indicators for **JIO Financial Services Ltd.**, helping investors and analysts identify trends, make decisions, and monitor performance over a one-year period.

## Project Objective

To build a dynamic and interactive dashboard that visualizes stock performance using:
- Moving Averages (MA20, MA50)
- Resistance and Support Levels
- Volume and Volatility Trends
- Buy/Sell Signals
- Key metrics like 52-week high/low, last close price, and total volume

## Tools & Technologies Used

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Excel (.csv) stock price dataset**

## DAX Measures Used (Key Highlights)

- LTP CHANGE % = (Last Close - Previous Close) / Previous Close * 100`
- 52 WEEK HIGH & LOW calculated using MAXX & MINX over a rolling 52-week window.
- MA20, MA50 are Calculated over 20 and 50 periods.
- **Sell Signal Logic** = Conditional formatting based on moving average crossovers or trend analysis.
- Rewsistance and Support Levels are calculated.

## Dashboard Components

| Section | Description |
|--------|-------------|
| **Header KPIs** | Displays 52-week High/Low, Last Close Price, LTP %, Total Volume, and Signal |
| **Moving Averages** | Plots 20-day and 50-day MAs alongside Close Price |
| **Volume Analysis** | Horizontal bar chart showing daily trading volume |
| **Volatility Trend** | Line chart representing 20-day rolling volatility |
| **Resistance & Support** | Line chart showing Close price vs. Support & Resistance levels |

## Insights Derived

- The **Sell Signal** indicates a downward trend confirmed by MA_20 crossing below MA_50.
- The **price dropped** from around ₹394 to ₹229 in the last 12 months, showing a bearish sentiment.
- **Volatility spikes** align with volume surges, indicating market reactions during critical periods.
- Price consistently broke **support levels**, confirming trend reversal.
- Useful for identifying entry/exit points for traders using technical indicators.



