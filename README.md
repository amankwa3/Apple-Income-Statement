# Apple Income Statement


> To explore more of my projects and follow my data journey, visit my [Portfolio](https://www.notion.so/ansaa-data-portfolio/Hey-there-I-am-Ansaa-16041da5e7d080b0a6a6e14d7a65a71d).

Table of Contents

- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
    - [Customer Lifetime Value and Purchase Frequency Trend](#Customer-Lifetime-Value-and-Purchase-Frequency-Trend)
    - [Review Ratings Trend](#Review-Ratings-Trend)
    - [Retention Rate Trend](#Retention-Rate-Trend)
    - [Promo Codes, Distance and Location Trend](#Promo-Codes-Distance-and-Location-Trend)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#clarifying-questions-assumptions-and-caveats)

</details>


## Project Background


Apple Inc., founded in 1976, is a global leader in consumer electronics, software, and services, renowned for its innovation and ecosystem-driven business model. I collaborate closely with the Finance Team and Business Strategy Team to analyze revenue trends, assess profitability, and evaluate key financial metrics such as operating margin and income. Utilizing web scraping techniques, I gather real-time stock performance, market sentiment and key financial figures from Yahoo Finance to enhance financial forecasting and strategic decision-making. These insights drive data-backed recommendations that support revenue maximization and long-term business growth.

## Executive Summary

Apple's financial analysis highlights the strong correlation between **Operating Expenses and Profitability (+0.665)**, pointing to the importance of strategic spending. To optimize costs, Apple should focus on AI-driven automation and invest in high-return projects without compromising growth. The **fluctuations** in Operating Income show a clear need for predictive analytics and flexible financial planning to manage risks from market shifts and supply chain disruptions. Additionally, the negative correlation between **Cost of Revenue and Operating Margin (-0.310)** underscores the need to improve supply chain efficiency and negotiate better deals with suppliers to reduce costs while maintaining innovation, ultimately supporting long-term profitability and stability.



## Insights Deep-Dive
Python is used to answer key stakeholder questions and further visualization of the results is done in Tableau, enabling more informed and strategic decision-making.

 ### **Revenue Trend**

 Growth Percentages are calculated as:


 **How has year-over-year (YoY) revenue growth trended, and what factors explain fluctuations?**

The top 4 factors influencing Year-over-Year (YoY) revenue growth are Gross Profit Growth, Cost Growth, Operating Income Growth, and Net Income Growth. Notably, Gross Profit Growth has the highest correlation (0.98), indicating that pricing strategies and cost efficiency are key revenue drivers. Cost Growth (0.97), while positively correlated, suggests that cost management is crucial for sustaining profitability. Operating Income Growth (0.91) reflects operational efficiency, with streamlined processes boosting revenue. Net Income Growth (0.85), though important, shows a weaker correlation, likely due to tax strategies and one-time expenses. These insights highlight the importance of balancing profitability and efficiency to drive sustainable revenue growth.



**What percentage of total revenue is contributed by each metrics ?**

**Total Expenses** emerges as the largest contributor to overall revenue, accounting for **55.50%**. Close behind is **Reconciled Cost of Revenue** at **44.72%**, with **Cost of Revenue** also contributing **44.72%**, reflecting a balanced impact. **Gross Profit** follows with a solid **34.98%**, highlighting its importance in the overall financial performance.

On the lower end, **Other Income Expense** contributes a minimal **-0.03%**, while **Tax Rate for Calls**, **Diluted EPS**, and **Basic EPS** all show **0%** due to the absence of relevant data. **Net Interest Income** contributes a small **0.01%**, making its mark though it remains minor.


### **Operating Margin Trend**

Operating Margin is calculated as:

*** 

**Which operational costs (e.g., cost of revenue, operating expenses) are having the most significant impact on the operating margin, and how can they be optimized?**

**Operating Expenses** emerge as the most significant driver of **Operating Margin (%)**, showing a strong positive correlation of **+0.665**. This suggests that increased spending in this area may contribute to higher profitability, likely through strategic investments in efficiency and growth.

In contrast, **Cost of Revenue** has a weaker negative correlation of **-0.310**, indicating that higher production or service costs reduce profitability. Optimizing production efficiency and cost management will be key to improving margins.
### **Retention Rate Trend**

***

**How has our profitability evolved over the years, and what factors are driving changes in Operating Income and Operating Margin?**
Year	Operating Margin (%)	Operating Income (Sum)	Insights
2024	31.150	123,216,000	Highest profitability. The increase in both Operating Margin and Operating Income suggests improved cost efficiency, revenue growth, or a combination of both.
2023	29.82	114,301,000	Profitability decline. Operating Income dropped despite a stable margin, indicating possible revenue stagnation or higher non-operating costs.
2022	30.289	119,437,000	Recovery year. Higher Operating Income than 2023 despite a similar margin, suggesting better cost control or revenue rebound.
2021	29.782	108,949,000	Lowest profitability. Indicates higher costs, lower revenue, or operational inefficiencies compared to later years.

Profitability is improving overall, with 2024 showing the best performance. 2023 was a setback year, with a dip in Operating Income despite a stable margin, possibly due to higher fixed costs or external economic factors. 2022 marked a rebound, with better income despite a lower margin than 2024.  2021 had the weakest profit performance, but steady improvements have been made.
### Promo Codes, Distance and Location Trend

***

**How has the change in Cost of Revenue impacted our Operating Margin rankings over time?**

Insights from Cost of Revenue % Difference and Operating Margin Rank:
Year	% Difference in Cost of Revenue	Rank of Avg Operating Margin	Insights
2021	0.0%	4 (Lowest)	Baseline year. No change in Cost of Revenue, but Operating Margin was the weakest.
2022	+4.96%	2	Increase in Cost of Revenue, yet a strong Operating Margin ranking.Suggests revenue growth or better cost efficiency absorbed the higher costs.
2023	+0.27%	3	Slight cost increase, but Operating Margin ranking declined. Indicates margin pressures, potentially due to revenue stagnation or higher fixed costs.
2024	-0.413%	1 (Highest)	Cost of Revenue decreased, and Operating Margin improved. Shows strong cost control, revenue growth, or both driving higher profitability.


# Overall Dashboard of Trends


## Recommendations

**Optimize Cost Management for Higher Margins**

The negative correlation between **Cost of Revenue** and **Operating Margin (-0.310)** highlights the need for cost efficiency. Apple should focus on its supply chain, secure better deals with suppliers, and integrate smart technology to cut costs without sacrificing quality. Balancing cost reduction with innovation will be key to boosting profitability.

**Enhance Revenue Growth Through Pricing & Product Strategy**

Since **Gross Profit Growth (0.98)** is the strongest driver of revenue, Apple should optimize **pricing models, product differentiation, and market expansion strategies** to maximize revenue potential. A focus on premium products and bundling high-margin services can sustain strong growth.

**Improve Operational Efficiency & Expense Allocation**

A strong correlation between **Operating Expenses and Profitability (+0.665)** shows that **spending smartly is key**. Apple should focus on **using AI to automate tasks, simplifying operations, and investing in high-impact projects** that bring real value making sure every dollar spent fuels growth without unnecessary costs.

**Strengthen Financial Forecasting & Risk Mitigation**

With Operating Income fluctuating, Apple should **leverage AI-driven predictive analytics, strengthen risk-diversification tactics, and adopt flexible financial planning** to stay ahead of market shifts, supply chain challenges, and economic uncertainties. Taking a **proactive approach to risk management** will help ensure long-term financial stability.

## Clarifying Questions, Assumptions, and Caveats
- **`Revenue` Data Consistency:**
    
    How should we handle variations in `revenue` data across different regions or product categories to ensure consistency in our analysis?
    
- **`Cost and Expense` Breakdown:**
    
    Are all `costs and expenses` categorized correctly in the financial statements, and how can we ensure no critical expenses are overlooked in our cost analysis?
    
- **Impact of `External` Economic Factors:**
    
    How should we account for external market factors (e.g., inflation, global supply chain issues) when analyzing `operating margins and profitability`trends?
    

Assumptions and Caveats

- **Cost Structure:**
    
    The financial data assumes that Apple’s `cost structure` is consistent across the board, which might not be the case if there are major fluctuations in production or operational costs during the analysis period.
    
- **Seasonal Trends:**
    
    `Revenue and profitability` analysis is based on typical seasonal patterns; however, shifts in consumer demand, such as due to new product launches or global events, could affect these trends.
    
- **Risk from External Factors:**
    
    Assumes no `major disruptions` like global recessions, political instability, or technological changes. Any of these could significantly impact future profitability and market trends.


---

- See the web scrapping and my cleaning and analysis in this Jupyter Notebook.
- See my Tableau Dashboard in [this file](https://public.tableau.com/app/profile/afua.ansaa.amankwaah/viz/ApplesIncomeStatementAnalysis/Dashboard3).
- For more of my projects and data journey, visit [my portfolio website and reach out!](https://www.notion.so/Hey-there-I-am-Ansaa-16041da5e7d080b0a6a6e14d7a65a71d?pvs=21)



