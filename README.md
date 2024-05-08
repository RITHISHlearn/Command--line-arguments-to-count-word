# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.

### Step 2:
Create a file pointer and open the file which is passed in command line.

### Step 3:
Initialize word count as zero.

### Step 4:
For each line in file, split it into words and find number of the words in every line.

### Step 5:
Sum the number of words in each line.

### Step 6:
Display the total words in the file.

### Step 7:
Close the file pointer and end the program
 
## PROGRAM:

```
Developed by: RITHISH P
Register no: 212223230173
import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```

### OUTPUT:

![Screenshot 2024-05-08 214951](https://github.com/RITHISHlearn/Command--line-arguments-to-count-word/assets/145446645/58a014c3-19cf-4b5c-9c8c-3ab2bc95a1cc)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
