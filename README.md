# Maternal Mortality Capstone

Aysia Veal
Capstone Project

Maternal Mortality: Analysis of trends and determinants of maternal mortality on a regional/global/country specific scale
Problem Statement:
Given slight reductions in maternal mortality rates, it remains a significant global health challenge. These rates continue to be high in many regions, and disparities persist by geography, socioeconomic factors, race/ethnicity, and age. Understanding the trends, identifying key predictors, and forecasting future risk can help inform policy and targeted interventions to encourage further reductions of the mortality rates of mother. 
Scope: 
•	Global analysis 
or
•	Country specific
Objectives:
•	Descriptive analysis
o	Document the temporal trends of maternal mortality ratio (MMR) (deaths per 100,000 live births) for the selected region(s) (global, country, or U.S. states) over the last X years.
o	Explore differences in maternal mortality by demographic factors (age groups, race/ethnicity, urban vs rural) and by geographic unit (countries, states, regions).
•	Determinants / explanatory modelling
o	Identify key explanatory variables (socio‐economic, health system coverage, maternal age, parity, access to care, geographic/urbanization, etc) that are associated with higher/lower maternal mortality.
o	Build regression or machine‐learning models (e.g., linear regression, random forests, gradient boosting) to assess the relative importance of these predictors and possibly estimate the magnitude of their association with maternal mortality.
•	Forecasting / prediction
o	Develop a predictive model to forecast maternal mortality rates for the next 5–10 years in the selected region(s) under current trends and/or under hypothetical scenarios (e.g., improved access to obstetric care).
o	Use scenario modelling to estimate how changes in key predictors (e.g., increasing skilled birth attendance, reducing adolescent pregnancies) may influence future maternal mortality.
•	Clustering / segmentation
o	Using clustering techniques, segment geographic units (countries or states) into groups based on their maternal mortality profiles and underlying factors, to identify patterns of “high‐risk” vs “improving” regions.
o	Create a data‐driven typology of maternal mortality contexts (e.g., “high MMR & low health system coverage”, “moderate MMR & improving trends”, “low MMR region”), to assist in targeting interventions.
•	Visualization & communication
o	Develop interactive visualizations (maps, trend charts, dashboards) to communicate maternal mortality risks, trends, and predictor impacts to stakeholders or policy-makers.
o	Document insights and policy implications: For example, highlight the most impactful levers for reducing maternal mortality (from the model results), and suggest priority regions/populations for intervention.
Datasets/sources:
•	Maternal mortality ratio (per 100,000 live births)
o	https://www.who.int/data/gho/data/indicators/indicator-details/GHO/maternal-mortality-ratio-(per-100-000-live-births)
o	Can be world or country specific 
o	From 1985-2023
o	Literature about world health statistics
	https://iris.who.int/server/api/core/bitstreams/74b12494-f213-4b5b-9533-18442147e1fb/content
o	Maternal mortality background info
	https://www.who.int/news-room/fact-sheets/detail/maternal-mortality
o	Publication about trends in maternal mortality from 2000-2023
	https://www.who.int/publications/i/item/9789240108462
o	Attributes:
	
•	United States Maternal Mortality Ratio Estimates by Race and Ethnicity 1999-2019 from Global Health Data Exchange
o	https://ghdx.healthdata.org/record/ihme-data/united-states-maternal-mortality-by-state-race-ethnicity-1999-2019
o	Assesses trends in maternal mortality across five racial and ethnic groups. 
o	From 1999-2019
o	Attributes:
	States(all US)
	Race and ethnic groups
•	Hispanic(any race)
•	Non Hispanic
o	American Indian and Alaska native
o	Asian
o	Native Hawaiian or other pacific islander
o	Black
o	white
	Age 10-54
	Years from 1999-2019
	Estimates and ratios for each racial and ethnic group and census region and states.
	3 different CSVs
•	VSSR Provisional Maternal Death Counts and Rates from CDC
o	https://healthdata.gov/CDC/VSRR-Provisional-Maternal-Death-Counts-and-Rates/ehys-jtzp/about_data
o	presents national-level provisional maternal mortality rates based on a current flow of mortality and natality data in the National Vital Statistics System.
	Provisional rates are an early estimate of the number of maternal deaths per 100,000 live births
o	The provisional data include reported 12 month-ending provisional maternal mortality rates overall, by age, and by race and Hispanic origin.
o	Attributes:
	Jurisdiction: US but doesn’t list states
	Year of death
	Month of death
	List live births and maternal mortality rates for each month for: 
•	total
•	Under age 25
•	25-39
•	40 and up
•	Race and Hispanic origin
	Years: 2019-2025 
•	Public use mortality data files from the CDC 
o	Not CSVs but has good charts, data, and visuals from 1968-2023
o	Has age, race/ethnic group
o	https://www.cdc.gov/nchs/maternal-mortality/data.htm
•	Maternal mortality declined by 40 per cent between 2000 and 2023 from Unicef
o	Estimates of country-level lifetime risk (LTR) of maternal death 2000-2023
o	https://data.unicef.org/topic/maternal-health/maternal-mortality/
o	Attributes:
	Target:  By 2030, reduce the global maternal mortality ratio to less than 70 per 100,000 live births
	Years: 2000-2023
	Contains income groups and causes of maternal mortality
	Worldwide, country level and regional level
	No age group or race




<img width="468" height="635" alt="image" src="https://github.com/user-attachments/assets/0fd14a9d-961e-405e-ab8c-2f76a4be7fed" />
