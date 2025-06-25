# Bike Sharing Analysis

```python
# imports
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np
%matplotlib inline
```

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
