```py

import random
import time
import os


def clear():
    os.system('clear')


def sleep():
    time.sleep(1.5)


def slep(sleeptime):
    time.sleep(sleeptime)

def enter():
    sleep()
    print()
    enter = input('press ENTER to continue')
    clear()


def letter(msg, howlongyougonnasleep):
    for i in range(len(msg)):
        print(msg[i], end='')
        time.sleep(howlongyougonnasleep)
    print()


```

```py
print("You come back to ISAK.")
lastchoice = int(input('''1. Meet your roommate
2. Go to your room
3. Meet with RA
4. Meet the house-mentor
'''))
clear()
if lastchoice == 1:
    print("Alarm too loud.")
    enter()
    letter("SLEEP DEPRIVED", 1)
    quit()
if lastchoice == 2:
    print("Too smelly.")
    enter()
    letter("LOST YOUR SENSES", 1)
    quit()
if lastchoice == 3:
    print("Stop and Clean.")
    enter()
    letter("DUST ALLERGY", 1)
    quit()
if lastchoice == 4:
    print("COC for not watching your dishes.")
    enter()
    letter("EXPELLED", 1)
    enter()
    letter("CONGRATS!!! YOU SURVIVE ISAK.", 0.7)
    enter()
```
