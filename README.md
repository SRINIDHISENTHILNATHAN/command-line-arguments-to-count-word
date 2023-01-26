# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

To write a python program for getting the word count from a text file
### Step 2: 

 Open the required file by using the function "with"
### Step 3: 

Then use tha laptop to assign the i value in the file
### Step 4:  

Using split function to split the words
### Step 5: 

Finding the given length of the words by using len() function
### Step 6: 

Calling the function and Printing the number of words

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

![image](https://user-images.githubusercontent.com/121373170/214834184-83a01c71-7957-4210-a089-da45e0e73019.png)

![image](https://user-images.githubusercontent.com/121373170/214834288-ce48ec19-6209-4459-8b77-6fc8b29c4319.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
