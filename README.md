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
![Screenshot 2024-01-02 211147](https://github.com/hindhujanaki/copy-file/assets/148514666/21ff924d-d7d2-4628-8f15-203d6eae76e1)
![Screenshot 2024-01-02 211430](https://github.com/hindhujanaki/copy-file/assets/148514666/72f02348-39c5-4935-b7da-66bcd8d90379)
![Screenshot 2024-01-02 211444](https://github.com/hindhujanaki/copy-file/assets/148514666/3e70cbb5-4fec-444b-8212-cc8c0ca083d5)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
