# Gender Inequality Index - Data package

This data package contains the data that powers the chart ["Gender Inequality Index"](https://ourworldindata.org/grapher/gender-inequality-index-from-the-human-development-report?tab=line&country=USA~CHN~BRA~URY~CHL~JPN~PRT~ESP~MEX~KOR~ZAF~ARG~RUS~IND~DEU&overlay=download-data&v=1&csvType=filtered&useColumnShortNames=false) on the Our World in Data website. It was downloaded on September 12, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:
country: USA, CHN, BRA, URY, CHL, JPN, PRT, ESP, MEX, KOR, ZAF, ARG, RUS, IND, DEU
tab: line
overlay: download-data

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Gender Inequality Index
This index captures gender-based disadvantage in reproductive health, empowerment and the labour market; ranges from 0 (full equality) to 1 (maximum inequality), representing the share of potential human development lost because of gender gaps.
Last updated: May 7, 2025  
Next update: May 2026  
Date range: 1990–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
UNDP, Human Development Report (2025) – with minor processing by Our World in Data

#### Full citation
UNDP, Human Development Report (2025) – with minor processing by Our World in Data. “Gender Inequality Index – UNDP” [dataset]. UNDP, Human Development Report, “Human Development Report” [original data].
Source: UNDP, Human Development Report (2025) – with minor processing by Our World In Data

### What you should know about this data
* The Gender Inequality Index (GII) reflects gender-based disadvantage in three dimensions— reproductive health, empowerment and the labour market—for as many countries as data of reasonable quality allow. It shows the loss in potential human development due to inequality between female and male achievements in these dimensions.
* It ranges from 0, where women and men fare equally, to 1, where one gender fares as poorly as possible in all measured dimensions.
* The GII highlights how unequal opportunities for women and men translate into foregone national human‑development potential.
* It combines five indicators: maternal mortality ratio, adolescent birth rate, women’s parliamentary seats, secondary‑education attainment, and labour‑force participation (all sex‑disaggregated).
* Data is originally sourced from WHO/UNICEF/UNFPA/World Bank, UNDESA, IPU, UNESCO UIS, Barro-Lee, DHS/MICS and ILO datasets.

### Source

#### UNDP, Human Development Report – Human Development Report
Retrieved on: 2025-05-07  
Retrieved from: https://hdr.undp.org/  

#### Notes on our processing step for this indicator
We calculated averages over continents and income groups by taking the population-weighted average of the countries in each group. If less than 80% of countries in an area report data for a given year, we do not calculate the average for that area.


    