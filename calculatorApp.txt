# calculator.py

from microbit import *

while True:
    text = input("Enter first integer a: ")
    a = int(text)
    op = input("Enter operation + - * /: ")
    text = input("Enter second integer b: ")
    b = int(text)
    
    if op == "+":
        c = a + b
    elif op == "-":
        c = a - b
    elif op == "*":
        c = a * b
    elif op == "/":
        c = a / b
    
    print("a", op, "b = ", c)
    print(" ")