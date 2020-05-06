# Capstone1

Data Sources:

European Centre for Disease Prevention and Control; daily global geographic distribution of covid-19: https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide

Wikipedia compilation containing lockdown information by country/region with lockdown start/end times: https://en.wikipedia.org/wiki/Template:COVID-19_pandemic_lockdowns

Annals of Internal Medicine; Incubation period of SARS-CoV-2: https://annals.org/aim/fullarticle/2762808/incubation-period-coronavirus-disease-2019-covid-19-from-publicly-reported


Proposal:

The rapid spread of SARS-CoV-2 has forced many countries into lockdown. To see how necessary locksdowns are to the cointainment of a pandemic we can use two different tests to see if there is a correlation between implementing lockdowns and average rate of death by the virus. Countries who have locked down can be compared against countries who haven't to see if implementing a lockdown actually has a statistically significant correlation with death rate. A sub hypothesis can also be run comparing the rate of death before and after going into lockdown pertaining to the countries that quarentined or social distanced in any way (factoring in the incubation period to know when the effects of the lockdown procedures would be felt). If the average death rates are normally distributed, each hypothesis can run their respective ttests. Ttest_ind would be used in the case where we compare strictly the countries who isolated vsvstrictly the countries who didnt. The sub hypothesis would use ttest_rel to compare the effects of isolation within the same sample groups. The rate of death before isolation would be compared to the rate of death after isolation in that instance.

The hypothesis: lockdowns statistically significantly decrease the average rate of death of countries affected by Covid-19. Therefore, the null hypothesis is that there is no significant relationship in the implementation of a lockdown on the average death rate of those countries.

This research would be most insightful for any governing body in deciding which precautions should be considered when combating a pandemic (or at least mitigating the casualties in the situation). If there is indeed a statistically significant relationship between implementing any form of lockdown, it can be assumed continuing or enforcing stricter lockdowns would further contain the spread of the virus and continue to decrease the average death rate in countries afflicted by Covid-19.
