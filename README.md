# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function:

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by:DHANUSH P
RegisterNumber: 23001835

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/Dhanush0143/copy-file/assets/139841924/ca52188e-eea4-4da3-8339-a8881e28a6fa)

![image](https://github.com/Dhanush0143/copy-file/assets/139841924/d51a5ee3-c4de-4368-b16a-ccea3fcb3b67)
![image](https://github.com/Dhanush0143/copy-file/assets/139841924/e6f6a960-64f8-43cb-9de0-d651d645457e)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
