# Excel Project: London Bike Sharing 2016

## **Introduction**

This Excel project aims to analyze the London Bike Sharing dataset sourced from Kaggle. The project includes data cleaning, exploration, and analysis to derive meaningful insights about bike usage patterns in London.

## **Data Source**

The dataset used for this project is the “London Bike Sharing dataset” from Kaggle. It was selected due to its large volume and potential for extensive data cleaning, exploration, and analysis. The dataset can be found here - https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset.

## **Key steps in data cleaning:**

Used only the complete dataset for 2016.
Removed duplicates using the “Remove Data Duplication” option.
Renamed columns for clarity.
Separated “time” from the timestamp and converted it to "Date" and "Time".
Kept only the real temperature column, deleting the "feel like" temperature.
Converted data types for temperature, humidity, and wind speed to numbers.
Transformed numerical weather codes and other status columns to text using nested IF functions.
Updated holiday statuses based on the UK Public Holiday list.


## **Data Analysis**

**Seasonal Bike Ridership:** Bike ridership shows significant variation across seasons, with the highest numbers observed during summer and spring. This trend suggests that warmer weather conditions are conducive to increased biking activity.

**Impact of Wind Speed on Ridership:** There is an inverse relationship between wind speed and bike ridership. Higher wind speeds correlate with fewer riders, indicating that windy conditions deter people from cycling.

**Holiday Influence on Ridership:** Holidays such as Christmas and Good Friday coincide with notable increases in bike ridership. This pattern suggests that holidays, possibly due to reduced work commitments and favorable weather, encourage more people to engage in biking activities.

**Temperature and Ridership Patterns:** Bike ridership tends to align positively with temperature, peaking during the warmer months like July and August. This observation underscores the preference for biking in more comfortable weather conditions.

**Weekday vs. Weekend Riding Behavior:** On weekdays, the peak bike riding hours during morning and evening correlate with typical commuting times. This suggests that many riders use bikes as a mode of transportation to commute to and from work or other daily activities. In contrast, on weekends, the steady increase in ridership throughout the day likely reflects recreational and leisurely biking, as people have more flexible schedules and time for outdoor activities. 



## **Conclusions**

In 2016, 10.1 million riders used the London Bike Sharing service, with peak usage in summer and spring. Weekday peak hours correlate with work commute times, while holidays see increased usage. These insights can help Transport for London (TFL) manage resources, maintenance, and operations to meet demand and improve system efficiency.
