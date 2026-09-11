
1. What type of programming language would you use?

I would use a High-level programming language because it is easy to understand, write, and maintain.


2. What is the difference between compiler and interpreter?

Compiler:
A compiler translates the entire program into machine code at once.

Interpreter:
An interpreter translates and executes the program line by line.


3. Role of Source code, Object code, and Executable file

Source Code:
The original code written by the programmer in a programming language.

Object Code:
The machine-level code generated from the source code by a compiler.

Executable File:
A file that can be directly executed by the computer to run the program.


4. SDLC Phases and what we do in each phase

1. Planning:
Identify the project goals, scope, time, and resources.

2. Requirement Analysis:
Collect and understand the user's requirements.

3. Design:
Design the system structure, database, user interface, and architecture.

4. Development:
Write the actual program/code.

5. Testing:
Test the software and find and fix errors or bugs.

6. Deployment:
Release the completed software for users.

7. Maintenance:
Monitor the software, fix issues, and add improvements or updates.


5. Program to find the sum of digits until it becomes a single digit

num = int(input("Enter a number: "))

while num >= 10:
    total = 0
    while num > 0:
        total += num % 10
        num //= 10
    num = total

print("Single digit sum:", num)


6. Program to print first n Fibonacci numbers using recursion

def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

n = int(input("Enter n: "))

for i in range(n):
    print(fibonacci(i), end=" ")
