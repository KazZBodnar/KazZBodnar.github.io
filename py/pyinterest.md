# PyInterest
A quarterly interest calculator
```py
from colorama import Fore
print(Fore.CYAN + "Python Quarterly Interest Calculator")
q0 = int(input(Fore.WHITE + "What is your starting amount (USD)? "))
cent = float(input("What is the interest rate (percent out of 1, for example, 3% would be 0.03, 10% would be 0.1)? "))
q = 1+cent
q1 = (q*q0)
print("You have", Fore.YELLOW + str(round(q1, 2)), Fore.WHITE + "dollars.")
add2 = float(input("How much cash (USD) do you want to add for the second quarter? "))
q2 = (q*q1)+add2
print("You have", Fore.YELLOW + str(round(q2, 2)), Fore.WHITE + "dollars.")
add3 = float(input("How much cash (USD) do you want to add for the third quarter? "))
q3 = (q*q2)+add3
print("You have", Fore.YELLOW + str(round(q3, 2)), Fore.WHITE + "dollars.")
add4 = float(input("How much cash (USD) do you want to add for the fourth quarter? "))
q4 = (q*q3)+add4
print("You have", Fore.YELLOW + str(round(q4, 2)), Fore.WHITE + "dollars.")
print("Final result:", Fore.GREEN + str(round(q4, 2)))
```
## How to run
`git clone https://github.com/kazzbodnar/pyinterest`

`cd pyinterest`

`python main.py`

### OR

[Click me](http://pyinterest.kazzbodnar.repl.run/)
