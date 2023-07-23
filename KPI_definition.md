# Introduction:  

In this project, we aim to assist with mutual fund investment decisions by employing a range of key performance indicators (KPIs) that consider return expectations, risk profile, ESG risk positioning, and optional factors like the Morningstar Rating.

Our approach revolves around analyzing the historical performance of funds using the Performance Persistence Paradigm. This paradigm posits that a mutual fund's future performance can be predicted based on its past performance.[Link for Source](https://www.researchgate.net/publication/325115723_A_Review_of_Performance_Indicators_of_Mutual_Funds)


__We emphasize that this exercise is solely for educational purposes and does not constitute any form of financial advice.__

# Selection criteria for a Mutual Fund (MF)

## __1. Return__

|KPI|Average Return|Yearly Return |
|---|---|---|
|Definitions|The mean return of a fund is a measure of the average percentage increase or decrease in the fund's value over a specific period.|percentage increase or decrease in the fund's value over a year|
|Direction |__the higher,the better__|__the higher,the better__|
|Names in our Dataset| fund_mean_annual_return_10years|fund_return_2006 until fund_return_2020 |

## __2. Risk Profile__ 
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

## __4. Optional KPIs__ 

Reputation- Rating: morningstar_risk_rating
