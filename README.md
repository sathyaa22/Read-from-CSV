# Read-from-CSV

## AIM:
To write a python program to read from csv file

## ALGORITHM:
### Step 1:
Import the pandas to use the functions inside the module

### Step 2:
Read the csv file using pd.read_csv()

### Step 3:
Read random number ofrows and columns using df.head() and df.tail()

### Step 4:
Print the number of rows using df.axes[0] and number of columns using df.axes[1]

### Step 5:
End the program

## PROGRAM:

Developed by: SATHYAA R

Register number: 212223100052

```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("N0. of rows", len(df.axes[0]))
print("No. of columns", len(df.axes[1]))
```

## OUTPUT:

![alt text](<Screenshot 2024-05-15 190745.png>)
![alt text](<Screenshot 2024-05-14 113504.png>)

## RESULT:
Thus, the program to read from csv file is written and executed successfully.