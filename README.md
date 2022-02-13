# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

import sys

### Step 2: 
 Give count = 0 because begin count is zero
 
### Step 3: 
Open a file in read mode.
### Step 4:  

Split a line using a for loop.

### Step 5: 

Now count a word using len(word).

### Step 6: 

Then get a output by giving print(count). 

## PROGRAM:
```
import sys
count=0
with open(sys.argv[1], 'r') as f:
    for line in f:
        word = line.split()
        count += len(word)
print("word count in file =", count)
```
### OUTPUT:
![GitHub Logo](.//img1.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
