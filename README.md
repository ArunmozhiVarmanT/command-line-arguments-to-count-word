# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name as input from the user.

### Step 2: 
Use for loop to count the number of words in the file.
 
 
### Step 3: 
Use split() to read the splitted words.We assume that words in a sentance are separted by a space character.


### Step 4:  
The length of the split list should equal the numbers of words in the test file. 


### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: 
End the program

## PROGRAM:
### Program to find the word count using command line arguments
### Developed by: ARUNMOZHI VARMAN T
### Register Number: 212223230022
```
fname=input("enter the file name")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![Screenshot 2024-01-03 202803](https://github.com/ArunmozhiVarmanT/command-line-arguments-to-count-word/assets/144870523/6984b094-32a7-4c1b-b238-6fbbba5409af)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
