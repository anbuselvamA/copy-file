# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new text file
### Step 2: 
Open the file using open() in read mod
 
### Step 3: 
Initialize count is 0

### Step 4:  
for each line split the words and store in a list

### Step 5: 
add the length of the list to the count for each line

### Step 6: 
print the count


## PROGRAM:
Developed by: anbuselvam
RegisterNumber: 22009081

f=open("sample1.txt","r")
wc=0
for line in f:
    word=line.split(" ")
    wc=wc+len(word)
print("word count is:",wc)
f.close()

### OUTPUT:
![output](/Screenshot%20(75).png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.