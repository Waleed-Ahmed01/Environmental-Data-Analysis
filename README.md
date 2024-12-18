# Environmental-Data-Analysis
## Analyzing the effect of Environmental Factors on Air quality of Shanghai-China for the last 10 Years
The goal was to analyse the effect of environmental factors like Temperature, Wind Direction, Wind Speed, Humidity and Pressure on Air Quality which is compromised by pollutants namely PM2.5, PM10, SO2,NO2 & CO
## Data Extraction
The data for environmental conditions was feasibly extracted using Meteostat which is one of the largest vendors of open weather and climate data. The Meteostat Python library provides simple access to open weather and climate data using Pandas. The latitude and longitude values for Shanghai have been used to fetch Hourly data for the past 10 years, since daily or monthly APIs donot provide us with all the environmental data we need. 
The data for air quality was not available through meteostat library. It was acquired from China's air quality on-line monitoring and analysis platform https://www.aqistudy.cn/historydata/ and saved into an excel file. The data required a lot of preprocessing and imputation before it could be used for analysis all of which is done using python jupyter notebook environment and contained in file 'data-extraction&cleaning.ipynb'
## Data Description:
Description of numerical variables are summarized in the table below:

<img src="https://github.com/user-attachments/assets/686818d0-ca36-4987-b3c9-8f5e0795c326" heigth="950" width="850">

## Time Series Analysis
The overall Air Quality of Shanghai has improved since the last 10 years with a noticeable decline in the value of  Air quality index (AQI) 

<img src="https://github.com/user-attachments/assets/d37dff3f-a832-43e2-ba54-f572dc8400fd" heigth="350" width="350">  <img src="https://github.com/user-attachments/assets/80f27b0b-93fa-4759-8d41-8c69da493a52" heigth="325" width="350"> 

All of the pollutants show a downward trend from 2014 till 2024 with a clear seasonal pattern of maximum concentration at the start of every year which decreases during the mid of every year. Similarly, the level of ozone declines during the period when the pollutants levels are high in the atmosphere. The pollutant levels are low when temperature is high and pressure is low

<img src="https://github.com/user-attachments/assets/f53a73a5-3006-45f3-b1d7-11a236e74fc1" heigth="325" width="325"> <img src="https://github.com/user-attachments/assets/21bf5627-c553-4b3f-bc0a-2a55dec20e16" heigth="325" width="325">
<img src="https://github.com/user-attachments/assets/88fde50e-76dd-4133-bfff-595b1298947e" heigth="650" width="650"> 
<img src="https://github.com/user-attachments/assets/8b6697ea-756e-4df7-a2e4-f16b570f5536" heigth="650" width="650"> 

## Correlation of Environmental factors with Air Quality
*Pollutants are highly correlated with temperature and pressure as compared to other environmental factors  <br />
*Temperature has a negative relation to all pollutants and pressure is positively correlated  <br />
*AQI (Air Quality Index) has the highest correlation with PM2.5, PM 10,CO, SO2 and then NO2  <br />

<img src="https://github.com/user-attachments/assets/9fd7e001-1a0f-405a-9e89-693739a163b2" heigth="600" width="600"> 









 



