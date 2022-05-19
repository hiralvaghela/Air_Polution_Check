# Future Ready Talent
# Air_Polution_Check

Project made as part of the Future Ready Talent Virtual Internship Program organized by Microsoft.

### Problem Statement

Indian cities have some of the **most polluted air** in the world, according to most global air quality databases. A majority of cities, including both mega cities as well as smaller cities are emerging as **pollution hotspots** with ordinary citizens facing severe **health impacts** leading to a wide range of diseases, including stroke, chronic obstructive pulmonary disease, trachea, bronchus and lung cancers, aggravated asthma and lower respiratory infections. Vehicle emissions, fuel oils and natural gas to heat homes, by-products of manufacturing and power generation, particularly coal-fueled power plants, and fumes from chemical production are the primary sources of **human-made air pollution**. It is clear that **public participation** plays a key role in the successful implementation of air quality interventions. For this, it is necessary to get a sense of the priorities and current **levels of awareness** so that **public engagement efforts** can be better defined and implemented.

### Project Description

To overcome the challenges pondered over in the problem statement, I ideated a web application with the following functionalities:

1. **Fetching real-time data of the AQI**: To make the public aware about the amount of air contamination that has be done in their locality, visualizing the **real-time data** plays a **vital role** in informing, analyzing and taking necessary steps to reduce risks from toxic air pollutants. Air pollutants such as:

   + Carbon Monoxide
   + Nitrogen Monoxide
   + Nitrogen Dioxide
   + Ozone
   + Sulphur Dioxide
   + Fine particles matter
   + Coarse particulate matter
   + Ammonia

   (All above air pollutants in units of μg/m³ provided by OpenWeatherMap), These raw measurements are converted into a separate **Air Quality Index** (AQI) value for each pollutants using standard formulae developed by **Environmental Protection Agency** (EPA). The highest of these AQI values are reported as the AQI value for that day. The **Air Quality Index** (AQI) is an index for reporting air quality on a daily basis. It is a measure of how air pollution affects one's health within a short time period. The purpose of the AQI is to help people know how the local air quality impacts their health.

2. **Automatically locating the user's location**: Sometimes it becomes a bit **tedious** to enter the longitude and latitude values of the user's location. So as to make this process much simpler, this step is **automated** to automatically detect the user's approximate location.

3. **Reading aloud the data**: Used as an **accessibility** feature to help the user who might have some trouble reading on-screen text, but it's also convenient for those who might want to be read to, by presenting information in an **audio format**.

3. **Providing more information through a chat interface**: A user might have some doubts, queries or want to **learn more** about air pollution. Through a chat interface the user can type out the question and **relevant information** will be provided.

Web App Homepage


