# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content.
### Step 3: 
Read the file and close the file.
### Step 4:  
Now write content in the new file.
### Step 5: 
When done print "file copied successfully.
### Step 6: 
End the program
## PROGRAM
```
'''
#Program to copy the file
#Developed by: G.Hindhu
#Register Number:23014493
'''
with open("text1.txt",'r')as fp:
  msg1=fp.read()
with open("text2.txt",'a')as fp1:
  fp1.write(msg1)
print("Copied Successfully")
```
### OUTPUT:
![Alt text](<Screenshot 2024-01-02 202047.png>)
## RESULT:
Thus the program is written to copy the contents from one file to another file.