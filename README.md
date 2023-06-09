# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
First we need to open the required file from one file to another file.

## Step 2:
Using key word "with" to open the required file.

## Step 3:
Again using the with keyword to open the empty file.

## Step 4:
The empty file is open by using "w" which is used to write only.

## Step 5:
The for fuction is used to take the each line from the main file.

## Step 6:
Write() is used to write the lines of main file to the empty file or do the directed file.

## Step 7:
Print the output.

## PROGRAM:
```
Developed By : Vasanth S
Register Number : 212222110052
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
```

### OUTPUT:
<img width="335" alt="1" src="https://github.com/vasanth0908/copy-file/assets/122000018/8d3ef41f-922c-44ca-9b5f-d72f6990e651">



## RESULT:
Thus the program is written to copy the contents from one file to another file.
