# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Define the function as copy with arguements as existing file name and new file name.
### Step 2: 
 Open the existing file to read.
### Step 3: 
Open the new file to write.
### Step 4:  
Copy the contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.
### Step 6: 
End the program.

## PROGRAM:
'''
# Developed by: HARISH S
# REG-NO: 212223230071

with open("sam.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)


'''
### OUTPUT:
![image](https://github.com/pirateharishs/Copy-File/assets/166011385/40ec26cb-60e9-470b-8fd5-9f077a17ec17)

![image](https://github.com/pirateharishs/Copy-File/assets/166011385/dd5d19c5-b54c-424b-839f-340fd22d5281)

![image](https://github.com/pirateharishs/Copy-File/assets/166011385/4547be61-1beb-4075-a157-ffb71b10d48d)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
