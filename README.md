# Stock Performance During Global Crises

## Project Background
This project analyzes the performance and resilience of major publicly traded companies across three significant global crises:
- The 2008 Global Financial Crisis
- The COVID-19 Pandemic
- The 2022 Inflation & Geopolitical Shock

The goal is to understand how companies across sectors (Tech, Healthcare, Finance, Consumer, Energy) reacted to market shocks, how long they took to recover, and which stocks remained resilient during volatile periods. In today’s economic climate, understanding sectoral and stock-specific resilience is vital for informed investing, risk management, and economic analysis.

## Project Overview

This project analyzes how five major companies— *AAPL, JNJ, JPM, PG, and XOM* —performed during three global crises: the 2008 Financial Crisis, the COVID-19 pandemic, and the 2022 Inflation & War period.
Stock data was retrieved using the `yfinance` Python library, which pulls historical market data from Yahoo Finance.

Using historical stock data from Yahoo Finance and economic timelines for each crisis, this project explores:

- Volatility trends using rolling 30-day standard deviations
- Cumulative returns for long-term performance tracking
- Time to recovery post-crisis drawdowns
- Crisis-specific resilience scoring based on performance metrics across multiple events

The analysis was performed in Python, and key insights were visualized using Power BI, creating a comprehensive dashboard.

## Tech Stack

- Python: Pandas, Matplotlib, Seaborn, yfinance
- Power BI: Visualizations and dynamic KPI comparisons
- Jupyter Notebook: Data preprocessing, exploratory analysis, and metric calculation

## Business & Analytical Questions

This project was designed to answer key financial questions:

1. Which companies recovered the fastest from major economic shocks?
2. How volatile were different sectors during each crisis?
3. What is the relative resilience of each stock across crises?
4. How does sector impact recovery time and cumulative returns post-crisis?
5. Which stocks showed the most consistent performance regardless of crisis type?

## Key Insights

JNJ (Healthcare) and PG (Consumer Staples) showed the highest resilience across all three crises, reflecting the traditionally defensive nature of these sectors.

XOM (Energy) had extreme variation, performing poorly during the pandemic but strongly during the inflation/war crisis — highlighting sector sensitivity to macroeconomic conditions.

AAPL (Tech) had the strongest post-COVID recovery but was among the most volatile stocks overall.

JPM (Banking) showed high vulnerability during the 2008 crisis but improved in subsequent ones, indicating stronger financial regulation and robustness post-2008.

Recovery times varied significantly: Tech stocks like AAPL recovered quickly post-COVID, while Energy (XOM) lagged after 2008.

## Conclusion & Takeaways

This project offers a comprehensive view of how different stocks and sectors responded to major global crises over the last two decades. By analyzing rolling volatility, recovery time, and cumulative returns, we were able to quantify the resilience of key companies during the 2008 Financial Crisis, the COVID-19 pandemic, and the 2022 Inflation & War crisis. 

The analysis revealed that traditionally defensive sectors like Healthcare (JNJ) and Consumer Staples (PG) remained the most resilient across all three crises, while sectors like Energy (XOM) and Tech (AAPL) showed more event-specific performance variations. Financial institutions like JPM demonstrated improved resilience post-2008, likely due to regulatory strengthening. These insights highlight the importance of sector selection and historical context in portfolio risk management. The interactive Power BI dashboard enables further exploration and comparison, making this framework valuable for investors, analysts, and anyone seeking to understand stock behavior during uncertain times.
