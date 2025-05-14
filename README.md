# Bitcoin Trader Performance & Market Sentiment Analysis
## Overview
This project explores the relationship between trader performance and market sentiment in the Bitcoin market. 
Using proprietary sentiment data and detailed historical trading records, we uncover actionable patterns, identify elite and contrarian traders, and provide a foundation for advanced trader ranking systems. 
The analysis is designed to inform smarter trading strategies and product development.

## Datasets
Bitcoin Market Sentiment Dataset: Daily sentiment classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral) and a sentiment index value. 
Historical Trader Data: Trade-level details including account, execution price, size, side, time, position, PnL, and more. Key Features

## Data Alignment:
Trades are mapped to the prevailing sentiment regime on their execution date. Advanced Feature Engineering: For each trader and sentiment regime, we compute: Total PnL Number of Trades Average Trade Size Winrate Maximum Drawdown Profit Factor Rolling Sharpe Ratio Trading Frequency ROI

## Statistical Analysis:
Trader performance is compared across sentiment regimes. Elite and contrarian traders are identified and ranked. Correlations between sentiment and trading outcomes are explored. Visualization & Reporting: Bar plots, heatmaps, and leaderboards. Well-structured report with actionable insights.

##How to Run
Clone the repository and add the datasets (fear_greed_index.csv and historical_data.csv). Open analysis_notebook.ipynb in Jupyter or VSCode. Run all cells to reproduce the analysis, generate tables, and create visualizations. Review the final report (Bitcoin_Trader_Sentiment_Report.docx) for a summary of findings and recommendations.

## Key Findings
Trader performance is highest during Greed and Extreme Greed regimes. Certain traders consistently outperform in specific sentiment regimes, while others excel as contrarians during Extreme Fear. There is a positive correlation between market sentiment and average trading outcomes. The developed ranking system enables identification of elite traders under different market conditions.

## Recommendations
Focus on strategies that exploit Greed and Extreme Greed regimes. Study contrarian traders for risk-hedging or mean-reversion strategies. Integrate sentiment-aware analytics and leaderboards into trading platforms.

## Limitations & Next Steps
Results are based on historical data; future market conditions may differ. Transaction costs, slippage, and leverage effects are not fully accounted for.

## Future work: Incorporate more features (volatility, volume), apply machine learning, and explore regime-switching models.
