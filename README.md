# Bike Sharing Analysis


# Problem Statement
This project seeks to investigate how temporal features and weather conditions affect the number of bike sharing demand, aiming to uncover meaningful insights that can inform operational strategies and improve service responsiveness.


# Introduction
This project focuses on analyzing bike sharing data from Capital Bikeshare in Washington, D.C., USA, for the period between January 1, 2011, and December 31, 2012. The data is aggregated on an hourly basis. This means that no initial and final locations of the individual rides are available, but only the total number of rides per hour. Nevertheless, additional meteorological information is available in the data, which could serve as a driving factor for identifying the total number of requests for a specific time frame (bad weather conditions could have a substantial impact on bike sharing demand)


# Dataset
 The columns from the original dataset are splitted into three main groups:

- temporal features: This contains information about the time at which the record was registered. This group contains the dteday, season, yr, mnth, hr, holiday, weekday, and workingday columns.
- weather related features: This contains information about the weather conditions. The weathersit, temp, atemp, hum, and windspeed columns are included in this group.
- record related features: This contains information about the number of records for the specific hour and date.


## Understanding the data
```python
# load hourly data
hourly_data = pd.read_csv('https://raw.githubusercontent.com/'\
'PacktWorkshops/'\
'The-Data-Analysis-Workshop/'\
'master/Chapter01/data/hour.csv')
```

```python
hourly_data.head(10)
```

![Image](https://github.com/user-attachments/assets/d7397000-2a32-4daf-8071-bf8f93e5debb)
