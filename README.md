# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Use open function to open the file in which we want to copy from and access it in read mode.

Step 2: Read the file and store in a variable.

Step 3: Now create a new file in which we want to paste the content using write access mode.

Step 4: Use write function to copy the read file that has been stored in the variable.

Step 5: The content in the original file will be copied in the new file.

Step 6: End the program.

## PROGRAM:
```python
#To write a program for copying the contents from one file to another file.
#Developed by: Sriram.s.s
#RegisterNumber: 22004880
with open("MyFile.txt","r") as fp:
    x = fp.read()
with open("MyFile2.txt","w") as fp1:
    fp1.write(x)
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/120554177/215004832-2581198c-a5b3-4f2b-9bd7-c4a9601e72fa.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
