# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.
### Step 3:
Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: NAVEEN S
#RegisterNumber: 212222110030

import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![245212315-ee3690a4-8401-4f07-856c-6a0b7c409127](https://github.com/NaveenSivamalai/Read-from-CSV/assets/123792574/4a238afe-2110-4689-9576-d9584f8dedb4)

## RESULT:
Hence the programe is executed successfully!
