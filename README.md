# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
 Pass the filename as the first argument after the name of script.Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use spli() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
Developed by: Jothilakshmi
Register number: 212223110017
'''
import sys
file= open(sys.agvr[1]
data=file.read()
words=data.split()
print("Total Words:",len(words))
```

### OUTPUT:
![commandoutput1](https://github.com/Jothilakshmi12/command-line-arguments-to-count-word/assets/138849182/0ace15b1-a793-4113-a508-846b1a9ee032)
![comandoutput2](https://github.com/Jothilakshmi12/command-line-arguments-to-count-word/assets/138849182/4d67c978-3236-43b9-b142-1b567e556cd9)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
