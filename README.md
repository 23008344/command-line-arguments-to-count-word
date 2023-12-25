# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
start the program
### Step 2: 
open the file
### Step 3: 
find the command line argument to count word
### Step 4:  
end the program


## PROGRAM:
```
'''
Developed by : VARNIKA.P
Registered number : 23008344
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))

```
### OUTPUT:

![Alt text](<Screenshot 2023-12-25 184446.png>)
![Alt text](<Screenshot 2023-12-25 184502.png>)
![Alt text](<Screenshot 2023-12-25 184511.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
