# Our Approach:  
1. Consistent long-term performance rather than short-term gains

2. Selection criteria based on historical Performance according to the Performance Persistence Paradigm: 

Performance Persistence means that the future performance of mutual funds can be predicted through their
past performance’ that is the past performance of the fund schemes is an indicator of their future
performance.
[Link for Source](https://www.researchgate.net/publication/325115723_A_Review_of_Performance_Indicators_of_Mutual_Funds)

## Funds Characteristics 

|Characteristics | Columns|
|---|---|
|Inv. Fund age |1. inception_date	|
|Inv. Fund size and details |2. total_net_assets, 3. fund_category	,  4. fund_family 5. exchange_timezone|
|Inv. strategies | 6. investment strategies, 7. investment types  |
|Reputation- Rating|9. morningstar_risk_rating|
|__Financial and ESG Performance__| __Columns__|
|Inv. Fund Risk Profile| 10. fund_alpha_10years	11. fund_beta_10years 12. fund_sharpe_ratio_10years|  
|Inv. Funds Fees| 13. fund_mean_annual_return_10years|
|Returns| 14. fund_annual_report_net_expense_ratio|
|Sustainability| 15. esg_score|

# Selection criteria for an investment fund

## __1. Risk Profile KPI__ 
||[Link for Source](https://www.investopedia.com/investing/measure-mutual-fund-risk/)| _"Risk is one word, but it is not one number._"Harry Kat, professor of risk management  |  |
|---|---|---|---|
|KPIs|Alpha|Beta|Sharpe Ratio|
|Definitions| Difference between what I have earned (Actual in %) and what I should earn (Expected benchmark in %) | The volatility or systematic risk of the fund portfolio, compared to the market as a whole| indicates risk-adjusted return. Use to compare peer with same level of return  *__Sharpe Ratio = (expected return –  risk-free rate) / Standard deviation__|
|Interpretations|__*1__. a null alpha means that the actual return = the expected return, __*2__. a positive alpha means that the fund outperforms the market and __*3__. an alpha of -1.0 would indicate an underperformance of 1%. |__*1__. a beta lower than one suggests that a stock is less risky than the market. __*2__. a beta of one suggests that the stock moves in sync with the market,  __*3__. a beta of more than 1.0 indicates that the investment's price will be more volatile than the market. For example, if a fund portfolio's beta is 1.2, it is theoretically 20% more volatile than the market.| In comparison to peers, the greater an investment's Sharpe ratio, the better its risk-adjusted performance|
|Direction |__the higher,the better__( DESC)| __the lower , the better__(ASC)|__the higher the ratio, the better__| 
|Names in our Datasets|fund_alpha_10years|fund_beta_10years|fund_sharpe_ratio_10years	| 
|Range in our Datasets |*Max 25.92    *Min -37.20 |*Max 5.21  *Min -25.34 |Max  2.63  Min -4.36	| 


## __2. Fees__

fund_annual_report_net_expense_ratio
.
## __3. Return Profile KPI__ 

fund_mean_annual_return_10years	


|KPI|Fees|Return|
|---|---|---|
|Definitions|is a measure of the total annual operating expenses of the fund, expressed as a percentage of its average net assets. It represents the costs incurred by the fund to manage and operate the investment portfolio|The average annual return of a fund is a measure of the average percentage increase or decrease in the fund's value over a specific period.|
|Direction |__the lower, the better__(ASC)|__the higher,the better__( DESC)|
|Names in our Datasets|fund_annual_report_net_expense_ratio| fund_mean_annual_return_10years|
|Range in our Datasets |*Max 25.92    *Min -37.20 |*Max 5.21  *Min -25.34 |Max  2.63  Min -4.36	| 


