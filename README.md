# HK property situation

This repository is intended to extract the historical domestic property data.
<br>Here is the description of the files in this depository:

1. data_cleaning.ipynb
> It download the historical domestic property data from the government website which mainly from [Rating and Valuation Department](https://www.rvd.gov.hk/en/publications/property_market_statistics.html), and adding the latitude and longitude of the estate location with few of it are manual found written in ***estate_with_coordinates.csv*** since they can't be found with Nominatim package

2. HOS_2nd_market_web_scrapping.ipynb
> Since without the proper csv file in the website, this python script extract the transaction records of HOS Secondary Market from the wesbite of [Housing Department](https://www.housingauthority.gov.hk/en/home-ownership/hos-secondary-market/transaction-records/index.html), ranged from 2020 to 2025
