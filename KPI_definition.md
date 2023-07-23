# Our Approach:  
1. Consistent long-term performance rather than short-term gains

2. Selection criteria based on historical Performance according to the Performance Persistence Paradigm: 

Performance Persistence means that the future performance of mutual funds can be predicted through their
past performance’ that is the past performance of the fund schemes is an indicator of their future
performance.
[Link for Source](https://www.researchgate.net/publication/325115723_A_Review_of_Performance_Indicators_of_Mutual_Funds)

# Selection criteria for an investment fund

## __1. Return__

|KPI|Average Return|Yearly Return |
|---|---|---|
|Definitions|The mean return of a fund is a measure of the average percentage increase or decrease in the fund's value over a specific period.|percentage increase or decrease in the fund's value over a year|
|Direction |__the higher,the better__|__the higher,the better__|
|Names in our Dataset| fund_mean_annual_return_10years|fund_return_2006 until fund_return_2020 |

## __2. Risk Profile KPI__ 
||[Link for Source](https://www.investopedia.com/investing/measure-mutual-fund-risk/)| _"Risk is one word, but it is not one number._"Harry Kat, professor of risk management  |[Link for Source](https://www.forbes.com/advisor/investing/sharpe-ratio/#:~:text=The%20Sharpe%20Ratio%20is%20calculated,a%20measure%20of%20its%20volatility.) |
|---|---|---|---|
|KPIs|Alpha|Beta|Sharpe Ratio|
|Definitions| Difference between what I have earned (Actual in %) and what I should earn (Expected benchmark in %) | The volatility or systematic risk of the fund portfolio, compared to the market as a whole| indicates risk-adjusted return. Use to compare peer with same level of return  *__Sharpe Ratio = (expected return –  risk-free rate) / Standard deviation__|
|Interpretations|__*1__. a null alpha means that the actual return = the expected return, __*2__. a positive alpha means that the fund outperforms the market and __*3__. an alpha of -1.0 would indicate an underperformance of 1%. |__*1__. a beta lower than one suggests that a stock is less risky than the market. __*2__. a beta of one suggests that the stock moves in sync with the market,  __*3__. a beta of more than 1.0 indicates that the investment's price will be more volatile than the market. For example, if a fund portfolio's beta is 1.2, it is theoretically 20% more volatile than the market.| In comparison to peers, the greater an investment's Sharpe ratio, the better its risk-adjusted performance|
|Direction |__the higher,the better__| __the lower , the better__|__the higher the ratio, the better__| 
|Names in our Dataset|fund_alpha_10years|fund_beta_10years|fund_sharpe_ratio_10years	| 

## __3. ESG risk Profile__ 


|KPI|ESG Risk|
|---|---|
|Definition| Potential negative impacts that arise from Environmental, Social and Governance factors |
|Direction|__the lower , the better__|
|Names in our Dataset|esg_score|

Environmental Pillar

Climate change impacts the ESG score by measuring carbon emissions, product carbon footprint, financing environmental impact, and climate change vulnerability.
Natural capital comprises the topics of water stress, biodiversity and land use, and raw material sourcing.
Pollution and waste are tied to toxic emissions, packaging material, and electronic waste.
Environmental opportunities look at a company’s usage of clean tech, green building, and renewable energy.
Social Pillar

Human capital comes from labor management, health and safety, human capital development, and supply chain labor standards.
Product liability encompasses product safety and quality, chemical safety, consumer financial protection, privacy and data security, responsible investment, and insuring health and demographic risk.
Stakeholder opposition includes controversial sourcing and community relations.
Social opportunities regards access to communication, access to finance, access to health care, and opportunities in nutrition and overall health.
Governance Pillar

Corporate governance is scored through the board, employee pay, ownership, and accounting.
Corporate behavior is defined through business ethics and tax transparency.



## __4. Optional KPI__ 

Reputation- Rating: morningstar_risk_rating
