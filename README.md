**Trading Behavior & Market Sentiment Analysis
Overview**

This project investigates the relationship between cryptocurrency trader behavior on the Hyperliquid exchange and Bitcoin market sentiment using the Fear & Greed Index. The objective was to determine how market emotions influence trading profitability, win rates, trade volume, and overall trading performance.

By combining historical trading records with sentiment data, the analysis uncovers statistically significant behavioral patterns that can support data-driven trading and risk management strategies.

**Datasets Used
Bitcoin Fear & Greed Index**

**Market sentiment dataset containing daily classifications:**

Extreme Fear
Fear
Neutral
Greed
Extreme Greed
Hyperliquid Historical Trading Data

**Trading dataset containing:**

Account Information
Trading Symbol
Execution Price
Position Size
Trade Direction
Timestamp
Leverage
Closed Profit & Loss (PnL)
Position Details
Objectives
Analyze how market sentiment affects trading profitability.
Compare win rates across sentiment categories.
Study trading volume behavior under different market emotions.
Validate findings using statistical testing.
Generate actionable trading and risk management insights.
**Methodology**
**1. Data Cleaning & Preprocessing**
Standardized timestamps and date formats.
Converted PnL and volume fields into numerical values.
Aligned trading records with corresponding sentiment data.
Handled missing and inconsistent values.
**2. Data Integration**
Merged trader activity with daily Fear & Greed Index values.
Created a unified dataset for sentiment-based performance analysis.
**3. Exploratory Data Analysis**

**Performed analysis on:**

Sentiment distribution
Profitability by sentiment
Trading volume patterns
Win rate comparison
**4. Statistical Testing**

Applied the Kruskal-Wallis test to verify whether profitability differences across sentiment groups were statistically significant.

**5. Visualization**

Generated multiple visualizations to identify trends and support conclusions.

Key Findings
Metric	Result
Most Profitable Sentiment	Extreme Greed
Average PnL During Extreme Greed	$67.89
Least Profitable Sentiment	Neutral
Average PnL During Neutral Markets	$34.31
Highest Win Rate	Extreme Greed (52%)
Lowest Win Rate	Extreme Fear (37%)
Statistical Significance	p-value = 0.0000
**Major Insights**
Traders achieved the highest profitability during Extreme Greed periods.
Extreme Fear conditions produced the lowest trading success rates.
Trading volume decreased significantly during fearful market conditions.
Sentiment has a measurable and statistically significant impact on trading performance.
**Trading & Risk Management Recommendations
Contrarian Trading
Explore buying opportunities during Fear and Extreme Fear periods when markets may be overreacting.
Dynamic Position Sizing
Increase caution during highly emotional market conditions.
Adjust exposure according to sentiment intensity.
Risk Management
Apply stricter stop-loss mechanisms during volatile sentiment phases.
Reduce concentration risk during extreme market conditions.
Sentiment Monitoring
Use shifts in market sentiment as potential indicators of trend reversals and changing market conditions.
**Technologies Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Google Colab
**Outputs Generated**
Processed Data
merged_dataset.csv
performance_summary.csv
**Visualizations**
Sentiment Distribution Analysis
Profit/Loss by Sentiment
Trading Volume by Sentiment
Win Rate by Sentiment
**Business Impact**

This analysis demonstrates how sentiment-driven insights can support:

Algorithmic Trading Systems
Portfolio Risk Management
Dynamic Position Sizing
Trading Strategy Optimization
Market Timing Decisions

The project showcases practical applications of data science, statistical analysis, financial analytics, and behavioral market research within cryptocurrency trading environments.
