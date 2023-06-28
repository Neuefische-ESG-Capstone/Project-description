# Project-description
# ESG_ Sustainable Finance Capstone project

In this project, we plan to combine our Python, SQL, and Tableau skills and use them in combination with each other.  

## Objective

We are a Data Analyst team in Europe and our clients are considering expanding their investments in to Mutual Funds in the United States. A mutual fund is a financial vehicle that pools assets from shareholders to invest in securities like stocks, bonds, money market instruments, and other assets

However, our customers want to expand their investments while maintaining their values and the sustainability standards set out in Europe. They want to make investments with returns that are not only adjusted to financial risk but also take into account environmental, social, and governance dimensions. 

Our consulting firm has a data set of all Mutual Funds in the USA with all the characteristics, returns, and sustainability scores. We are responsible to help our clients to select X top Mutual Funds taking into account their different investor profiles and combining two factors: financial performance and ESG dimensions. 


We will answer the following questions : 
What are the investment options that can yield maximum financial returns while also aligning with our client's values and commitment to sustainability?
Are financial leaders also sustainability leaders? As a deliverable, we aim to examine the financial performance and ESG scores of various mutual funds. Our goal is to investigate whether there are discernible patterns in ESG scores based on factors such as fund size, investment strategy, investment type, and dividend distribution.

## __Research Questions__ 
|Questions|Hypothesis|
|---|---|
|1. Which Inv. Funds are leaders in financial performance on average? | X strategy, X type, large and established Mutual Funds because of experience/good track record |
|2. Which Inv. Funds are leaders in ESG performance on average ?|Smaller and newer Mutual Funds because they want to build good reputation|
|3. Which Inv. Funds combine the best financial and ESG score |__MVP__ [Summary capstone last year](https://github.com/neuefische/daily-protocol-cgn-da-23-2/blob/main/Module%205%20-%20EDA%20Visualization/protocol_day17_10may23.md)| 
|4. We will make the assumption that the financial rating coincides with the ESG rating?  
|5. What are the determinants of ESG score | Regression analysis| 

## Task Steps


1. Define Financial Performance KPIs 

2. Define a composite KPI for ESG performance 

4. a. Clean our data (e.g. specify which columns you want to keep, rename columns etc.)  
   b. Reduce our dataframe
   c. Make an EDA on the data we have downloaded and explain any unexpected findings.   
   d. Connect to the database 
    
## Deliverables
1. Clean and structured .ipynb notebook containing a (well-documented) code of data cleaning. 
2. Visualizations
3. Tableau Filter tool and Dashboard __MVP__

##  __Columns to be used__
<span style="color:grey">

|New Dataframe| Columns|
|---|---|
|MF age |inception date|
|MF size |total_net_assets, size_type|
|MF strategies |investment_type|
|Reputation- Rating|morningstar_overall_rating|
|Returns|fund_return_10years, year_to_date_return|
|Sustainability|esg_score, environment_score |
