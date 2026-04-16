# trader-sentiment-analysis
# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

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
2. Run all cells
