# DATE:
# EX-12 Read-from-CSV
## AIM:

## ALGORITHM:
### Step 1:
Start the program.
### Step 2:
Create a file nba.csv in anaconda navigator.
### Step 3:
Write a program to read the contents in the csv file.
### Step 4:
Run the program.
### Step 5:
Print the output.
### Step 5:

## PROGRAM:
```
# Developed by: DEEPIKA R
# Register number: 212223230038
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/e484aea7-01cc-4ca4-a5ce-4f917f010cca)

## RESULT:
Hence, the contents are read successfully.
