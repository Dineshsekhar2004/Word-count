# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Open the file in read mode and handle it in test mood.

### Step 2: Read the text using read() function.
 
### Step 3: Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4:  The length of the split list should equal the numbers of words in the test file.

### Step 5: You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: End the program.

## PROGRAM:
```
Program to count the words in a file
Reg No:212222230033
Name:S.Dinesh
"""
fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
for line in f:
words=line.split()
OUTPUT:
RESULT:
Thus the program is written to find the word count from a text.
num_words+=len(words)
print('Number of words:',num_words)
```
### OUTPUT:
![yy Screenshot from 2023-06-10 12-03-19](https://github.com/Dineshsekhar2004/Word-count/assets/119405916/29d6aa64-0b0e-46b4-be1b-c6aaca1f6bc2)




## RESULT:
Thus the program is written to find the word count from a text.
