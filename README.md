# weather-gc-ca-python [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/csianglim/weather-gc-ca-python/master)
Jupyter notebooks for scraping Environment Canada weather data

---

This repo demonstrates how to download Environment Canada's weather data using Python with popular data analysis libraries like pandas and Beautiful Soup. Read the accompanying blog post [here](https://www.ubcenvision.com/blog/2017/11/30/jupyter-part1.html) on the [UBC Envision](https://www.ubcenvision.com) website for more details.

# Summary

1. Download CSV weather data from this link: [http://climate.weather.gc.ca/climate_data/bulk_data_e.html?format=csv&stationID=51442&Year=2020&Month=01&timeframe=1](http://climate.weather.gc.ca/climate_data/bulk_data_e.html?format=csv&stationID=51442&Year=2020&Month=01&timeframe=1)

2. Replace `stationID`, `Year` and `Month` with the dataset that you'd like to download.

3. StationIDs can be found here: [http://climate.weather.gc.ca/historical_data/search_historic_data_e.html](http://climate.weather.gc.ca/historical_data/search_historic_data_e.html)

4. This notebook shows you how to download multiple CSV files across different cities by scraping data using BeautifulSoup.

- **Scripts are working as of March 2020**

# Launch

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/csianglim/weather-gc-ca-python/master)

To run this notebook interactively on the cloud, click the Launch Binder button or use the [Syzygy](http://intro.syzygy.ca/getting-started/) platform. 

Feel free to use, copy, paste, modify or distribute this notebook however you wish.

*These examples are provided as-is with no guarantee that they will work in the future if Environment Canada modifies their API.*

Similar projects:
- [data-gc-ca-api](https://github.com/igable/data-gc-ca-api), but it's about 2 years old, not sure if it's still working.

# Contents
- [Part I: Data Extraction and Cleaning](https://github.com/csianglim/weather-gc-ca-python/blob/master/Part%20I%20-%20Data%20Extraction%20and%20Cleaning.ipynb)

# Data Source
- [climate.weather.gc.ca/historical_data/search_historic_data_e.html](climate.weather.gc.ca/historical_data/search_historic_data_e.html)
