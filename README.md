Data Science Assignment – Web3 Trading Team
 Project Overview

This project analyzes the relationship between trader behavior and market sentiment using two key datasets:

Historical Trader Data → Contains details like execution price, size, side, leverage, PnL, etc.

Bitcoin Fear & Greed Index → Tracks market sentiment as Extreme Fear, Fear, Neutral, Greed, or Extreme Greed.

The objective is to identify how trading strategies, profitability, leverage usage, and trading volume align or diverge from prevailing market sentiment to help traders make smarter decisions.

 Folder Structure
ds_shreya/
├── notebook_1.ipynb        # Main Google Colab notebook with code & analysis
├── csv_files/              # Datasets used in the project
│   ├── trader_data.csv
│   ├── fear_greed_index.csv
├── outputs/                # Graphs & visualizations
│   ├── volume_vs_sentiment.png
│   ├── sentiment_over_time.png
│   ├── profitability_vs_sentiment.png
├── ds_report.pdf           # Final report summarizing insights
└── README.md               # Project documentation

 Important Links
📓 Google Colab Notebook
https://colab.research.google.com/drive/1YYbmuqEs22tjQxpsqAege-ri6am4rzWL?usp=sharing

Here are the main insights derived from the datasets:

Total Trading Volume vs Market Sentiment
Shows how trading activity changes based on market mood.

Market Sentiment Over Time
Visualizes Fear, Greed, and Neutral phases across the timeline.

Average Trader Profitability vs Market Sentiment
Compares average trader returns under different market conditions.

Methodology

The analysis followed these steps:

Data Preparation

Imported datasets into Google Colab.

Handled missing values and formatted date columns.

Exploratory Data Analysis (EDA)

Visualized sentiment distribution and trends.

Analyzed trading volume, leverage usage, and profitability.

Dataset Merging

Combined sentiment data with trader data to align activity with market mood.

Statistical Insights

Identified key patterns and correlations.

Highlighted actionable insights for better trading strategies.

Reporting

Created a final PDF summarizing findings and visualizations.

How to Reproduce This Project

Open the Google Colab Notebook from the link above.

Mount Google Drive when prompted.

Place the datasets inside the csv_files/ folder.

Run all cells sequentially.

All graphs will be saved automatically inside the outputs/ folder.

Export the final PDF report via Colab: File → Print → Save as PDF.

Author

Name: Shreya Gilda
Submission Date: 20 Aug 202
