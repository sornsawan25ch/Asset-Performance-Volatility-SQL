

# Data Analytic Project : Asset Allocation in High Uncertainty of Covid19 and Monetary policy (2020 -2022).

## Introduction

This data project in which I apply a data analytic process from Google Data Analytic Course. This project will enhance me in finding insight from data to answer business questions related to portfolio management.

## Scenario

Asset Management Company have a variety of funds which combine many classes of assets. By the end year of 2020, where the Covid19 pandemic is still an intense situation. Global economic slowdown and asset prices around the world are volatile. Portfolio managers discuss with the team about Covid19 impact on the market and do data analysis to assess asset performance and asset risk during Covid19 pandemic to mitigate portfolio risk and find investment opportunities to optimize portfolio return when covid pandemic seem relief.

## Purposes

-Analyze asset performance and asset volatility to allocate assets to mitigate risk.

-Analyze economic indicators and covid19 pandemic situations to find investment opportunities and allocate assets to optimize portfolio return.

## Data Analytic Process

### Step1: Ask

All asset got impact from high uncertainty during Covid19 Pandemic and how portfolio manager will use data to answer following questions:

How has asset risk and performance been since Covid19 Pandemic began?
How to allocate assets in a portfolio to mitigate risk ? (Assume portfolio manager doing data analytic in the end year of 2020 and at the beginning portfolio combines with equity 40%, bond 40%, gold 10%, and real estate 10%.)
What asset will be an investment opportunity to allocate based on your data ? (Assume that portfolio manager doing data analytic again at the first half of 2022)


### Step2: Prepare

This project analyzes asset performance, volatility, and also economic factors to allocate assets in a portfolio. The relevant data is asset price, economic indicators, and covid new cases. 

![DataSource](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/ac7d567e-bdf4-440a-89ac-41f6c4570135)

### Step3: Process

To make data integrity, It’s important to clean and manipulate data before applying it as the correction of data will lead to the reliability result. So I apply the following process in cleaning and manipulating the data in the Structured Query Language Program from Google.

1.Check data format in each dataset 
2.Check data type in each column
3.Check data size
4.Check the completion in all rows and manage NULL rows.
5.Combine relevant data into one table.       

### Step4: Analyze

### How has asset risk and performance been since Covid19 Pandemic began?

Asset Performance: Equity’s YTD dropped at the beginning of Covid19 pandemic but it still outperforms other asset classes at the end of 2020 also equity’s annual return is still positive in 2020.Gold beat equity’s annual return since Covid19 pandemic in 2020. It shows gold is a safe-haven asset for investors during hard situations. While real estate ’s YTD decrease lower than bonds since real estate’s annual return is large drop and turn to negative in 2020.

 ![YTD 2015_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/d64da150-dee1-43cb-b1cd-359f3b412f1e)


 ![Asset_Return_2015_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/badde1b1-4aed-4cc1-b9cc-96956e9773cf)


![Asset_Return_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/a2357079-67e6-434b-98c4-2a28a6b0578c)


Asset Volatility: Equity and real estate tend to have higher volatility in 2019-2020. Especially real estate, which will have the highest volatility in 2020. While gold volatility is higher by little in 2020 compared to previous year.

![Asset_Variance_2015_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/b4ef9d50-3ae7-4a94-a526-7970b1f3d6e9)


![Asset_Variance_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/9158942c-7be3-40ce-b965-ff33bb07a000)



Portfolio Return and Volatility: Portfolio cumulative return large drop in March 2020 as market panic about Covid19 spread brings large drop of equity which portfolio holds around 40 percent. However, 2 months later the portfolio rebounded to the same level and increased higher. Portfolio variance increased since March 2020 and moved higher than highest variance of 2015 in November 2020. It shows portfolios tend to volatile more in next year and need to reduce portfolio risk.

![Covid 2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/6e75dca3-7383-49f9-9f4c-c3b4f46d392a)


![Cumulative Portfolio Return 2015_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/05b5ccb2-8a7d-49d4-9328-b1d07c86aae7)


![Port_Variance_2015_2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/76903d05-4260-4936-8d20-8bab081f17ff)



### How to allocate assets in a portfolio to mitigate risk ? (Assume portfolio manager doing data analytic in the end year of 2020 and at the beginning portfolio combines with equity 40%, bond 40%, gold 10%, and real estate 10%.)




Asset Allocation: Underweight high volatility asset during Covid19 pandemic. From the volatility data, real estate and equity volatility increase and overall portfolio volatility  increase and more than highest volatility of 2015 since November 2020, so equity and real estate should be underweighted to mitigate portfolio risk during Covid new cases growing and tend to increase more in the future. 

![Asset Allocation2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/4ee621b7-7054-4e9b-a145-ccfa14b45b32)


### What asset will be an investment opportunity to allocate based on your data ? (Assume that portfolio manager doing data analytic again at the first half of 2022)


Market View: Covid pandemic was relieved in the first quarter of 2022 after the number of covid new cases went to the peak in January 2022. Economic recovery from shutdown and high inflation make the Federal Reserve Bank start to increase interest rates from March,3th 2022 and hike rates again by large and fast from 0.33% to 1.88% in June 2022.

![Covid 2020_1H2022](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/1b5907a0-af98-46d3-92fb-ad14dbc82a7a)


![FED_CPI](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/0ea2ba8e-8777-4eb9-a16f-c23d9895d606)



Asset Allocation: 

Changing of interest rate large and fast pressure on many assets. For equity, companies will run businesses with higher financing costs. Bond market will get price pressure when the interest rate is higher. Higher opportunity cost of gold investors as holding gold cannot get interest or dividend. Lower home purchasing power will put pressure on demand in the real estate market. Based on the business cycle, we are on the stage of full expansion in the first half of 2022. Under high inflation and hawkish interest rate policy, although business will get higher financing costs, at the same time the growth of demand and productivity will be a positive factor for business growth at this stage. So equity should be overweight on the portfolio and we underweight on bonds as interest rate has a high effect on bond price directly. Neutral for gold as gold is a good asset for long-term hedge against inflation, but underweight for real estate as growth of the real estate sector was pressured by lower house demand  because of the higher home financing cost.



### Step5: Share


Create a dashboard in Tableau to present asset allocation by considering performance and volatility risk of asset class and portfolio. Moreover,using economic indicators and Covid19 new cases to make investment decisions in order to mitigate risk and optimize return.


### Appendix

### Business Cycle

![Economic Cycle](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/a2fa3c11-14b1-4592-a4db-2f64750bab46)

Source : StockCharts.com

Stage1 : The economy weakens and the central bank loose monetary policy by cutting interest rates.

Stage2 : The economy moves to the bottom.

Stage3 : The economy improves and tries to move into an expansion phase.

Stage4 : In the full expansion period. The expansion increased inflation pressure and the Central bank started to increase the interest rate.

Stage5 : In a peak of economic growth.The economy grows at a slower pace because of rising interest rates.

Stage6 : Economic cycle prepares to move from an expansion phase to a contraction phase.

