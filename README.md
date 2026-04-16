# trader-sentiment-analysis
# Trader Performance vs Market Sentiment Analysis
This project analyzes how market sentiment impacts trader behavior and performance using real trading data.

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

## Requirements
- pandas
- seaborn
- matplotlib
  
## Data
The following datasets were used:
- fear_greed.csv (Bitcoin market sentiment data)
- trader_data.csv (Hyperliquid trading data)

## Methodology
- Cleaned and aligned sentiment and trading datasets using timestamps
- Merged datasets at daily level
- Computed metrics like PnL, trade frequency, and position size

## Key Insights
- Profitability peaks during Extreme Greed (~205 PnL)
- Fear periods (~128 PnL) outperform Greed (~54), indicating disciplined trading
- Performance is non-linear across sentiment phases

## Strategy Recommendations
- Reduce exposure during Extreme Fear
- Use momentum carefully during Extreme Greed while avoiding overtrading

## How to Run
1. Open `final_analysis.ipynb`
2. Install required libraries: pandas, seaborn, matplotlib
3. Run all cells
