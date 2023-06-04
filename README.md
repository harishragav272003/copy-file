
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
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by:Tharun Kumar.M
RegisterNumber: 212222110013

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![image](https://github.com/harishragav272003/copy-file/assets/119345345/7d609c53-5525-4ebc-a544-f709d7e8c4bb)

![image](https://github.com/harishragav272003/copy-file/assets/119345345/0fc9108f-1e06-4eb7-8599-e5d70646c69e)

![image](https://github.com/harishragav272003/copy-file/assets/119345345/0208f6b4-b568-4921-9c1d-5632b2bfdfd0)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
