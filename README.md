# trader-sentiment-analysis
Analysis of trader performance vs market sentiment with insights and strategies
# Trader Performance vs Market Sentiment Analysis

## Objective
The objective of this project is to analyze how market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid, and derive actionable trading insights.

## Datasets Used
1. Bitcoin Market Sentiment Dataset (Fear/Greed Index)
2. Historical Trader Data (Hyperliquid)
3. 
## Data Preparation
- Loaded and explored both datasets
- No missing values or duplicates found
- Converted timestamps to datetime format
- Aligned both datasets at daily level
- Merged datasets using date column

### Key Metrics Created
- Daily PnL per trader
- Win rate
- Trade size (USD)
- Trade frequency
- Long/Short ratio

## Methodology
- Performed Exploratory Data Analysis (EDA)
- Compared trader performance across sentiment conditions
- Analyzed behavior changes (activity, trade size, direction)
- Segmented traders into Frequent vs Infrequent groups
- Built a simple predictive model for profitability

## Key Insights

1. Highest profitability and win rate occur during Extreme Greed, indicating strong bullish trends favor traders.

2. Trading activity is highest during Fear, suggesting traders actively exploit volatile market conditions.

3. Trade sizes are largest during Fear, showing increased capital deployment in high-volatility phases.

4. In Extreme Greed, SELL activity increases, indicating profit-taking behavior near market peaks.

5. Win rates are lowest during Extreme Fear, reflecting uncertainty and difficult trading conditions.

6. Infrequent traders outperform frequent traders, showing that trade quality is more important than trade quantity.

##  Strategy Recommendations

- Adjust trading strategies based on sentiment conditions:
  - Increase activity during Fear (high opportunity)
  - Reduce risk during Extreme Fear (high uncertainty)
  - Focus on profit-taking during Extreme Greed

- Prioritize high-quality trades over high-frequency trading

- Apply dynamic position sizing based on market sentiment

## Predictive Model

- Model: Random Forest Classifier  
- Features: Trade size + sentiment  
- Accuracy: ~61.3%

### Insights:
- Behavioral and sentiment features provide predictive signals
- Performance can improve with more advanced features

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook  
2. Upload datasets if required  
3. Run all cells sequentially  


## Conclusion

Market sentiment significantly influences trader behavior and performance. Traders who adapt their strategies based on sentiment—by managing risk, timing trades, and focusing on quality—can achieve better and more consistent results.

## Author
Sakthi Saravana M
