# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Read the csv file using csv_method
### Step 3:
Use head and tail method to get the required contents from the file. 
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Display the result
## PROGRAM:
```
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```
## OUTPUT:
![image](https://github.com/YuvarajVB/Read-from-CSV/assets/151488375/2d4c49cb-709c-4690-8068-4409eb7a5281)

## RESULT:
Thus the program excuted successfully
