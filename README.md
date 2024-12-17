# Environmental-Data-Analysis
## Analyzing the effect of Environmental Factors on Air quality of Shanghai-China for the last 10 Years
The goal was to analyse the effect of environmental factors like Temperature, Wind Direction, Wind Speed, Humidity and Pressure on Air Quality which is compromised by pollutants namely PM2.5, PM10, SO2 and NO2
## Data Extraction
The data for environmental conditions was feasibly extracted using Meteostat which is one of the largest vendors of open weather and climate data. The Meteostat Python library provides simple access to open weather and climate data using Pandas. The latitude and longitude values for Shanghai have been used to fetch Hourly data for the past 10 years, since daily or monthly APIs donot provide us with all the environmental data we need. 
The data for air quality was not available through meteostat library. It was acquired from China's air quality on-line monitoring and analysis platform https://www.aqistudy.cn/historydata/ and saved into an excel file. The data required a lot of preprocessing and imputation before it could be used for analysis all of which is done using python jupyter notebook environment and contained in file 'data-extraction&cleaning.ipynb'

## Time Series Analysis
<img src="https://github.com/user-attachments/assets/ca52ced0-a7fe-46d3-b485-47cfd33f3463" height="200" width="200">

