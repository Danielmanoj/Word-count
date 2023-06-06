# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open then required file by using the function"with"
### Step 2: 
 Using split function to split the words.
### Step 3: 
Finding the length of the words by using len() function.
### Step 4:  
Calling the function and printing the number of words.

## PROGRAM:
```
#Developed by: MANOJ G
#Register No: 212222240060
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
for line in f:
words=line.split()
wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
![241972667-fd0eed3b-07c7-4110-a5f9-09587035db58](https://github.com/Danielmanoj/Word-count/assets/69635071/d9bb66ec-aa26-4c4e-819e-7e13afe90202)



## RESULT:
Thus the program is written to find the word count from a text.
