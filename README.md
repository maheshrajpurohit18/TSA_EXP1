# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 04-03-2025
### Name: Mahesh Raj Purohit J

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```
```
data = pd.read_csv("C:/Users/SEC/Downloads/archive(1)/manufacturing_6G_dataset.csv")
```
```
data.set_index('Timestamp', inplace=True)
```
```
sns.histplot(data["Temperature_C"], bins=30, kde=True, color="blue")
plt.title("Temperature Distribution")
plt.show()
```










# OUTPUT:

![Screenshot 2025-03-04 143900](https://github.com/user-attachments/assets/4a87052f-700a-4f84-a0d7-cfb9231db860)





# RESULT:
Thus we have created the python code for plotting the time series of given data.
