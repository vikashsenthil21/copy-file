# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Assign a variable count =0
### Step 3: 
open a file in read mode
### Step 4:  
iterate a variable (lines) through the file
### Step 5: 
Assign a variable words = lines.split ()
### Step 6: 
 Now iterate through the variable and increase the count: and print the count vi
## PROGRAM:
```
'Program For Copying The Contents:
Developed by: VIKASH S
RegisterNumber: 22008879

print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
```

### OUTPUT:

![WhatsApp Image 2023-01-25 at 21 13 37](https://user-images.githubusercontent.com/119433834/214643735-f9e3559e-d79a-4272-a1e0-5257c3606870.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
