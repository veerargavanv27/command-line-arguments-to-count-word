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
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1] 
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: VEERARAGAVAN V
# Register number: 2122232320237
import sys
fp= open(sys.argv[0])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![Screenshot 2023-12-31 133459](https://github.com/veerargavanv27/command-line-arguments-to-count-word/assets/138955645/61995a48-c4df-463a-af45-80101567a59f)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
