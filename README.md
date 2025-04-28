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
 ![image](https://github.com/gokulkrishnan2005/19CS301-Module33/blob/main/vv.png)

### RESULT
Thus the python program for printing a list with odd numbers up to n, was implemented and executed successfully.

Exp.No:3(d)	TUPLES- A TUPLE WITH MULTIPLE 0F 9
### AIM
To write a python program to create the tuple by the multiples of 9 up to N and the print length of the tuple. Get the N value from the user..
### ALGORITHM

Start

Read an integer a from the user

Initialize an empty list b

Loop from i = 9 to a - 1:

If i % 9 == 0, then:

Append i to list b

Convert list b to a tuple

Find the length of the tuple using len(b) and store in c

Print the tuple

Print the length c with a message

End
### PROGRAM
```
a=int(input())
b=[]
for i in range(9,a):
    if i%9==0:
        b.append(i)
b=tuple(b)
c=len(b)
print(b)
print("Length of the tuple is",c)
```
### OUTPUT
![image](https://github.com/gokulkrishnan2005/19CS301-Module33/blob/main/CC.png)

### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 9 up to N, was implemented and executed successfully.

Exp.No:3(e)	SEB- ODD OR EVEN
### AIM
To write a python program to define a function to check the number 1781 is even or odd.

### ALGORITHM

Start

Read an integer a from the user

Check if a % 2 == 1:

If True, print "a is Odd number"

Else, print "a is not Odd number"

End

### PROGRAM
```
a=int(input())
if a%2==1:
    print(f"{a} is Odd number")
else:
    print(f"{a} is not Odd number")
```
### OUTPUT
 ![image](https://github.com/gokulkrishnan2005/19CS301-Module33/blob/main/XX.png)

### RESULT
Thus the python program to define a function to check the number 1781 is even or odd was implemented and executed successfully.









