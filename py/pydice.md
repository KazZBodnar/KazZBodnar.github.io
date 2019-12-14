# PyDice
### A simple Python D&D dice roller
PyDice is a simple python D&D dice roller that generates psuedo-random integers to virtually "roll a die." 
It can be used simply for random purposes or for RPG games.

## How to use PyDice
1. Go to [OnlineGDB](https://onlinegdb.com) or a similar Python compiler.
2. Set the language to Python 3.
3. Select the filler text and paste in [PyDice's code](https://langlang.tech/py/pydice#code).
4. Hit *run*.

## Code
```
import random
print("DnD Virtual PyDice Roller")
rr = input("Commands: 'd4', 'd6', 'd8', 'd10', 'd12', 'd20', 'd100'. >")
if rr == "d4":
    rand = random.randint(1, 4)
    num = int(input("How many d4 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d6":
    rand = random.randint(1, 6)
    num = int(input("How many d6 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print(" __________")
    print("|\ o       \\")
    print("| \_______o\u0332_\\")
    print("| | o       |")
    print("|o|    o    |")
    print("\ |       o |")
    print(" \|_________|")
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d8":
    rand = random.randint(1, 8)
    num = int(input("How many d8 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d10":
    rand = random.randint(1, 10)
    num = int(input("How many d10 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d12":
    rand = random.randint(1, 12)
    num = int(input("How many d12 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d20":
    rand = random.randint(1, 20)
    num = int(input("How many d20 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
elif rr == "d100":
    rand = random.randint(1, 100)
    num = int(input("How many d100 do you want to roll? >"))
    add = int(input("How many should I add to the roll? >"))
    print("Rolling...")
    print((rand*num)+add)
else:
    print("I am sorry, but I am unable to process your request. You might have made a typo.")
```
