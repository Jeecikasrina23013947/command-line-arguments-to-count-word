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
 initially make count = 0
### Step 3: 
open the content file using command line arguments.
### Step 4:  
by using for loop name the function as "line"
### Step 5: 
split the line using .split
### Step 6: 
split the line using .spli
## PROGRAM:
```python
'''
Program for getting the word count from the contents of a file using command line arguments
Developed by:JEECIKASRINA
RegisterNumber: 23013947

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![293365303-f791f097-f5f3-4ce8-9e42-a14034357925](https://github.com/Jeecikasrina23013947/command-line-arguments-to-count-word/assets/148515300/b5054fa6-965e-4275-8042-92404e50cb09)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
