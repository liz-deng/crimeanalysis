
# Seattle Crime Analysis - 2008 to 2023


# Authors
- Elizabeth (Liz) Deng

# Date
February 18, 2023

# Abstract
This oroject takes crime data from the City of Seattle dating from 2008 to present and analyzes trends in different crime types and neighborhoods.

# Keywords
- Seattle
- Policing
- Crime
- Community Safety.

# Introduction
According to King5 news, 2022 and the previous few years demonstrated a considerable growth in both violent and property crimes. For example, shootings in Seattle have spiked:
> “Police said shootings and shots fired reached an all-time in 2022. The previous high was 2021, followed by 2020, indicating a three-year trend in which shootings have increased.”
[(Ramirez 2023)](https://www.king5.com/article/news/crime/seattle-2022-crime-report/281-61f06cb3-9d2b-4183-a6d8-476bf6b50963)

Additionally, overall crime in the city has increased.
> "As a whole, the violent crime rate for the City of Seattle increased to 736 per 100,000 in 2022, with property crime rates increasing slightly in 2022." (Ramirez 2023)

The goal of this data analysis is to identify possible trends in different crime categories over time, as well as to map frequencies of different crimes in each of Seattle's "beats".

# Problem Domain
## I. Values Addressed
One of the core values the project aims to investigate is the delicate balance of maintaining public safety and overpolicing. By delving deeper into the data and investigating the real-world effects of certain societal changes (such as the pandemic and declining police force size), we may be able to identify specific weaknesses and provide support to the city without developing a culture that values overpolicing and more undertrained police, as both have demonstrated to have negative effects on communities in the long-term.
>"...larger police forces make more arrests for low-level “quality-of-life” offenses, with effects that imply a disproportionate burden for Black Americans. Notably, cities with large Black populations do not share equally in the benefits of investments in police manpower"
[(Chalfin et. al 2020)](https://www.nber.org/papers/w28202?utm_source=npr_newsletter&utm_medium=email&utm_content=20210419&utm_term=5326149&utm_campaign=money&utm_id=49355949&orgid=&utm_att1=money)

## II. Potential Harms & Benefits
Investigating crime patterns would allow city government to determine which areas and factors of crime prevention need the most support. We would be able to ask and answer questions like "Do we need an overall increase in police force? Or would reassigning our existing force to cover certain areas more be of greater benefit?"

Additionally, the project would aid in bringing awareness to the safety needs of certain Seattle neighborhoods, and potentially foster a greater sense of community amongst Seattle residents.

# Research Questions
1. How does total crime for different offense types change by time of day and month of year? Is there any seasonality for any offense or offense parent category?
For this question specifically, I would like to focus on two domains.
  * How does the rate of domestic violence across the city correlate with certain events, such as sports games or major news events?
  * What is the relationship between the COVID-19 pandemic and the rate of violent crime?
2. What unique statistics and patterns were you able to identify in Seattle’s crime?
  * This question is important because in any data project, it is crucial to set aside preconceived notions about the things that the data represents; for this project, the goal is to generate a statistically accurate picture of Seattle and its crime, regardless of the image of Seattle that we may already have.
3. What are the geographic hotspots for different types of offense and offense parents category? What patterns do you notice?
  * We can use the answers to this question to create a geographical image of the city's crime and identify how location, culture, and community may play a role in crime rates.

# The Datasets


| Name of Data File                                      | Number of Observations (Rows) | Number of Variables (Columns) |
|--------------------------------------------------------|-------------------------------|-------------------------------|
|Seattle Police Department (SPD) Crime Data 2008-present | 1033416                       | 17                            |
|SPD Call for Service Data| 1048576                      | 11                            | 11                            |


Open Data, Seattle. “Call Data.” data.seattle.gov, 18 Feb. 2023, [Call Data](https://data.seattle.gov/Public-Safety/Call-Data/33kz-ixgy)

SPD Crime Data provided by DubsTech.

# Expected Implications
Lorem ipsum blahblah Lorem ipsum blahblah Lorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblah

# Limitations
Lorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblahLorem ipsum blahblah

# References
Chalfin, A., Hansen, B., Weisburst, E. K., & Williams, M. C. (2020).*Police Force Size and Civilian Race.* National Bureau of Economic Research. https://www.nber.org/papers/w28202?utm_source=npr_newsletter&utm_medium=email&utm_content=20210419&utm_term=5326149&utm_campaign=money&utm_id=49355949&orgid=&utm_att1=money

Ramirez, Q. (2023, February 1). Seattle 2022 crime report: Violent crime, homicides and shootings increased. King5.Com. https://www.king5.com/article/news/crime/seattle-2022-crime-report/281-61f06cb3-9d2b-4183-a6d8-476bf6b50963

