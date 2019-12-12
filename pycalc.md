# PyCalc
### A simple python calculator (WIP)
This is a simple and easy-to-use calculator written in Python 3 (work in progress!).

## Source Code
```
help = input("PythonCalc V 1.3; Say 'help' for available commands, and 'ready' to start the calculator. ")
if help== "help" or "Help":
  print("Signs: '+', '-', '*', '/', '^2', 'sqrt', '^3', '!', 'power'. ")
  sign = input("What operation should I use? ")
  if sign== "+":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1+num2)
  elif sign== "-":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1-num2)
  elif sign== "*":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1*num2)
  elif sign== "/":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1/num2)
  elif sign== "^2":
    num1 = int(input("What is the number you wish to be squared? "))
    print("Processing...")
    print (num1**2)
  elif sign== "^3":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1**3)
  elif sign== "power":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1**num2)
  elif sign== "sqrt":
    num1 = int(input("What is the number you seek the square root of? "))
    print("Processing...")
    print (sqrt(num1))
  elif sign== "!":
    num1 = int(input("What is the number you seek the factorial of? "))
    print("Processing...")
    print (factorial(num1))
  else:
    print("I am sorry, but I am unable to process your request.")
else:
  sign = input("What operation should I use? ")
  if sign== "+":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1+num2)
  elif sign== "-":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1-num2)
  elif sign== "*":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1*num2)
  elif sign== "/":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1/num2)
  elif sign== "^2":
    num1 = int(input("What is the number you wish to be squared? "))
    print("Processing...")
    print (num1**2)
  elif sign== "^3":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1**3)
  elif sign== "power":
    num1 = int(input("What is the first number? "))
    num2 = int(input("What is the second number? "))
    print("Processing...")
    print (num1**num2)
  elif sign== "sqrt":
    num1 = int(input("What is the number you seek the square root of? "))
    print("Processing...")
    print (sqrt(num1))
  elif sign== "!":
    num1 = int(input("What is the number you seek the factorial of? "))
    print("Processing...")
    print (factorial(num1))
  else:
    print("I am sorry, but I am unable to process your request.")
```
## How to Run this Program
