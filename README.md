# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys module
### Step 2: 
 import sys module
### Step 3: 
import sys module
### Step 4:  
use split() method to split the file into word
### Step 5: 
use len() to find the total word
### Step 6: 
run the program to determine the number of word in a file created
## PROGRAM:
```
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] +=1
print(count)
f.close()
```
### OUTPUT:
![output](output.jpeg)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
