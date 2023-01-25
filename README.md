# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

create a file and add some content to it

### Step 2: 

open file using with keyboard/built-in function in read mode
 
### Step 3: 

use read() to read the contents of the file.

### Step 4:  

split the lines using split().

### Step 5: 

iterate the list and increament the count.

### Step 6: 

print the output

## PROGRAM:
#program to find number of words
#developed by:s.thirisha
#register number: 22001920
```
fname = input('enter file name: ')
num_words = 0
with open(fname, 'r') as f:
for line in f:
words = line.split()
num_words += len(words)
print('number of words: ',num_words)
```

### OUTPUT:
![Screenshot_20230125_161831](https://user-images.githubusercontent.com/120380280/214619989-29303e4f-fe07-4143-81a9-67c4e985d53b.png)

## RESULT:
Thus the program is written to find the word count from a text.
