# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open the source file in read mode.

### Step 2: 

Open the destination file in write mode.
 
### Step 3: 

Read the contents of the source file.

### Step 4:  

Write the contents,read from the source file to destination file.

### Step 5: 

Close both files.

### Step 6: 

End the program.

## PROGRAM:
```
def copy(src,dest):
    with open(src,'r') as src_file:
        with open(dest,'w') as dest_file:
            dest_file.write(src_file.read())
```

### OUTPUT:

![alt text](<Copy file.png>)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
