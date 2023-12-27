# Data-Nerds

Team name: Data Nerds \
Language: Python \
Data sources: Kaggle \
  https://archive.ics.uci.edu/ml/datasets.php \
  https://data.gov/ \
  https://databank.illinois.edu/datasets

## Presentation
[Data Nerds.pptx](https://github.com/UIUC-DSC/Data-Nerds/files/13774878/Data.Nerds.pptx)

## Project Overview
* Climate change is linked to wildfires through increase in temperatures
* Looking at details on global temperatures and extreme weather patterns
* Analysis is focused on California due to an abundance of wildfire data

## Data Dictionary:

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


## Data Schema:
![alt text](https://github.com/UIUC-DSC/Data-Nerds/blob/main/Data_Schema.png)
