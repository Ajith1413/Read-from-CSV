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
#Program to read contents from a CSV file.
#Developed by: AJITH KUMAR A
#RegisterNumber: 23002150
```
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Number of Rows:',len(f.axes[0]))
print('Number of column:',len(f.axex[1]))
```
## OUTPUT:
![image](https://github.com/Ajith1413/Read-from-CSV/assets/139842524/4e385378-c24a-418d-bbeb-b5016c116f9e)
![image](https://github.com/Ajith1413/Read-from-CSV/assets/139842524/1e42a64d-fe88-4747-9929-369a22ab8c55)


## RESULT:
Hence the program is executed successfully!
