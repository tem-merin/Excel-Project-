# Excel Project: London Bike Sharing Data Analysis

## **Introduction**

This Excel project aims to analyze the London Bike Sharing dataset sourced from Kaggle. The project includes data cleaning, exploration, and analysis to derive meaningful insights about bike usage patterns in London.

## **Data Source**

The dataset used for this project is the “London Bike Sharing dataset” from Kaggle. It was selected due to its large volume and potential for extensive data cleaning, exploration, and analysis. The dataset can be found here.

## **Key steps in data cleaning:**

Used only the complete dataset for 2015.
Removed duplicates using the “Remove Data Duplication” option.
Renamed columns for clarity.
Separated “time” from the timestamp and converted it to "Date" and "Time".
Kept only the real temperature column, deleting the "feel like" temperature.
Converted data types for temperature, humidity, and wind speed to numbers.
Transformed numerical weather codes and other status columns to text using nested IF functions.
Updated holiday statuses based on the UK Public Holiday list.


## **Data Analysis**

**Season Wise Bike Riders:** Pie chart showing bike riders per season, with highest numbers in summer and spring.

**Relation Between Wind & Bike Riders:** Chart showing fewer riders with higher wind speeds.

**Holiday Bike Riders:** Chart showing increased riders during holidays like Christmas and Good Friday.

**Relation Between Temperature & Bike Riders:** Chart showing more riders at higher temperatures, peaking in July and August.

**Weekday and Weekend Bike Riders Comparison by Hour:** Chart comparing peak hours on weekdays (morning and evening) to weekends (steady increase from morning to evening).

## **Conclusions**

In 2015, 10.1 million riders used the London Bike Sharing service, with peak usage in summer and spring. Weekday peak hours correlate with work commute times, while holidays see increased usage. These insights can help Transport for London (TFL) manage resources, maintenance, and operations to meet demand and improve system efficiency.
