# Annual change in primary energy consumption - Data package

This data package contains the data that powers the chart ["Annual change in primary energy consumption"](https://ourworldindata.org/grapher/change-energy-consumption?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on February 09, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

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


## Annual change in primary energy consumption
Last updated: June 20, 2024  
Next update: June 2025  
Date range: 1966–2023  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
U.S. Energy Information Administration (2023); Energy Institute - Statistical Review of World Energy (2024) – with major processing by Our World in Data

#### Full citation
U.S. Energy Information Administration (2023); Energy Institute - Statistical Review of World Energy (2024) – with major processing by Our World in Data. “Annual change in primary energy consumption” [dataset]. U.S. Energy Information Administration, “International Energy Data”; Energy Institute, “Statistical Review of World Energy” [original data].
Source: U.S. Energy Information Administration (2023), Energy Institute - Statistical Review of World Energy (2024) – with major processing by Our World In Data

### What you should know about this data

### Sources

#### U.S. Energy Information Administration – International Energy Data
Retrieved on: 2023-12-12  
Retrieved from: https://www.eia.gov/opendata/bulkfiles.php  

#### Energy Institute – Statistical Review of World Energy
Retrieved on: 2024-06-20  
Retrieved from: https://www.energyinst.org/statistical-review/  

#### Notes on our processing step for this indicator
- Primary energy consumption data was compiled based on two key data sources: [Energy Institute (EI) Statistical Review of World Energy](https://www.energyinst.org/statistical-review), and [International energy data from the U.S. Energy Information Administration (EIA)](https://www.eia.gov/international/data/world/total-energy/more-total-energy-data). EI provides the longest and most up-to-date time-series of primary energy. However, it does not provide data for all countries. We have therefore supplemented this dataset with energy data from the EIA. Where EI provides data for a given country, this data is adopted; for countries where this data is missing, we rely on EIA energy figures.
- Per capita figures have been calculated using a population dataset that is based on [different sources](https://ourworldindata.org/population-sources).
- To calculate energy per unit of GDP, we divide by total real GDP figures from [the Maddison Project Database](https://ourworldindata.org/grapher/gdp-maddison-project-database).



    