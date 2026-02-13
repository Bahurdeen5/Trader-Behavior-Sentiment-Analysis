# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes the relationship between Bitcoin market sentiment 
(Fear vs Greed) and trader behavior.

## Methodology
1. Data cleaning and timestamp alignment
2. Merging trader data with sentiment index
3. Creating key metrics:
   - Daily PnL
   - Win rate
   - Trade size analysis
   - Trade frequency
4. Sentiment-level comparison
5. Trader segmentation (frequent vs infrequent, consistent vs inconsistent)
6. Strategy recommendations

## Key Insights
- Extreme Greed periods show the highest average profitability.
- Fear periods involve larger average trade sizes.
- Trade behavior varies significantly across sentiment regimes.
- Larger trades are associated with higher average PnL but increased volatility risk.

## Strategy Recommendations
1. Apply aggressive trend-following strategies during Extreme Greed periods with risk controls.
2. Introduce volatility-adjusted position sizing during Fear regimes.

## How to Run
1. Open the notebook in Jupyter or Google Colab.
2. Install required libraries: pandas, numpy, matplotlib, seaborn.
3. Place the datasets in the same directory.
4. Run all cells sequentially.

## Author
Bahurdeen U
