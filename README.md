# Multivariate-Time-series-Analysis-using-LSTM-ARIMA
Multivariate Time series Analysis Using LSTM &amp; ARIMA

# Data
The data is obtained from UCI Machine Learning Repository. It was recorded by 5 metal oxide chemical sensors located in a 
significantly polluted area in an Italian city, and I will analyze one of them, CO. The dataset contains 9358 instances of 
hourly averaged responses spreading from March 2004 to February 2005.

Below is the attributes description loaded from UCI Machine Learning Repository.
Attribute Information:

0 Date	(DD/MM/YYYY) 

1 Time	(HH.MM.SS) 

2 True hourly averaged concentration CO in mg/m^3 (reference analyzer) 

3 PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)	

4 True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer) 

5 True hourly averaged Benzene concentration in microg/m^3 (reference analyzer) 

6 PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)	

7 True hourly averaged NOx concentration in ppb (reference analyzer) 

8 PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted) 

9 True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)	

10 PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)	

11 PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted) 

12 Temperature in Â°C	

13 Relative Humidity (%) 

14 AH Absolute Humidity 


Problem:

Humans are very sensitive to humidity, as the skin relies on the air to get rid of moisture. The process of sweating is your body's attempt to keep cool and maintain its current temperature. If the air is at 100-percent relative humidity, sweat will not evaporate into the air. As a result, we feel much hotter than the actual temperature when the relative humidity is high. If the relative humidity is low, we can feel much cooler than the actual temperature because our sweat evaporates easily, cooling us off. For example, if the air temperature e is 75 degrees Fahrenheit (24 degrees Celsius) and the relative humidity is zero percent, the air temperature feels like 69 degrees Fahrenheit (21 C) to our bodies. If the air temperature is 75 degrees Fahrenheit (24 C) and the relative humidity is 100 percent, we feel like it's 80 degrees (27 C) out.

Objective:

So we will predict the Relative Humidity of a given point of time based on the all other attributes affecting the change in RH

Content:

1) Load data

2) Basic statistics

3) Data Cleaning

4) Co-relation between variables

5) Influence of features on output-RH

6) LSTM ARIMA
