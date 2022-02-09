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

open line
 
### Step 3: 

usinf for loop

### Step 4:  

using split()

### Step 5: 

counting words using len()

### Step 6: 

print the output

## PROGRAM:

import sys
count=0
with open(sys.argv[1], 'r') as f:
    for line in f:
        word = line.split()
        count += len(word)
print("word count in file =", count)

### OUTPUT:
![GitHub Logo](.//img1.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
