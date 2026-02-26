Trader Performance vs Market Sentiment Analysis
Objective

The goal of this project is to analyze how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid. The analysis aims to identify patterns that can help design smarter trading strategies.

Datasets Used

Bitcoin Market Sentiment dataset

Date

Sentiment classification (Fear / Greed / Neutral)

Hyperliquid Trader Data

Account activity

Trade direction

Closed PnL

Trade timestamps

Position details

Methodology
Data Preparation

Loaded both datasets into Python (Google Colab)

Checked missing values and dataset structure

Converted timestamps into datetime format

Merged trader data with sentiment data using date alignment

Feature Engineering

Created key metrics:

Win rate per sentiment

Trader profitability (Closed PnL)

Trade frequency

Long vs Short behavior

Trader segmentation (high vs low activity)

Analysis Performed
1. Performance vs Market Sentiment

Compared win rates across Fear, Greed, and Neutral markets

Identified how trader success varies by sentiment

2. Behavioral Patterns

Studied long vs short positions

Observed changes in trade frequency during Fear and Greed periods

3. Trader Segmentation

Classified traders into:

High-frequency vs Low-frequency traders

Profitable vs Non-profitable traders

Key Insights

Trader win rate is highest during Extreme Greed conditions.

Fear and Extreme Fear markets show lower profitability.

Greed markets encourage confident trading behavior.

Fear markets lead to cautious or loss-driven trading.

High-frequency traders dominate market activity and influence overall trends.

Strategy Recommendations
Strategy 1 — Risk Control in Fear Markets

Reduce position size

Avoid aggressive trading

Focus on capital preservation

Strategy 2 — Momentum Trading in Greed Markets

Increase trade participation carefully

Follow market trends

Use disciplined profit booking

Tools & Technologies

Python

Pandas

Seaborn

Matplotlib

Google Colab

Outcome

This analysis demonstrates that market sentiment significantly influences trader behavior and profitability. Understanding sentiment-driven patterns can help design data-driven trading strategies and improve decision-making.

How to Run

Open notebook in Google Colab

Upload datasets

Run all cells sequentially

Visualizations and insights will be generated automatically
