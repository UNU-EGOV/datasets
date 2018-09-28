
# Datasets

## World Bank 

### `doing-business`

World Bank data on measures of business regulations and their enforcement, combined into an
overall "ease of doing business" index.

* Source: https://datacatalog.worldbank.org/dataset/doing-business
* Total number of countries: 189 (note: not all the features are available for all countries
  across all years).

The following features for each country are included:

* Country Code - as defined by [ISO3166](https://en.wikipedia.org/wiki/ISO_3166) 3 letter code
* Country Name
* "Ease of doing business index (1=easiest to 185=most difficult)" (indicator: IC.BUS.EASE.XQ)

Available for the following years:

* 2012, 2013, 2014, 2015, 2016, and 2017

An in the Available formats:

* CSV: plain text using comma-separated values
* XLSX: Microsoft Excel Open XML Format 
* Python [Pandas](https://pandas.pydata.org/) DataFrame: serialized using [pickle](https://docs.python.org/3.1/library/pickle.html)
