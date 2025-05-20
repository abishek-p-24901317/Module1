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
```
num=int(input())
if(num%2==0):
      print("Even")
else:
    print("Odd")
```
## Output
![odd even](https://github.com/user-attachments/assets/7fa471f7-323c-42f4-8c22-b8d0e553be2e)

## Result
Thus the Program has been successfully executed

---

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
```
a = (0 == True)
b = (False== False)
c = True + True
d = False + 9
print('a is',a)
print('b is',b)
print('c:',c)
print('d:',d)
```
## Output:
![boolean](https://github.com/user-attachments/assets/f74b7d93-faf9-487b-ad84-f2d61fbc4fc0)

## Result
Thus the program has been successfully executed

---
# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
t='T'
v='a'
print(t)
print(v)
```
## Output
![char](https://github.com/user-attachments/assets/50defecf-688f-4968-945a-0741a5e00938)

## Result
Thus the program has been successfully executed

---
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
```
x=int(input())
y=int(input())
x=complex(x,y)
print(x)
print(x.real)
print(x.imag)
```
## Output
![complex](https://github.com/user-attachments/assets/cbdb9a88-c687-4a1d-869c-797896e7afa1)

## Result
Thus the program has been successfully executed

---
# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```
## Output
![step](https://github.com/user-attachments/assets/9b07de24-8dd8-4646-8e29-de78fd231ff4)

## Result
Thus the program has been successfully executed
