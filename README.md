# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file and add some content into it.
### Step 2: 
 Open file using with keyword/built-in function in read mode.
### Step 3: 
Use read() to read the contents of the file.
### Step 4:  
Split the lines using split().
### Step 5: 
Iterate the list and increment the count
### Step 6: 
Print the output.
## PROGRAM:
To write a program for getting the word count from a file.
Developed by: paulsamson s
RegisterNumber: 212222230104
```
def wordcount():
    cnt = 0
    with open("MyFile.txt","r") as fp:
        data = fp.read()
        for line in data.split():
            cnt += 1
    print("The number of words in the given file is:",cnt)
wordcount()
```
### OUTPUT:
![153130605-800df2b3-c476-413c-b85c-512547cae752](https://github.com/Rohithravi333/Word-count/assets/119394126/ea10b152-e87e-48a1-8f03-ba64df8e12ae)
output:
![153130618-2fdb5469-9e15-4224-b9c7-cf732fd8331c](https://github.com/Rohithravi333/Word-count/assets/119394126/66617513-12dd-4f73-8b1f-4166b43deb11)



## RESULT:
Thus the program is written to find the word count from a text.
