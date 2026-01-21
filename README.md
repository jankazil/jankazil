# Atmospheric, Climate, and Weather Data Tools

Software for automated data retrieval, processing, analysis, and visualization.

## Projects

- **[Arotake](https://github.com/jankazil/Arotake)**  
  Provides a command-line tool and an application programming interface (API) that automate evaluating
  - [NOAA High-Resolution Rapid Refresh (HRRR)](https://rapidrefresh.noaa.gov/hrrr/) surface forecasts
  
  against observational time series:
  
  - [Local Climatological Data version 2 (LCD v2)](https://www.ncei.noaa.gov/access/search/data-search/local-climatological-data-v2)
  - [Integrated Surface Database Lite (ISD-Lite)](https://www.ncei.noaa.gov/access/search/data-search/global-hourly)
  
- **[hrrr-data](https://github.com/jankazil/hrrr-data)**  
  Provides a command-line tool and an API that automate accessing, downloading, and processing NOAA High-Resolution Rapid Refresh (HRRR) forecast data from NOAA’s public AWS S3 bucket.

- **[`lcd-v2-data`](https://github.com/jankazil/lcd-v2-data)**  
  Provides a command-line tool and an API that automate downloading, filtering, and processing NOAA Local Climatological Data version 2 ([LCD v2](https://www.ncei.noaa.gov/access/search/data-search/local-climatological-data-v2)) observations for
  
  - selected U.S. states and territories,
  - Regional Transmission Organization (RTO) and Independent System Operator (ISO) [regions](https://www.ferc.gov/power-sales-and-markets/rtos-and-isos).
  
  The original time series are converted from their irregularly spaced, local time to full-hour UTC time.

- **[isd-lite-data](https://github.com/jankazil/isd-lite-data)**  
  Provides a command-line tool and an API that automate downloading, filtering, and processing NOAA Integrated Surface Database Lite ([ISD-Lite]((https://www.ncei.noaa.gov/access/search/data-search/global-hourly))) observations for
  
  - selected countries,
  - U.S. states and territories,
  - Regional Transmission Organization (RTO) and Independent System Operator (ISO) [regions](https://www.ferc.gov/power-sales-and-markets/rtos-and-isos).
  


