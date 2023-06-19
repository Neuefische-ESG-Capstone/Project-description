# Project-description
# ESG_ Sustainable Finance Capstone project

In this project, we plan to combine our Python, SQL, and Tableau skills and use them in combination with each other.  

## Objective

We are a Data Analyst team of a big Consulting Firm in Europe and our clients are considering expanding their investments in Investment Funds ( MF and ETF) in the United States. 


However, our customers want to expand their investments while maintaining their values and the sustainability standards set out in Europe. They want to make investments with returns that are not only adjusted to financial risk but also take into account environmental, social, and governance dimensions. 

Our consulting firm has a data set of all Mutual Funds and ETFs in the USA with characteristics, returns, and sustainability scores, and we are responsible to help our clients to select 500 top MF taking into account their different investor profiles and combining the factors: financial performance and ESG dimensions. 


We will answer the following questions : 
Where do I invest if I want to maximize financial return and align with my values and engagement for sustainability 

## __Research Questions__ 
|Questions|Hypothesis|
|---|---|
|1. Which Inv. Funds are leaders in financial performance on average? | X strategy, X type, X regions, Large and Older Mutual Funds because of experience |
|2. Which Inv. Funds are leaders in ESG performance on average ?|Small and new Mutual Funds because they want to build reputation|
|3. Are financial leaders also sustainable leaders? |Answer:| 
|4. Which Inv. Funds combine the best financial and ESG score |__MVP__ [Summary capstone last year](https://github.com/neuefische/daily-protocol-cgn-da-23-2/blob/main/Module%205%20-%20EDA%20Visualization/protocol_day17_10may23.md)| 
|5. Does the financial rating coincide with the ESG rating? |Answer:| 
|6. Is there any ESG score clustering |Per size, per investment strategy, per investment type, per dividend| 
|7. What are the determinants of ESG score | Regression analysis| 

## Task Steps


1. Define Financial Performance KPI 

2. Define a Composite KPI for ESG performance 

4. a. Clean our data (e.g. specify which columns you want to keep, rename columns etc.)  
   b. Reduce our dataframe 
   
   c. Make an EDA on the data we have downloaded and explain any unexpected findings.   
   d. Connect to the database 
    
## Deliverables
1. Clean and structured .ipynb notebook containing the (well-documented) code of data cleaning. 
2. Visualizations
3. Tableau Filter tool and Dashboard __MVP__

##  __Columns to be used__
<span style="color:grey">

|New Dataframe| Columns|
|---|---|
|MF age |1. inception date|
|MF size |2. total_net_assets, 3. asset_convertible,  4. category, 5. Timezone|
|MF strategies | 5. investment strategies, 6.initial_investment, 7. investment types  |
|Reputation- Rating|8. morningstar_risk_rating|
|Returns|9.Price_earnings_ratio, 10. dividends, 11. year_to_date_return, 12. Time ( to better define)|
|Sustainability| 13. ESG scores (to better define)|
