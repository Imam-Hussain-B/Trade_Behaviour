# Trade_Behaviour
🟦 1. Objective
Explore how market sentiment (Fear/Greed) influences trader behavior, performance, and coin sensitivity in crypto markets.

🟨 2. Dataset Summary
📌 a. Sentiment Data
Columns: date, classification (Fear, Greed, etc.)

Daily market mood indicator

📌 b. Trader Data
Columns: Account, Coin, Closed PnL, Side, Size USD, etc.

Individual crypto trade records

🟧 3. Data Preparation
Date conversion & formatting

Handled missing values

Merged datasets on trade date

Final columns used: Coin, Closed PnL, Size USD, Side, classification

🟪 4. Exploratory Data Analysis (EDA)
Analysis	Key Findings
Avg. Profit per Sentiment	Highest in Extreme Greed (+205.8 USD), lowest in Extreme Fear (+1.89 USD)
Avg. Trade Size per Sentiment	Highest in Fear ($5744), lowest in Extreme Greed
Buy/Sell Behavior	More Buy trades in Greed, more Sell in Fear
Coin-Specific Insights	Some coins perform better in specific sentiment zones

Include visuals like:

Boxplot: Closed PnL by sentiment

Bar chart: Avg trade size by sentiment

Countplot: Buy/Sell trades per sentiment

Bar chart: Avg PnL by Coin & Sentiment

🟫 5. Insights & Recommendations
Summarize what you discovered:

Trade carefully in Extreme Fear

Prioritize active trading in Greed/Extreme Greed

Adjust coin strategies based on sentiment (e.g., avoid @1 in Greed)

🟨 6. Conclusion
Sentiment strongly influences crypto trading behavior.
By combining sentiment data with trade performance, we can design smarter, sentiment-aware strategies to manage risk and improve profitability.
