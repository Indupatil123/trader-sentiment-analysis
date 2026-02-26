Trader Performance vs Market Sentiment Analysis
📌 Objective

This project analyzes how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and performance on Hyperliquid.

The goal is to uncover behavioral patterns and derive actionable trading strategy insights.

📊 Datasets Used

Bitcoin Fear/Greed Index (Daily sentiment classification)

Hyperliquid Historical Trade Data (Trader-level execution data)

⚙️ Methodology

Cleaned and validated both datasets

Converted and aligned timestamps at daily granularity

Merged trader data with sentiment classification

Engineered key metrics:

Closed PnL

Win rate

Trade frequency

Long/Short ratio

Position sizing

Segmented traders based on activity and behavioral characteristics

🔍 Key Insights

Trading activity is ~3x higher during Fear periods.

Traders maintain a persistent short bias across all sentiment regimes.

Greed periods still show dominant SELL positioning.

Market participation increases significantly during negative sentiment phases.

🚀 Strategy Recommendations

Reduce leverage and trade frequency during Fear regimes.

Monitor crowded short positioning during Greed regimes.

Implement sentiment-aware risk management rules.

▶ How to Run
pip install pandas numpy matplotlib seaborn
jupyter notebook analysis.ipynb
📌 Notes

Analysis performed at daily aggregation level.

Results are exploratory and can be extended with volatility modeling or predictive frameworks
