# Data-Nerds

Team name: Data Nerds
Language: Python
Software:
Data sources:
Kaggle
https://archive.ics.uci.edu/ml/datasets.php
https://data.gov/
https://databank.illinois.edu/datasets

Data Dictionary:

| Table | Attribute Name | Description | Datatype |
| --- | --- | --- | --- |
|  | record_# | Record number | Numeric |
|  | date | Date data was recorded | Date |
| Wildfire | latitude | Latitude of location where satellite data was acquired | Numeric |
| Wildfire | longitude | Longitude of location where satellite data was acquired | Numeric |
| Wildfire | satellite | Name of the satellite that acquired data | Text |
| Wildfire | avg_frp | Average Fire Radiative Power; measurement of heat energy released from fire, or strength, in Megawatts (MW) | Numeric |
|  | surface_temp | Surface temperature of location where satellite data was acquired | Numeric |
| Wildfire | confidence | This attribute represents the algorithmic confidence level that a pixel is a fire pixel. The confidence range is between 0 and 100, with 100 being the highest confidence. A higher confidence level indicates that the pixel is more likely to be a fire pixel. | Numeric |
| Wildfire | fire_count | Number of fires in a day | Numeric |
| Weather | max_temp | Maximum temperature recorded for a day | Numeric |
| Weather | rain | Rain levels of a day measured in inches | Numeric |
| Weather | city | Name of city in which data was collected | Text |


Data Schema:
![alt text](https://github.com/UIUC-DSC/Data-Nerds/blob/main/Data_Schema.png)

Ideas:
meteorology (climate data)
Details on global temperatures
Extreme weather patterns
Healthcare
COVID-19 data
Hospitalization rate
Prevalence of infectious diseases over history
Agriculture
Biology
Genetics(?)
Detecting/predicting diseases


Questions (general)
What trends have been occuring in the dataset?
What is the significance of this data / topic?
Meteorology
What do changing weather patterns mean for the climate?
What geographic areas are at high risk for (damage)?
Why are weather patterns important?
Are we trying to predict using a machine learning model? Or a regression model

Data sets we might use:
https://archive.ics.uci.edu/ml/datasets/Multimodal+Damage+Identification+for+Humanitarian+Computing
https://archive.ics.uci.edu/ml/datasets/Forest+Fires
https://archive.ics.uci.edu/ml/datasets/PM2.5+Data+of+Five+Chinese+Cities
https://archive.ics.uci.edu/ml/datasets/Greenhouse+Gas+Observing+Network
https://data.ca.gov/dataset/sgma-climate-change-resources/resource/b3595018-e0d0-467f-b485-32e62e5ec5ac
https://www.kaggle.com/datasets/selfishgene/historical-hourly-weather-data (~5 years of high temporal resolution (hourly measurements) data of various weather attributes, such as temperature, humidity, air pressure, etc.) - has 3 california cities
https://data.cnra.ca.gov/dataset/sgma-climate-change-resources?ref=hackernoon.com
https://github.com/cc-ai/climategan

Kushi’s advice:
Analyze issues coming from climate change
What areas are more higher risk?
Combining data might be important for this project
Maybe narrow down a geographic area (based on most impacted areas)
Maybe predict future data

Goals:
Find / finalize data set
Define project scope
Find region to focus on

Try to look for:
Areas most affected by climate change (lighter color is more affected)
Climate Change Impacts on California