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
Developed by: MUKESH.R
RegisterNumber: 23006020

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2023-12-24 094332](https://github.com/2005Mukesh/copy-file/assets/138849308/21bb55fa-1dd3-499d-9576-cd6a5aa43464)
![Screenshot 2023-12-24 094345](https://github.com/2005Mukesh/copy-file/assets/138849308/6804f336-0fa2-43c3-975a-656a5681cc5a)
![Screenshot 2023-12-24 094355](https://github.com/2005Mukesh/copy-file/assets/138849308/93f94236-df29-4175-a2fd-2d693c551699)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
