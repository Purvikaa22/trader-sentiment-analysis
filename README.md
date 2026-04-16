# trader-sentiment-analysis
# Trader Performance vs Market Sentiment Analysis
This project analyzes how market sentiment impacts trader behavior and performance using real trading data.

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

## Requirements
- pandas
- seaborn
- matplotlib
- python
  
## Data
The following datasets were used:
- fear_greed.csv (Bitcoin market sentiment data)
- trader_data.csv (Hyperliquid trading data)

## Methodology
- Cleaned and aligned sentiment and trading datasets using timestamps
- Merged datasets at daily level
- Computed metrics like PnL, trade frequency, and position size

## Feature Engineering
- Calculated daily PnL to evaluate trader performance
- Derived trade frequency to measure activity levels
- Computed average position size to understand risk exposure
- Aggregated sentiment data into categorical phases (Fear, Greed, Extreme Fear, Extreme Greed)

## Key Insights
- Trader profitability is highest during Extreme Greed (~205 PnL), suggesting strong momentum-driven gains but also potential risk of overtrading.
- Fear sentiment (~128 PnL) outperforms Greed (~54 PnL), indicating that traders act more cautiously and make better decisions during uncertain market conditions.
- The relationship between sentiment and performance is non-linear, showing that both extreme optimism and extreme fear impact trading behavior differently.
- Trade frequency increases significantly during Greed phases, but higher activity does not necessarily translate into higher profitability.
- Moderate sentiment phases provide more stable and consistent returns compared to extreme sentiment conditions.
  
## Visual Insights
- Scatter plots show a weak but noticeable relationship between sentiment and profitability
- Bar charts highlight that Extreme Greed yields the highest returns but also increased variance
- Time series analysis reveals fluctuations in performance aligned with sentiment shifts
- 
## Future Improvements
- Incorporate real-time sentiment data from news and social media (Twitter APIs)
- Apply machine learning models to predict trader performance based on sentiment
- Use advanced metrics like Sharpe Ratio for risk-adjusted returns
- Analyze individual trader behavior instead of aggregated data

## Strategy Recommendations
- Reduce exposure during Extreme Fear due to uncertainty and unpredictable movements
- Leverage momentum strategies during Extreme Greed, but avoid excessive trading
- Focus on disciplined trading during Fear phases for better risk-adjusted returns
- Avoid overtrading during high sentiment periods as increased activity may reduce profitability
  
## How to Run
1. Open `final_analysis.ipynb`
2. Install required libraries: pandas, seaborn, matplotlib
3. Run all cells
