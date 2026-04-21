# PYTHON PROGRAMMING MODULE 1
NAME: THOLKAPPIYAN A
REGISTER NUMBER: 212224020058
Ex 01: Conditional Statements in Python: Even or Odd Checker
# Aim
To write a Python program to check whether the given number is even or odd using if...else statements.

# Algorithm
1.Get an input from the user.

2.Convert the input to an integer and store it in a variable a.

3.Use the modulo operator % to check if a % 2 == 0.

1.If true, print "EVEN".

2.Else, print "ODD".
4.End the program.

# Program
```
num = int(input())
if num%2==0:
    print("EVEN")
else:
    print("ODD")
```
# Output
<img width="489" height="326" alt="image" src="https://github.com/user-attachments/assets/467eab03-e349-4d8b-b5b8-877a4cf5c592" />

# Result
Thus the Python Program for determining whether the given number is odd or even has been executed successfully and the output has been verified.

# Ex 2:Datatypes-Boolean Expression Evaluation in Python
## Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

# Algorithm
1.Set variable a to the result of the expression 0 == True.

2.Set variable b to the result of the expression False == False.

3.Set variable c to the result of the expression True + True.

4.Set variable d to the result of the expression False + 9.

5.Print the value of a with the label "a is".

6.Print the value of b with the label "b is".

7.Print the value of c with the label "c:".

8.Print the value of d with the label "d:".

Program
'''
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
'''
Output
<img width="514" height="399" alt="544754064-9b6c40ef-4609-40c1-919b-29477e1d1ffe" src="https://github.com/user-attachments/assets/db5b8cf7-d1e2-4dec-aa83-3afee1f3f608" />

# Result
Thus the given Python program has been executed successfully and the output has been verified.

# EX 03: Datatypes-Character Literal in Python
## Aim
To write a Python program that prints the characters 'T' and 'a' using character literals.

# Algorithm
1.Print the character 'T'.

2.Print the character 'a'.

# Program
'''
print('T')
print('a')
```
Output
<img width="606" height="358" alt="544754149-c5f26176-38eb-4ad5-a0d8-adce03429c83" src="https://github.com/user-attachments/assets/db59c40e-43e3-4edb-90f6-07711cd24122" />


# Result
Thus the given Python Program has been exceuted successfully and the output has been verified.

# EX 04- Datatypes-Complex Number Creation in Python
## Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

# Algorithm
1.Read an integer input from the user and assign it to the variable a (real part).

2.Read another integer input from the user and assign it to the variable b (imaginary part).

3.Create a complex number x using the complex(a, b) function.

4.Print the complex number x.

5.Print the real part of x using x.real.

6.Print the imaginary part of x using x.imag.

# Program
'''
a = int(input())
b = int(input())

x = complex(a, b)

print(x)
print(x.real)
print(x.imag)
'''
# Output
https://private-user-images.githubusercontent.com/182344739/544754310-50af8c78-921a-4dbc-8a11-cc5d6969e2d9.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzY3NTU5MDksIm5iZiI6MTc3Njc1NTYwOSwicGF0aCI6Ii8xODIzNDQ3MzkvNTQ0NzU0MzEwLTUwYWY4Yzc4LTkyMWEtNGRiYy04YTExLWNjNWQ2OTY5ZTJkOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQyMVQwNzEzMjlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kMjQ5M2I3MTQyZDU3ZTdlNGMxYzBlMzk3MTBmYzRmMTdiMzE4YjQwNmRjMzQ5M2QxMWY3OTdhYmQzNzk4YmM1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.EMo9dJrIAlViQL_2u9GTCi9snTHx_yaA6zwl9sm3rxg
# Result
Therefore the given Python Program has been executed succeefully and the output has been verified.

# EX 05-Datatypes-Read and Print a String in Python
## Aim
To write a Python program to read a string from the user and then print it.

# Algorithm
1.Assign a variable named men_stepped_on_the_moon.

2.Use input() to read a string from the user and store it in the variable.

3.Print the value stored in the variable.

# Program
'''
men_stepped_on_the_moon = input()
print(men_stepped_on_the_moon)
'''
# Output
https://private-user-images.githubusercontent.com/182344739/544754615-9ffdc6ef-5703-46d3-8e24-3acfc6fb9808.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzY3NTU5MDksIm5iZiI6MTc3Njc1NTYwOSwicGF0aCI6Ii8xODIzNDQ3MzkvNTQ0NzU0NjE1LTlmZmRjNmVmLTU3MDMtNDZkMy04ZTI0LTNhY2ZjNmZiOTgwOC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQyMVQwNzEzMjlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iMDlkNjU5M2I5NWRmNDVhZDFkYmExNWZjZjk4MmJmY2IxNmQzNTFjZWU5MDMwMjYyMTFhN2Q5YWZkYWRkMTk0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.wEV8WTzc2zGaski3wZ6aGD0wDN7ZgbezUrGrGGm0RQw
# Result
Therfore the given Python program has been executed successfully and the output has been verified.
