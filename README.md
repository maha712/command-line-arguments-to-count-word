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

 Pass the filename as the first argument after the name of script. Open the file as sys.argv
 
### Step 3: 

Read the file using read() method.

### Step 4:  

Use split() method to split the file content into words.

### Step 5: 

Use len() to find the total words.

### Step 6:

 Run the program to determine the number of words in the file created.

## PROGRAM:

Developed by:  Mahalakshmi.k

Register Number: 22009204


import sys

fp= open(sys.argv[1])

data=fp.read()

words=data.split()

print("Total Words:",len(words))


### OUTPUT:

![command line arguments](https://github.com/maha712/command-line-arguments-to-count-word/assets/121156360/217959bc-4e57-40ba-9997-647c8031fee3)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
