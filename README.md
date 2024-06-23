

# Data Analytic Project : Asset Allocation in High Uncertainty of Covid19 and Monetary Policy (2020 -2022).

## Introduction

This data project in which I apply a data analytic process from Google Data Analytic Course. This project will enhance me in finding insight from data to answer business questions related to portfolio management.

## Scenario

Asset Management Company have a variety of funds which combine many classes of assets. By the end year of 2020, where the Covid19 pandemic is still an intense situation. Global economic slowdown and asset prices around the world are volatile. Portfolio managers discuss with the team about Covid19 impact on the market and do data analysis to assess asset performance and asset risk during Covid19 pandemic to mitigate portfolio risk and find investment opportunities to optimize portfolio return when covid pandemic seem relief.

## Purposes

-Analyze asset performance and asset volatility to allocate assets to mitigate risk.

-Analyze economic indicators and Covid19 pandemic situations to find investment opportunities and allocate assets to maximize portfolio return.

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

Asset Performance: Covid19 began in December 2019 and spread out around the world. After 3 months the virus is still hard to control, Investors panic and are sensitive to fast Covid pandemics and bring volatility to market. Equity’s YTD dropped from 45.91% to 24.99%,Gold’s YTD keeps higher near to equity’s YTD. While real estate’s YTD decreased from 16.21% to -10.83% and was lower than bond’s YTD.

At the end of 2020, equity’s YTD increased to 64.17% and outperformed other asset classes. Equity's annual return increased 18.22%.Gold ‘s annual return increased 23.61% and beat equity’s annual return in 2020. It shows gold is a safe-haven asset for investors during hard situations. Real estate ’s YTD increased to 9.74% back from a large drop in March 2020 but overall real estate’s annual return dropped 5.25% in 2020.


Figure1: Yield to Date of Each Asset During 2015-2020.


![YTD 2015_2020(2)](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/c53ea192-11e8-4a24-8d05-47295b115878)

Figure2: Annual Return in Each Asset During 2015-2020.

![Asset_Return_2015_2020(3)](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/0778cb1c-ed1e-4c79-9389-68a87222fc2e)


Asset Volatility: Equity and real estate tend to have higher volatility in 2019-2020. From figure 3, equity volatility increased from 1.491% to 2.040% and real estate volatility increased from 1.969% to 2.496% which has the highest volatility compared to other assets in 2020. While gold volatility is higher by little from 1.789% to 1.871% in 2020 compared to previous year.

Figure3: Average Variance for Asset Class During 2015-2020.

![Asset_Variance_2015_2020(3)](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/380dc62c-a88e-46dd-8627-f8f7d655e215)


Portfolio Return and Volatility: Portfolio cumulative return large drop in March 2020 from 26.12% to 17.53% as market panic about Covid19 spread brings large drop of equity which portfolio holds around 40 percent. However, 2 months later the portfolio rebounded to the same level and increased to 36.76%. Portfolio variance increased since March 2020 from 3.58% and moved to 4.53% in December 2020. It shows portfolios tend to volatile more in next year and need to reduce portfolio risk as the number of Covid new cases still increase.




Figure4: The Cumulative Return of Portfolio in 2015-2020.

![Cumulative Portfolio Return 2015_2020(2)](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/972210b4-085b-475e-b56e-83bb021cbb9b)

Figure5: Portfolio Variance in 2015-2020

![Port_Variance_2015_2020(2)](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/307958d2-0e0c-4ee4-b2c0-9f1dc88258dd)

Figure6: The Number of Covid19 New Cases in 2020.

![Covid 2020](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/6e75dca3-7383-49f9-9f4c-c3b4f46d392a)

### How to allocate assets in a portfolio to mitigate risk ? (Assume portfolio manager doing data analytic in the end year of 2020 and at the beginning portfolio combines with equity 40%, bond 40%, gold 10%, and real estate 10%.)



Asset Allocation: Underweight high volatility asset during Covid19 pandemic. From the volatility data, real estate volatility increased from 1.969% to 2.496% and equity volatility increased from 1.491% to 2.040%.  and overall portfolio volatility increased to 4.531% in December 2020, so equity and real estate should be underweighted to mitigate portfolio risk during Covid new cases growing. 


Figure7: Percentage of Asset in Portfolio Before and After Allocate Asset in 2020.

![Asset Allocation(2)](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/59174945-d9d1-4eeb-b6bf-d66c4c55a408)


### What asset will be an investment opportunity to allocate based on your data ? (Assume that portfolio manager doing data analytic again at the first half of 2022)


Market View: Covid pandemic was relieved in the first quarter of 2022 after the number of covid new cases went to the peak in January 2022 (figure8). Economic recovery from shutdown, inflation increased to 9% in June 2022 and the Federal Reserve Bank decided to increase interest rates from March 2022 and hike rates again by large and fast from 0.33% to 1.58% in June 2022 (figure9).

Figure8: The Number of Covid19 in 2020- 1H2022.

![Covid 2020_1H2022](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/1b5907a0-af98-46d3-92fb-ad14dbc82a7a)

Figure9: The Federal Interest Rate Policy and Consumer Price Index in 2015- 1H2022.

![FED_CPI](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/0ea2ba8e-8777-4eb9-a16f-c23d9895d606)



Asset Allocation: 

Changing of interest rate large and fast pressure on many assets. For equity, companies will run businesses with higher financing costs. Bond market will get price pressure when the interest rate is higher. Higher opportunity cost of gold investors as holding gold cannot get interest or dividend. Lower home purchasing power will put pressure on demand in the real estate market. Based on the business cycle, we are on the stage of full expansion in the first half of 2022. Under high inflation and hawkish interest rate policy (figure 9), although business will get higher financing costs, at the same time the growth of demand and productivity will be a positive factor for business growth at this stage. So equity should be overweight on the portfolio and we underweight on bonds as interest rate has a high effect on bond price directly. Neutral for gold as gold is a good asset for long-term hedge against inflation, but underweight for real estate as growth of the real estate sector was pressured by lower house demand from higher home financing cost.


### Summary
	
- Portfolio volatility has higher volatility in 2020 coming from equity and real estate volatility and tends to have more volatility as the number of covid19 still increases.

- By the end of 2020, reducing the portion of high volatility assets is the way to mitigate portfolio risk.So recommend to underweight equity and real estate.

- In the first half of 2022, High inflation is  concerning. After the Covid19 relief, the federal reserve bank started to hike rates. This occurs in the full expansion stage of the business cycle. Equity will be a good opportunity as the demand and productivity is growing. So overweight for equity, but underweight for bond and real estate as higher interest rates large and fast will put pressure on both. Gold is a good asset to hedge inflation, it is neutral as we hold it with large amounts.




### Step5: Share


Create a dashboard in Tableau to present asset allocation by considering performance and volatility risk of asset class and portfolio. Moreover,using economic indicators and Covid19 new cases to make investment decisions in order to mitigate risk and optimize return.

![Dashboard](https://github.com/sornsawan25ch/Asset-Performance-Volatility-SQL/assets/166679003/e9985b78-e3a8-4f29-8325-6fffd1d08277)


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

