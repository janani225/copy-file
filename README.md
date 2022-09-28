# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.

### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program

## PROGRAM:
```
with open('janani.txt','r') as f3:
    with open ('janu.txt','a') as f4:
        for line in f3:
            f4.write(line)
```            

### OUTPUT:
![Screenshot from 2022-09-26 14-36-39](https://user-images.githubusercontent.com/113497333/192240077-0b9ac470-69d6-4569-b5a0-25709e3f0473.png)

Text file:
![Screenshot from 2022-09-26 14-39-25](https://user-images.githubusercontent.com/113497333/192240127-0aa9a7e9-6fd7-4bb7-bde2-ea4687469c63.png)

Copy file:
![Screenshot from 2022-09-26 14-39-25](https://user-images.githubusercontent.com/113497333/192676873-c1fbeb80-e646-41ba-aaab-766281b90854.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
