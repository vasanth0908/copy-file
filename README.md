# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:

with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
Text File:
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
Empty File:
with open("data.txt","w") as fd:
 fd.write("")
Copyed file:
with open("data.txt","r") as f2:
  data1=f2.read()

### OUTPUT:
<img width="335" alt="1" src="https://github.com/vasanth0908/copy-file/assets/122000018/8d3ef41f-922c-44ca-9b5f-d72f6990e651">



## RESULT:
Thus the program is written to copy the contents from one file to another file.
