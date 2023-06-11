# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Open the file in read mode and handle it in test mood.

Step 2: Read the text using read() function.

Step 3: Split the text using space separator.We assume that words in a sentance are separted by a space character.

Step 4: The length of the split list should equal the numbers of words in the test file.

Step 5: You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

Step 6: End the program.
## PROGRAM:
```
Program to count the words in a file
Reg No:212222110039
Name:SANJAY T

fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('Number of words:',num_words)
```
### OUTPUT:
![244876392-c5872df2-adae-4c4b-9d9a-97c264c15ca9](https://github.com/sanjaythiyagarajan/Word-count/assets/119409242/3fd884ff-6fa4-43cc-9dd7-a2f6b701c6b3)
![244876411-e9a31af2-99b8-4cde-b8c8-9b250446fc7f](https://github.com/sanjaythiyagarajan/Word-count/assets/119409242/79cc9a50-9490-4596-a886-a69a842a7036)



## RESULT:
Thus the program is written to find the word count from a text.
