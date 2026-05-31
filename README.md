# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```py
num = int(input("Enter a number: "))
if num % 2 == 0:
    print(f"{num} is even.")
else:
    print(f"{num} is odd.")
```
## Output
<img width="981" height="251" alt="Screenshot 2025-10-20 124723" src="https://github.com/user-attachments/assets/f33ae468-2ddc-44ad-b3e8-1122168561a9" />


## Result
Successfully wrote a Python program to check whether the given number is even or odd using if...else statements.




# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
Add Code here
```py
# Program to evaluate boolean and arithmetic expressions
a = (0 == True)        
b = (False == False) 
c = (True == False)    
d = (False + 9)         

print("a is", a)
print("b is", b)
print("c is", c)
print("d is", d)
```

## Output
<img width="1046" height="249" alt="Screenshot 2025-10-20 125702" src="https://github.com/user-attachments/assets/b0d813cc-d375-499a-a998-45dd86cc0fad" />

## Result
Successfully wrote a python  program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.


# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```py
print('T')
print('a')
```
## Output
<img width="1042" height="166" alt="Screenshot 2025-10-20 130227" src="https://github.com/user-attachments/assets/85a8d45e-130b-464c-a9b3-bd5f279830dd" />

## Result
Successfully wrote a Python program that prints the characters `'T'` and `'a'` using character literals.


# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
Add Code Here
```py
# Program to create and display a complex number

# Step 1: Read real and imaginary parts from user
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))

# Step 2: Create complex number
x = complex(a, b)

# Step 3: Display results
print("The complex number is:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```
## Output
<img width="895" height="127" alt="Screenshot 2025-10-20 130641" src="https://github.com/user-attachments/assets/0972d706-3d99-4b07-9449-a48cdbf277c0" />

## Result
Successfully wrote a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.


# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```py
# Program to read and print a string

# Step 1: Read input from the user
men_stepped_on_the_moon = input("Enter a string: ")

# Step 2: Print the string
print("You entered:", men_stepped_on_the_moon)
```

## Output
<img width="899" height="68" alt="Screenshot 2025-10-20 131019" src="https://github.com/user-attachments/assets/dd5cf969-beee-4efa-8ffc-16ea2df5d6a2" />

## Result
Successfully wrote a Python program to read a string from the user and then print it.
