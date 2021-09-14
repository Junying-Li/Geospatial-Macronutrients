# cs573-final-project

## Data API

Data is sorted by year in ascending order, then by country in ascending order

`/api/v1/data`

### Query params:

#### Specify a year range

`year_from=1970` - get data with year greater than or equal to

`year_to=1970` - get data with year less than or equal to

#### Specify a specific year

`year=1970` - get data by year **Note: Overrides `year_from` and `year_to`**

#### Specify a country

`entity=Albania` - get data for Albania

### Examples

Get data for the United Kingdom from 2011-2012

`/api/v1/data?entity=United%20Kingdom&year_from=2011&year_to=2012`

Get data for all countries for the year 1968

`/api/v1/data?year=1968`