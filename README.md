# CO2-geospatial-analysis


## Estimating Urban Carbon Emissions in a French city using IoT Sensor Network

In this project, I worked with the data of a French city to estimate the amount of carbon directly emitted over its territory by urban activities. To achieve this, I used data from a spatially distributed network of IoT sensors that measured CO2 concentration in real-time at a height of 3-5 meters above ground level.

## Key Components
Geospatial data: I used GeoJSON files containing the geometries of Dijon's communes, quartiers, and land cover data.
Sensor data: I collected real-time CO2 concentration measurements from IoT sensors installed throughout the city.
Data processing and analysis: I cleaned, preprocessed, and analyzed the data using pandas, geopandas, and other Python libraries.
## Workflow
- Data loading and preprocessing: I loaded the GeoJSON files and sensor data from an SQLite database, and preprocessed the data by dropping missing coordinates, duplicates, and performing spatial joins.
- Data visualization: I created several visualizations, such as:
  - A map of the city displaying the municipalities, quartiers, and sensor locations.
  <img src="https://user-images.githubusercontent.com/28387807/230375229-da7650ea-ed89-4331-b537-9176862e6386.png" width="400" >
  
  - A map displaying the average CO2 concentration values per sensor.
  <img src="https://user-images.githubusercontent.com/28387807/230375351-eee31f01-b950-443e-acb5-dcbd524ad870.png" width="400" >

  - Scatter plots illustrating the relationship between the minimum, maximum, and average CO2 concentration values.
   <img src="https://user-images.githubusercontent.com/28387807/230375476-2b3ac0ad-9393-435f-93ea-d269a0fdeb68.png" width="400" > <img src="https://user-images.githubusercontent.com/28387807/230375490-da4b6dd3-b260-440f-a921-ce99883d3a16.png" width="400" >
 

- Interpolation: I used a linear interpolation method to create a heatmap of CO2 concentration values across the city.
<img src="https://user-images.githubusercontent.com/28387807/230375551-e1593c23-e7b2-4889-aac7-cc017541e845.png" width="400" >



- Time series analysis: I analyzed the CO2 concentration values over time and fitted a polynomial model to the data.
<img src="https://user-images.githubusercontent.com/28387807/230375657-b28d7e83-d29b-4ad4-8718-7a2fd6e1106b.png" width="400" >


## Results
This project successfully demonstrates the potential of IoT sensor networks for monitoring urban carbon emissions in real-time. By visualizing and analyzing the sensor data, I can gain valuable insights into the spatial distribution of CO2 emissions across the city. This information can be used by local authorities to develop targeted policies and initiatives to reduce carbon emissions and combat climate change.
