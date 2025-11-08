
ds_siddhi - Bitcoin Market Sentiment vs Trader Behaviour Analysis

Project Overview:
This project investigates how Bitcoin market sentiment, as measured by the Fear/Greed Index, influences trader behavior. 
It explores trade decisions, trade sizes, and profit/loss outcomes to understand if market emotions are reflected in actual trading actions.

What Was Done:
- Imported historical Bitcoin trade data along with Fear/Greed sentiment data.
- Cleaned datasets by removing duplicates and aligning timestamps.
- Categorized market sentiment into Extreme Fear, Fear, Neutral, Greed, and Extreme Greed.
- Merged datasets based on date to connect sentiment with trade data.
- Calculated metrics including average trade size, trade direction distribution, and profitability.
- Created visual insights such as bar charts, boxplots, and correlation heatmaps.
- Saved charts in the 'outputs' folder and generated a final PDF report.

Key Insights:
- Traders take smaller positions and execute more sell trades during Fear and Extreme Fear periods.
- During Greed and Extreme Greed periods, buy trades increase, positions are larger, and average PnL improves.
- Overall, trader behavior clearly follows market sentiment patterns.

Files Included:
- notebook_1.ipynb: Data cleaning, analysis, and visualization.
- notebook_2.ipynb: Summary and final insights.
- csv_files/: Raw datasets.
- outputs/: Generated charts.
- ds_report.pdf: Final report.
- README.md: This document.

Technology Used:
Python, Pandas, Matplotlib, Seaborn, FPDF.

Purpose:
The project links market psychology to trading decisions, helping with risk management, position sizing, and developing sentiment-based trading strategies.

About the Author:
Name: Siddhi Pradip Katkar
LinkedIn: https://www.linkedin.com/in/siddhi-katkar01/
GitHub: https://github.com/Siddhi1412/Siddhi1412
