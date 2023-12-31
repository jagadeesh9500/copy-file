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
Now write the content in the new file.
### Step 5: 
When done print"File copied successfully".
### Step 6: 
End of the program
## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by :jagadeesh p 
#RegisterNumber:23013534
with open("file1.txt","r") as f:
    x=f.read()
with open("file2.txt","w") as f1:
    f1.write(x)
```
### OUTPUT:
![image](https://github.com/jagadeesh9500/copy-file/assets/149087921/68913092-36a9-4401-9686-a717411910e8)
![image](https://github.com/jagadeesh9500/copy-file/assets/149087921/a5b91605-e9a8-47e1-85f8-47a9bf96a447)
![image](https://github.com/jagadeesh9500/copy-file/assets/149087921/a2b3d1f3-c2a4-4986-8990-7165300d09cc)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
