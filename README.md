# Read-from-CSV

## AIM:

## ALGORITHM:

Step 1:

Import pandas as pd.

Step 2:

Read the CSV file using read_csv method.

Step 3:

Use head and tail method to get the required contents from the file.

Step 4:

Use len() method to get the number of rows and columns.

Step 5:

Print the output.
## PROGRAM:
```
#Developed by: SAKTHIVEL R
#Reference No: 22009121
import pandas as pd 
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```

## OUTPUT:
![Screenshot from 2023-01-26 18-39-50](https://user-images.githubusercontent.com/120550359/214843867-b0d37b82-921a-4ae0-9f8a-1dbe22efde83.png)






## RESULT:
Thus a python program is written to read the contents of a CSV file.
