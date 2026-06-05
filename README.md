# Ex 1:Conditional Statements in Python: Even or Odd Checker

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
num = int(input())
if num%2==0:
    print("EVEN")
else:
    print("ODD")
```

## Output
<img width="128" height="67" alt="image" src="https://github.com/user-attachments/assets/ed619d84-27c3-40f8-96c1-de486cc1caec" />

## Result
Thus the Python Program for determining whether the given number is odd or even has been executed successfully and the output has been verified.




# Ex 2:Datatypes-Boolean Expression Evaluation in Python

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
```py
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```

## Output
<img width="228" height="110" alt="image" src="https://github.com/user-attachments/assets/aebfe709-cd02-4d75-bd77-efc2983bdb32" />

## Result
Thus the given Python program has been executed successfully and the output has been verified.




# Ex 3:Datatypes-Character Literal in Python

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
<img width="165" height="66" alt="image" src="https://github.com/user-attachments/assets/8b62c7c9-d629-4103-bb48-1c2545991645" />

## Result
Thus the given Python Program has been exceuted successfully and the output has been verified.




# Ex 4:🧮 Datatypes-Complex Number Creation in Python

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
```py
a = int(input())
b = int(input())

x = complex(a, b)

print(x)
print(x.real)
print(x.imag)
```

## Output
<img width="173" height="128" alt="image" src="https://github.com/user-attachments/assets/f576499b-1ef5-4510-ba00-96966b4904e6" />

## Result
Therefore the given Python Program has been executed succeefully and the output has been verified.




# Ex 5:Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```py
men_stepped_on_the_moon = input()
print("Men stepped on the moon:",men_stepped_on_the_moon)
```

## Output
<img width="361" height="69" alt="image" src="https://github.com/user-attachments/assets/693123cd-d156-466d-98b3-fbf529100407" />

## Result
Therfore the given Python program has been executed successfully and the output has been verified.
