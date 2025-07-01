# Bike Sharing Analysis

```python
# imports
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np
%matplotlib inline
```


# Problem Statement
This project seeks to investigate how temporal features and weather conditions affect the number of bike sharing demand, aiming to uncover meaningful insights that can inform operational strategies and improve service responsiveness.


# Introduction
This project focuses on analyzing bike-sharing usage data from Capital Bikeshare in Washington, D.C., covering the period from January 1, 2011, to December 31, 2012. The dataset provides hourly aggregated counts of total bike rentals, without individual trip details such as start and end locations. Despite this limitation, the dataset includes rich meteorological information—such as temperature, humidity, and weather conditions—which can be valuable for uncovering patterns in user demand. By examining the relationship between time-based variables and weather factors, this analysis aims to identify trends and influences on hourly bike rental activity, offering insights into how external conditions affect bike-sharing usage.


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
