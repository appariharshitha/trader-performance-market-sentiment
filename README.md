# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid.

## Datasets
- Bitcoin Fear & Greed Index (daily sentiment)
- Hyperliquid historical trader data (private dataset)

## Methodology
- Cleaned and aligned both datasets at daily level
- Engineered key metrics such as daily PnL, win rate, leverage, trade frequency
- Segmented traders by leverage, activity, and consistency

## Key Insights
- Trader performance differs significantly between Fear and Greed days
- High leverage traders incur higher losses during Fear sentiment
- Frequent traders perform better during Greed sentiment

## Strategy Recommendations
- Reduce leverage exposure during Fear days
- Increase trade frequency selectively during Greed sentiment
- Prefer consistent traders for capital allocation

## How to Run
1. Upload datasets to the notebook environment
2. Open the notebook file
3. Run cells sequentially
