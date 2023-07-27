# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First, create a file and upload it in the google drive

### Step 2: 
 Next, Mount the google drive by clicking allow access.
### Step 3: 
Then, open the file by copying and pasting the file path in the appropriate position.
### Step 4:  
Then count the number of words by using the split keyword
### Step 5: 
Finally, print the number of words.
### Step 6: 
End of the program.

## PROGRAM:
```
#Program to for getting the word count from a text
#Developed by: Hari Prasath. P
#Register no: 23005079
from google.colab import drive
drive.mount('/content/drive')

f = open('/content/drive/MyDrive/JK','r')
b = f.read()
d = 0
c = b.split(' ')
for i in c:
  d = d+1
print('The number of words: ',d)
```
### OUTPUT:
![output](/Screenshot%20from%202023-07-27%2017-04-14.png)


## RESULT:
Thus the program is written to find the word count from a text.
