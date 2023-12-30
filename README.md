# Read-from-CSV

## AIM:TO FIND A PYTHON PROGRAM TO READ FROM CSV

## ALGORITHM:
### step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4: 
Use len() method to get the number of rows and columns.
### Step 5:
Display the result

## PROGRAM:
```
'''
Developed by:singamala venkakta sai kumar reddy.
Register No: 212223230208
'''
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/23004205/Read-from-CSV/assets/138971114/5feb2f15-24ae-4212-87b0-471595379317)

## RESULT:
thus python program for reading content from CSV file is successful.
