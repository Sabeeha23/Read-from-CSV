# Read-from-CSV

## AIM:
To write a python program to read content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
#Developed by: Sabeeha Shaik
#Register Number: 23012003
```
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Sabeeha23/Read-from-CSV/assets/150231876/8fcc1a1a-e4c0-40b5-b85b-205967a33148)

![Screenshot 2023-12-29 232305](https://github.com/Sabeeha23/Read-from-CSV/assets/150231876/99c0fd86-9ca8-4101-b83e-9c5c0cec9c27)


## RESULT:
Thus the python program for reading content from a CSV file is successfully executed. 
