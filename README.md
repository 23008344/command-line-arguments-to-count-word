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

![image](https://github.com/23008344/command-line-arguments-to-count-word/assets/145742655/bcd3e9c0-2044-4c01-af0f-091b7658cc6b)
![image](https://github.com/23008344/command-line-arguments-to-count-word/assets/145742655/b7900c14-cf81-435c-85d5-b9f148766435)
![image](https://github.com/23008344/command-line-arguments-to-count-word/assets/145742655/9b8f4bd2-ee30-4d6b-a251-f1a3a1a98c94)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
