

# Data Analytic Project : Asset Performance & Volatility

## Introduction

Asset performance and asset allocation is a data project in which I apply a data analytic process from Google Data Analytic Course. This project will enhance me in finding insight from data to answer business questions in the financial industry.

## Scenario

Asset Management Company have many funds which combine many classes of assets. By the end year of 2020, where the Covid19 pandemic is still an intense situation. Global economic slowdown and asset prices around the world are volatile. Senior portfolio managers discuss with quantitative analysts about Covid19 impact on the market and ask quantitative analysts to assess asset performance and asset risk during Covid19 to mitigate portfolio risk and find investment opportunities to optimize portfolio return. Quantitative analysts will share their insight to senior portfolio managers in making decisions. Assume that the current portfolio combines with equity 40%, bond 40%, gold 10%, and real estate 10%.

## Purposes

Analyze asset performance and asset volatility to allocate assets to mitigate risk.
Analyze economic indicators and covid19 pandemic situations to find investment opportunities and allocate assets to optimize portfolio return.

## Data Analytic Process

### Step1: Ask

All asset got impact from high uncertainty during Covid19 Pandemic and how quantitative analysts will use data to answer following questions:

How has asset risk and performance since Covid19 Pandemic began?
How to allocate assets in a portfolio to mitigate risk ? (Assume portfolio manager ask to doing data analytic in the end year of 2020)
What asset will be interesting and will be an investment opportunity to allocate based on your data during the circumstance situation ? (Assume that portfolio manager ask to doing data analytic again at the first half of 2022)

### Step2: Prepare

This project analyzes asset performance and asset allocation, Relevant data is asset price, economic indicators, and covid new cases. 

### Step3: Process

To make data integrity, It’s important to clean and manipulate data before applying it as the correction of data will lead to the reliability result. So I apply the following process in cleaning and manipulating the data in the Structured Query Language Program from Google.

1.Check data format in each dataset 
2.Check data type in each column
3.Check data size
4.Check the completion in all rows and manage NULL rows.
5.Combine relevant data into one table.       

### Step4: Analyze

How has asset risk and performance since Covid19 Pandemic began?


Asset Performance: Equity’s YTD dropped at the beginning of Covid19 pandemic but it still outperforms other asset classes at the end of 2020 also equity’s annual return is still positive in 2020.Gold beat equity’s annual return since Covid19 pandemic in 2020. It shows gold is a safe-haven asset for investors during hard situations. While real estate ’s YTD decrease lower than bonds since real estate’s annual return is large drop and turn to negative in 2020.

 





Asset Volatility: Equity and real estate tend to have higher volatility in 2019-2020. Especially real estate, which will have the highest volatility in 2020. While gold volatility is higher by little in 2020 compared to previous year.





Portfolio Return and Volatility: Portfolio cumulative return large drop in March 2020 as market panic about Covid19 spread brings large drop of equity which portfolio holds around 40 percent. However, 2 months later the portfolio rebounded to the same level and increased higher. Portfolio variance increased since March 2020 and moved higher than highest variance of 2015 in November 2020. It shows portfolios tend to volatile more in next year and need to reduce portfolio risk.












How to allocate assets in a portfolio to mitigate risk in the end year of 2020?



Asset Allocation: Underweight high volatility asset during Covid19 pandemic. From the volatility data, real estate and equity volatility increase and overall portfolio volatility strong increase and more than highest volatility of 2015 since November 2020, so equity and real estate should underweight during Covid new cases growing to mitigate risk of portfolio. 




What asset will be interesting and will be an investment opportunity to allocate based on your data during circumstance of  situation ?(Assume that portfolio manager ask to doing data analytic again at the first half of 2022)


Market View: Covid pandemic was relieved in the first quarter of 2022 after the number of covid new cases went to the peak in January 2022. Economic recovery from shutdown and high inflation make the Federal Reserve Bank start to increase interest rates from March,3th 2022 and hike rates again by large and fast from 0.33% to 1.88% in June 2022.





Asset Allocation: 

Changing of interest rate large and fast pressure on many assets. For equity, companies will run businesses with higher financing costs. Bond market will get price pressure when the interest rate is higher. Higher opportunity cost of gold investors as holding gold cannot get interest or dividend. Lower home purchasing power will put pressure on demand in the real estate market. Based on the business cycle, we are on the stage of full expansion in the first half of 2022. Under high interest rate policy, although business will get higher financing costs, at the same time the growth of demand and productivity will be a positive factor for business growth at this stage. So equity should be overweight on the portfolio and we underweight on bonds as interest rate has a high effect on bond price directly. And neutral for gold as gold is a good asset for long-term hedge against inflation and underweight for real estate as growth of the real estate sector was pressured by lower house demand from higher home financing cost.


### Step5: Share


Create a dashboard in Tableau to present asset allocation by considering performance and volatility risk of asset class and portfolio. Moreover,using economic indicators and Covid19 new cases to make investment decisions in order to mitigate risk and optimize return.


