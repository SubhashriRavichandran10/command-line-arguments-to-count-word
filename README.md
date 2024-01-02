# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys

## Step 2:
Then decleare count is equal to 0

## Step 3:
Read the file with python file name

## Step 4:
Splitting the word

## Step 5:
After splitting count the number of words in the line

## Step 6:
In last statement give the print statement

## PROGRAM:
```
'''
#Program to copy the file.
#Developed by:SUBHASHRI R
#RegisterNumber:212223230219

import sys
count=0
with open("text.txt",'r') as f:
    for line in f:
         word=line.split()
         count+=len(word)
print("Word Count in File=",count)





```


### OUTPUT:



![Screenshot 2024-01-02 174158](https://github.com/SubhashriRavichandran10/command-line-arguments-to-count-word/assets/145743413/bb112840-eee5-48f7-bbb4-3952d2c2b2ca)

![Screenshot 2024-01-02 174208](https://github.com/SubhashriRavichandran10/command-line-arguments-to-count-word/assets/145743413/3a1f3890-c727-4447-9836-e7f3d908d9d3)

![Screenshot 2024-01-02 174223](https://github.com/SubhashriRavichandran10/command-line-arguments-to-count-word/assets/145743413/2e19adb1-40a0-4ec8-8be5-5c5aadea0231)




![Screenshot 2024-01-02 174233](https://github.com/SubhashriRavichandran10/command-line-arguments-to-count-word/assets/145743413/11999d7e-b8ca-4f05-8b48-5b3369232966)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
