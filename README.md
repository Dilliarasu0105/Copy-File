# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.
### Step 2: 
Print the number of contents to be displayed using df.head(). 
### Step 3: 
The number of rows returned is defined in Pandas option settings.
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: Dilliarasu M
#Register Number: 212223230049

with open("text1.txt", 'r') as fp:
    msg=fp.read()
with open("copy.txt", 'w') as fp1:
    fp1.write(msg)
```
### OUTPUT:

![image](https://github.com/Dilliarasu0105/Copy-File/assets/144979593/d9743460-8512-48e8-b166-6575fe69b38a)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
