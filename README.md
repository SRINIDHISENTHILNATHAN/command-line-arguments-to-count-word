# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import sys
### Step 2: 

Open file using commandline arguments.
### Step 3: 

Using for loop find the word count from the contents of a file.
### Step 4:  

Use len to count number of words.
### Step 5: 

Give print statement.
### Step 6: 

End the program.

## PROGRAM:
```
#Developed by:SRINIDHI SENTHIL
#Register num: 22001408
num_words=0
with open('shara.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words += len(word)
print('num of words={}'.format(num_words))   
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/121373170/214841475-57c10fcd-cef1-48e6-829c-38cc1413f0ad.png)

![image](https://user-images.githubusercontent.com/121373170/214841615-ba14f543-a24c-45cb-885d-86ded77a656b.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
