# Inequality-adjusted Human Development Index - Data package

This data package contains the data that powers the chart ["Inequality-adjusted Human Development Index"](https://ourworldindata.org/grapher/inequality-adjusted-human-development-index?tab=line&time=earliest..2023&country=BRA~CHN~IND~RUS~KOR~ZAF~USA~DEU~JPN~PRT~ESP~CHL~ARG~URY~MEX&mapSelect=BRA~CHN~IND~RUS~KOR~ZAF~USA~DEU~JPN~PRT~ESP~CHL~ARG~URY~MEX&overlay=download-data&v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Inequality-adjusted Human Development Index
The Inequality-adjusted Human Development Index (IHDI) is a summary measure of key dimensions of human development: a long and healthy life, a good education, and a decent standard of living, adjusted for inequalities in these dimensions. Higher values indicate higher and more equal human development.
Last updated: May 7, 2025  
Next update: May 2026  
Date range: 2010–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
UNDP, Human Development Report (2025) – with minor processing by Our World in Data

#### Full citation
UNDP, Human Development Report (2025) – with minor processing by Our World in Data. “Inequality-adjusted Human Development Index – UNDP” [dataset]. UNDP, Human Development Report, “Human Development Report” [original data].
Source: UNDP, Human Development Report (2025) – with minor processing by Our World In Data

### What you should know about this data
* The Inequality-adjusted Human Development Index (IHDI) adjusts the Human Development Index (HDI) for inequality in the distribution of each dimension across the population.
* It is based on a distribution-sensitive class of composite indices proposed by Foster, Lopez-Calva and Szekely (2005), which draws on the Atkinson (1970) family of inequality measures. It is computed as a geometric mean of inequality-adjusted dimensional indices.
* The IHDI accounts for inequalities in HDI dimensions by "discounting" each dimension's average value according to its level of inequality. The IHDI value equals the HDI value when there is no inequality across people but falls below the HDI value as inequality rises. In this sense the IHDI measures the level of human development when inequality is accounted for.
* Data is originally sourced from UNDESA complete life tables (health), harmonised household-survey micro-datasets (education) and the UNU-WIDER WIID (income).

### Source

#### UNDP, Human Development Report – Human Development Report
Retrieved on: 2025-05-07  
Retrieved from: https://hdr.undp.org/  

#### Notes on our processing step for this indicator
We calculated averages over continents and income groups by taking the population-weighted average of the countries in each group. If less than 80% of countries in an area report data for a given year, we do not calculate the average for that area.


## World regions according to OWID
Regions defined by Our World in Data, which are used in OWID charts and maps.
Last updated: January 1, 2023  
Date range: 2023–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Our World in Data – processed by Our World in Data

#### Full citation
Our World in Data – processed by Our World in Data. “World regions according to OWID” [dataset]. Our World in Data, “Regions” [original data].
Source: Our World in Data

### Source

#### Our World in Data – Regions


    