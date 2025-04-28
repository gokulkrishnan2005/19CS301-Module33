# 19CS301-Module33
Exp.No:3(a)	STRING- REMOVE A STRING
### AIM
To write a function "remove" that accepts a string and removes all the vowels from the string.
### ALGORITHM
Start

Define a string vowels = "aeiouAEIOU"

Read string str (passed to the function)

For each character i in str:

If i is in vowels:

Replace all occurrences of i in str with an empty string ""

Print the modified str (with vowels removed)

End

### PROGRAM
```
def remove(str):
    vowels="aeiouAEIOU"
    for i in str:
        if i in vowels:
            str=str.replace(i,"")
    print(str)
```
### OUTPUT
 ![image](https://github.com/gokulkrishnan2005/19CS301-Module33/blob/main/nn.png)

### RESULT
Thus the python program of function "remove" that accepts a string and removes all the vowels from the string has been implemented and executed successfully.


Exp.No:3(b)	REGEX- MATCHING USING REGEX

### AIM
To write a Python program that matches a word at the beginning of a string.
### ALGORITHM

Start

Read a string str from the user

Define a regex pattern: patterns = '^\W+'

Use re.search(patterns, text) to check if the string starts with non-word characters

If a match is found:

Return "Not matched!"

Else:

Return "Found a match!"

Print the result

End

### PROGRAM
```
import re
def text_match(text):
    patterns= '^\W+'
    if re.search(patterns,text):
        return("Not matched!")
    else:
        return('Found a match!')
str=input()
print(text_match(str))
        
```
### OUTPUT
 ![image](https://github.com/gokulkrishnan2005/19CS301-Module33/blob/main/bb.png)

### RESULT
Thus the python program for that matches a word at the beginning of a string was  implemented and executed successfully.

Exp.No:3(c)	LIST- ODD NUMBERS LIST

### AIM
To write a python function that accepts N and to create a list with odd numbers up to N.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer a.

Step 3:	 Create an empty list l.

Step 4:	In For Loop, Iterate through the numbers from 1 to a-1.For each number i, check if i is even: If i % 2 == 1, append i to the list l.

Step 5:	 Print the list l which contains all odd numbers from 1 to a-1.

Step 6:	 Terminate the program.
### PROGRAM
```
def createlist(a):
    l=[]
    for i in range(1,a):
        if (i%2==1):
            l.append(i)
    print(l)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/a21369b0-1967-4362-b91f-84bb82becbcd)

### RESULT
Thus the python program for printing a list with even numbers up to n, was implemented and executed successfully.

Exp.No:3(d)	TUPLES- A TUPLE WITH MULTIPLES OF 5
### AIM
To write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer N from the user.

Step 3:	 Define an empty tuple multiples_of_5.

Step 4:	 Loop through the numbers starting from 5, up to N-1 (not including N), with a step size of 5 For each value of i, add i to the tuple multiples_of_5.

Step 5:	 Return the multiples_of_5 tuple.

Step 6:	 print the resultant tuple.

Step 7:	 Terminate the program.
### PROGRAM
```
def create_tuple(N):
    multiples_of_5 = tuple(i for i in range(5, N, 5))
    return multiples_of_5
N = int(input())
result = create_tuple(N)
print(f"{result}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/a16820ca-d669-4520-b141-c4e0a836c910)


 
### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 5 up to n, was implemented and executed successfully.

Exp.No:3(e)	SEB- STRING SLICING
### AIM
To write a python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Take a slice of input_string starting from index 2 up to index 10.

Step 3:	 Reverse the substring.

Step 4:	 slice the reversed string, extracting every second character, starting from the first.

Step 5:	 Print the sliced string in the above step.

Step 6:	 Terminate the program.
### PROGRAM
```
def slice(input_string):
    substring = input_string[2:10:]
    reversed_substring = substring[::-1]
    print(f"The reversed string is '{reversed_substring[::2]}'")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/1c3e5d33-4525-44e9-93c4-3431af135a04)

### RESULT
Thus the python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string was implemented and executed successfully.









