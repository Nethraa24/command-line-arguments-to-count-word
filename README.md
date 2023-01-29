# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Open file using open().
### Step 3: 
Use for loop
### Step 4:  
Use len to count number of words.
### Step 5: 
Give print.
### Step 6: 
End of the program
## PROGRAM:
```python
##ProgramDeveloped by:J.Nethraa
  Reference no.: 22006789
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![image](https://user-images.githubusercontent.com/121215786/215333518-635ba738-6079-4534-b487-7c2b562f2944.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
