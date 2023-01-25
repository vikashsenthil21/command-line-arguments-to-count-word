# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
import sys

Step 2:
Assign a variable count =0

Step 3:
open a file in read mode

Step 4:
iterate a variable (lines) through the file

Step 5:
Assign a variable words = lines.split ()

Step 6:
Now iterate through the variable and increase the count: and print the count vi

## PROGRAM:
```
#program is developed: VIKASH S
# REF.NO: 22008879
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: VIKASH S")
print("word count in file = ",count)
```
### OUTPUT:

![WhatsApp Image 2023-01-25 at 20 39 00](https://user-images.githubusercontent.com/119433834/214641923-92fab328-9e27-4813-af15-b86937238a1e.jpg)


![WhatsApp Image 2023-01-25 at 20 01 35](https://user-images.githubusercontent.com/119433834/214641943-c9c53afa-04f9-4816-947d-39f44adfaf0f.jpg)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
