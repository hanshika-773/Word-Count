# Date:
# Ex.No 09: Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Start the program.

### Step 2: Create a file story.txt in anaconda navigator.
 
### Step 3: Write a program to count the number of words in a text file.

### Step 4:  Run the program.

### Step 5: Print the output.

### Step 6: End the program.

## PROGRAM:
```
##DEVELOPED BY: Hanshika Varthini R
##REFERENCE NUMBER: 212223240046
num_words =0
file1 = open("my_file.txt", "r")
with open('my_file.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:

![Screenshot 2024-10-16 161644](https://github.com/user-attachments/assets/976b6a27-70b3-4200-ac79-8feb9de2f5d0)


## RESULT:
Thus the program is written to find the word count from a text.
