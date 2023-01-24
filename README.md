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
Developed by: vikash s
RegisterNumber: 22008879
file = open("test.txt", "r") 
count=0 
for line in file:    
    words = line.split(" ");
    count  += len(words);  
print("Number of words present in given file: " + str(count));  
file.close();
### OUTPUT:
![Screenshot 2023-01-24 235937](https://user-images.githubusercontent.com/119433834/214377835-11f0c1c7-081f-4a29-872f-cb258e363bb9.png)


![Screenshot 2023-01-24 235920](https://user-images.githubusercontent.com/119433834/214377862-f02c524e-ac02-4c11-b3e2-4e93b9af90ae.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
