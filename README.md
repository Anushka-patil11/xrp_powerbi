
# Project Title: XRP Cryptocurrency Analysis and Visualization using Power BI
link to dashboard - https://app.powerbi.com/links/R96XKJss1n?ctid=b4b62109-b5e5-499a-a5da-97f68d962343&pbi_source=linkShare 

link to dashboard pdf- -https://drive.google.com/file/d/11xRh9lLc4qwk0hQK9BU9TVOIyTQ_-rhG/view?usp=sharing

#Background and Problem:

Cryptocurrencies play an essential role in the modern financial market. XRP, one of the prominent cryptocurrencies, has exhibited significant price changes over time. Understanding these changes and analyzing the data is crucial to making informed decisions regarding trading or investments.

This project focuses on visualizing XRP data using Power BI to identify key insights such as profit/loss patterns, price trends, and trading volumes.

#Objective:

The objective of this project is to:

-Visualize XRP data over 44 weeks using various Power BI charts.
-Identify key information like the highest and lowest prices, profit and loss, and the trends associated with trading volumes.

-Highlight the periods and days that witnessed the most profitable trades.

#Data:

The data used in this project includes cleaned XRP trading information over 44 weeks. Key metrics like the sum of Open, Close, High, and Low prices, as well as trade volumes and profit/loss calculations, have been used to generate insights.

#Linkk to data :
https://docs.google.com/spreadsheets/d/1qu9p2mcDrKRz2mWn1f0CuZbga3dn5tczelW3HK5gMSo/edit#gid=0

#Method:

Imported the cleaned XRP dataset into Power BI.
The data includes metrics like prices (Open, Close, High, Low), volumes, and dates.

#Data Modeling:
#Created calculated measures for Profit and Loss (PnL) using the formula:

PnL = (Exit Price x Sell Volume) – (Entry Price x Bought Volume)

Power BI formula:
PnL = ('Sheet1 (2)'[Close]* 'Sheet1 (2)'[taker_sell_volume])-('Sheet1 (2)'[Open]*'Sheet1 (2)'[Taker buy base asset volume])
-Measures like sum of profit, sum of loss, average PnL for specific time periods have been derived.

#Visualization Creation:

-Candlestick Bar Chart: Used to visualize daily price movements of XRP.
snap of candlestick bar -
![xrp3](https://github.com/user-attachments/assets/1f817e14-9bfa-4eae-abb8-6ebce0c3a0e7)



-Pie Chart: Representing trading volumes by date.

-Bar Chart: Showing the proportion of winning vs losing trades.

#Dashboard Creation:
dashboard snapshot- 
![xrp4](https://github.com/user-attachments/assets/d01d0b63-2637-4eeb-9862-5bb75af3ac23)


dashboard snapshot-
![xrp-5](https://github.com/user-attachments/assets/5b2cd4bb-8fea-4af4-aacf-8dcce2021506)



-Various charts have been compiled into a comprehensive dashboard for deeper insights. 

-The dashboard shows trends in prices, profit/loss analysis, and trading volumes across different periods.

-Filters have been applied to segment the data by time period, trading days, and specific trade metrics.

#Formatting and Styling:

Applied formatting to ensure the visuals are easy to interpret, with clear labels and consistent color schemes for profit vs loss.

#Results:

1-Price Analysis:
-The highest price recorded for XRP in the 44-week period was $0.938, while the lowest was $0.34.
-Max Close: $0.8199, Max Open: $0.8198
-Min Close: $0.4622, Min Open: $0.4622

2-Profit and Loss Analysis:
-Over the 44-week period, the total profit was $27.67 billion while the total loss was $172.42 million.
-The month of July stood out, recording the highest profits at $5.2 billion with a trading volume of 12 million trades.

3-Trading Volume Insights:
-A total of 65 million trades were recorded, with March having the highest volume (10M trades) and July experiencing the highest profitability.
-November had the lowest number of trades with 405K trades, likely due to limited data for that month.

![xrp1](https://github.com/user-attachments/assets/d030d6ad-b8fb-404e-9e7d-e036e49743ca)


4-Day-wise Profitability:
Fridays recorded the highest average profit based on the day-wise comparison of PnL.

5-Monthly Trends:
-July yielded the most profit, while May saw the highest losses.
November had the least trading activity.
![xrp2](https://github.com/user-attachments/assets/f853b6ee-6fdd-4a9b-96ac-79e5837f4cef)


#Power BI Dashboard:

The Power BI dashboard contains the following key visualizations:
-Candlestick Chart: Depicts daily price fluctuations (Open, Close, High, Low).

-Profit and Loss Bar Chart: Shows PnL over time, with clear distinctions between profitable and loss-making periods.

-Trading Volume by Month: Displays total trade volumes for each month of the 44-week period.

-  Win/Loss: A quick glance at the ratio of winning vs losing trades.

