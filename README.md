# Bayesian Models of Residential Rooftop Solar Adoption in MA

Code written for CAS EE 509: Environmental Statistics, Boston University spring 2022.

## Background

This analysis attempts to determine the factors that most affect residential rooftop solar adoption in municipalities of Massachusetts. Factors include: 2020 voting pattern, income, education level, and time.

## Data

- Existing PV installations in MA, provided by the [Massachusetts Clean Energy Center](https://www.masscec.com/public-records-requests), which includes all solar PV systems fully registered in the Production Tracking System (PTS), current as of May 2021: “PV in PTS Public Records Request.” Massachusetts Clean Energy Center, May 2021. https://www.masscec.com/public-records-requests.

- Boundaries of MA by town and zipcode, provided by [MassGIS](https://www.mass.gov/info-details/massgis-data-zip-codes-5-digit-from-here-navteq). From these, I extracted the zipcodes included in the study locations: MassGIS (Bureau of Geographic Information), Commonwealth of Massachusetts EOTSS, accessed 12/09/2021.

- Household income data by MA block group (2015-2019), provided by [NHGIS](https://data2.nhgis.org/): Steven Manson, Jonathan Schroeder, David Van Riper, Tracy Kugler, and Steven Ruggles. IPUMS National Historical Geographic Information System: Version 16.0 [dataset]. Minneapolis, MN: IPUMS. 2021. http://doi.org/10.18128/D050.V16.0.

- Education in MA by block group, provided by [NHGIS](https://data2.nhgis.org/): Steven Manson, Jonathan Schroeder, David Van Riper, Tracy Kugler, and Steven Ruggles. IPUMS National Historical Geographic Information System: Version 16.0 [dataset]. Minneapolis, MN: IPUMS. 2021. http://doi.org/10.18128/D050.V16.0.

- Town voting data: William Smith. Map: See How Your Town or City Voted in the 2020 Election. November 3, 2020. WBUR. https://www.wbur.org/news/2020/11/03/2020-massachusetts-election-map.

## Other Sources

- “Massachusetts: State Profile and Energy Estimates.” US Energy Information Administration (EIA), US EIA, https://www.eia.gov/state/?sid=MA.

- Pew Research Center, April, 2015, “A Deep Dive Into Party Affiliation.”

- U.S. Census Bureau, A Compass for Understanding and Using American Community Survey Data: What Researchers Need to Know U.S. Government Printing Office, Washington, DC, 2009.

- Vilallonga, Lucia. “Policy Analysis of Rooftop Solar Incentives in MA.” GitHub, 31 Jan. 2022, https://github.com/ghostpress/ma-solar.

## Use Instructions

To replicate this project on your local machie with anaconda, enter the following command in a terminal window:

`conda create --name myenv --file requirements.txt`

Where `myenv` is the name of your local environment. Then clone this repository to edit and run the code.
