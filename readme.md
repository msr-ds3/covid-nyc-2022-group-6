Project preview 

Based on the article [Differential COVID-19 case positivity in New York City neighborhoods: Socioeconomic factors and mobility](https://onlinelibrary.wiley.com/doi/epdf/10.1111/irv.12816) by Mathhew R. Lamb, Sasikiran Kandula and Jeffrey Shaman  the replication of Figure 1, Figure 2, Table 1 (April 01, 2020) & Table 2 (April 01, 2020) was performed. The article highlights important socio-economic factors and mobility that affected the COVID -19 case positivity.

Figure 1 depicts the maps of six explanatory variables used in the study as measured of SES characteristics of ZIP codes. The ZIP code-level characteristics used in the study were taken from the US Census and the American Community Survey 2016 (ACS). Six variables included proportion of 18-64 year olds who are uninsured, median income(in million, 2016$), proportion self-identifying as White, proportion of households of 4 or more, proportion of population that commutes by bus and proportion of population 65+ years of age. Same went for Table 1 except for the population that commutes by bus and the population 65+ years of age. 

Figure 2 depicts the proportional change in mobility over time by Zip Code. The mobility status was obtained from SafeGraph which facilitates in providing the location of desired point of interest and the number of daily visits to each POI as tracked by mobile phone. 

Replication breakdown 

We aimed to replicate the data and generate the figures as in the article. The breakdown is as follows: 
1. "tidycensus" package is loaded in the replicated code file. However, the user should signup [here](https://api.census.gov/data/key_signup.) to have the API key in order to get the ACS data. 

2. The reproducible file can be found [here](https://github.com/msr-ds3/covid-nyc-2022-group-6/blob/main/replication.Rmd). 



