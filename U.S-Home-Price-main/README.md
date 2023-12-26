# U.S-Home-Price

# Research on factors responsible for effect in Home Prices in US

Task - Using publically available data for the national factors that impact supply and demand of homes in US, build a model to study the effect of these variables on home prices.

Data_set_Approch - the following data chose for research

Unemployment Rate
Per Capita GDP
Median Household Income
Construction Prices
CPI
Interest Rates
Number of new houses supplied
Working Population
Urban Population
Percentage of population above 65
Housing subsidies
Number of Households
As a proxy to the home prices, S&P CASE-SHILLER Index is used.

Most of the data is downloaded from [https://fred.stlouisfed.org/].

Data for all the variables is downloaded, preprocessed and combined to create a datset. Data for different variables had different frequencies. So, to combine the data, necessary interpolations are made.

    Following sources were used to gather data -
CASE-SCHILLER Home Price Index - https://fred.stlouisfed.org/series/CSUSHPISA

Interest rates - https://fred.stlouisfed.org/series/FEDFUNDS

Unemployment rate - https://fred.stlouisfed.org/series/UNRATE

Income - https://fred.stlouisfed.org/series/DSPIC96

Per Capita GDP - https://fred.stlouisfed.org/series/A939RX0Q048SBEA

New Constructed units - https://fred.stlouisfed.org/series/COMPUTSA

Construction price index - https://fred.stlouisfed.org/series/WPUSI012011

percent urban population - https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS?end=2021&locations=US&start=2001

Housing Subsidies (Federal) - https://fred.stlouisfed.org/series/L312051A027NBEA

Total households - https://fred.stlouisfed.org/series/TTLHH


