
# Datasets

## `countries-data`

A dataset with information about countries extracted from the United Nations
E-Government Survey.

* Source: https://publicadministration.un.org/egovkb/en-us/
* Example: https://publicadministration.un.org/egovkb/en-us/Data/Country-Information/id/136-Portugal
* Income and population features refer to the year 2018.
* Total number of countries: 193.

The following features for each country are included:

* Country Code - as defined by [ISO3166](https://en.wikipedia.org/wiki/ISO_3166) 3 letter code
* Country Name
* Website
* Region
* Sub-Region
* Income
* Income Value
* Population

Available formats:

* CSV: [countries-data.csv](countries-data.csv)
* XLSX: [countries-data.xlsx](countries-data.xlsx)
* Python [Pandas](https://pandas.pydata.org/) DataFrame: [countries-data.pkl](countries-data.pkl) (serialized using [pickle](https://docs.python.org/3.1/library/pickle.html))