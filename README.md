# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 28-04-2026

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature).
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
from matplotlib import pyplot as plt
import pandas as pd
import seaborn as sns
df=pd.read_csv("market.csv")
df.head()
plt.title("Market Dataset")
plt.xlabel("High")
plt.ylabel("Date")
plt.legend()
plt.grid(True)
sns.distplot(df['High'],color='green')
```


# OUTPUT:


<img width="780" height="551" alt="image" src="https://github.com/user-attachments/assets/380a090f-e204-44ec-b8fa-42da339dd17f" />


# RESULT:
Thus we have created the python code for plotting the time series of given data.
