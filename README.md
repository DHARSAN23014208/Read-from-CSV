# Read-from-CSV

## AIM:To write the python program for reading content from a csv file.

## ALGORITHM:
### Step 1:import pandas as ps.
### Step 2:read the csv  file using read_csv method.
### Step 3:use the head and tail method to get the required contents from the file.
### Step 4:use len() method to get number of rows and coloumn.
### Step 5:Disply the result

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/DHARSAN23014208/Read-from-CSV/assets/149365413/ca448854-17a1-4e78-a36a-9a8a555cec3c)
![image](https://github.com/DHARSAN23014208/Read-from-CSV/assets/149365413/b2e8fa7d-876d-4215-866c-1ddc427d0ef2)



## RESULT:
Thus the python program for reading content from csv file is successful.
