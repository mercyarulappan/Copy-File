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
```python
#Developed by: Mercy A
#Register Number: 212223110027

with open("text1.txt",'r') as file:
    msg=file.read()
with open("copy.txt","w") as file2:
    file2.write(msg)
```

### OUTPUT:

![Screenshot 2024-05-13 084712](https://github.com/mercyarulappan/Copy-File/assets/149233730/91e6137a-dde0-4910-8eca-be7118f5f45a)

![Screenshot 2024-05-13 084604](https://github.com/mercyarulappan/Copy-File/assets/149233730/90e8a99d-1b40-4e64-9024-c90053fd5653)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
