# TSA-EX1
# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 12.08.2025

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

# Read the CSV file
df = pd.read_csv("asiacup.csv") 

# Plot Year vs Avg Bat Strike Rate
plt.figure(figsize=(10,6))
plt.plot(df["Year"], df["Avg Bat Strike Rate"], marker='o', color='b', linestyle='-')

# Labels and title
plt.xlabel("Year")
plt.ylabel("Avg Bat Strike Rate")
plt.title("Year vs Avg Bat Strike Rate - Asia Cup")

# Show grid
plt.grid(True)

# Display the plot
plt.show()



```
# OUTPUT:

<img width="850" height="545" alt="OUTPUT1A" src="https://github.com/user-attachments/assets/dfe7c5e3-d1ea-45cb-8150-f221c1d73d58" />



# RESULT:
Thus we have created the python code for plotting the time series of given data.
