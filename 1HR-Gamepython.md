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


Final code
```py

import random
import time
import os


def clear():
    os.system('clear')


def slep(sleeptime):
    time.sleep(sleeptime)

def enter():
    slep(1.5)
    print()
    enter = input('press ENTER to continue')
    clear()



def letter(msg, howlongyougonnasleep):
    for i in range(len(msg)):
        print(msg[i], end='')
        time.sleep(howlongyougonnasleep)
    print()

#Isak wakeup
print("U Wake up in ISAK. WHere do u wanna go")
print("answer your Option by number")
choice1 = int(input('''1.go to class
2.shower
3.go to Breakfast
4.jump down the bed
5.Mindfullness practice
6.go back to sleep
7.Change to ESS
8.Quit IB
'''))

clear()
if choice1 == 1:
    print("you die because of [stress]")
    quit()

if choice1 == 2:
    print("you die because of [water is too cold]")
    quit()
if choice1 == 3:
    print("you die because of [food too dry]")
    quit()
if choice1 == 4:
    print("you die because of [Break your ankle]")
    quit()
if choice1 == 5:
    print("you die because of [boredom]")
    quit()
if choice1 == 6:
    print("you are [late to class]")
    enter()
    print("you die because of [disappointment]")
    quit()
if choice1 == 7:
    print("you chose ESS!")
    enter()
    letter("FAILURE",1)
    quit()
if choice1 == 8:
    print("you survive!")
    enter()

#
print("your first period is PE. You have to run")
choice2 = int(input('''what do you do?
1.go to nurse
2.cheat running
3.run
4.OED
'''))

if choice2 == 1:
    print("you die because of [nurse say you are too weak]")
    enter()
    letter("EMOTIONAL DAMAGE",1)
    quit()
if choice2 == 2:
    print("Ms.Flo is following u")
    enter()
    letter("ANXIETY",1)
    quit()
if choice2 == 3:
    print("You die from tiredness")
    quit()
if choice2 == 4:
    print("you go to OED trip")
    print("You survive")
    enter()

#
print("What do u want to do for OED")
choice3 = int(input('''
1.hike
2.ski
3.pokemon
4.cycling
'''))
if choice3 == 1:
    print(" [asama shaking]")
    enter()
    letter("SHOCK",1)
    quit()

if choice3 == 2:
    print("[ski too big]")
    enter()
    letter("UNCOMFORTABLE",1)
    quit()

if choice3 == 3:
    print("[pokemon hike]")
    enter()
    letter("SCARED OF HEIGHT",1)
    quit()

if choice3 == 4:
    print("[cycling to combini]")
    enter()
    letter("SURVIVE",1)
    enter()

#
print("You went to the combini")
choice4 = int(input('''
what would u do
1. buy kinoko no yama
2.buy instant noodle
3.talk to staff
4.Buy a sock
'''))

if choice4 == 1:
    print("[you bought kinokono yama]")
    enter()
    letter("FOOD POISONING",1)
    quit()

if choice4 == 2:
    print("[you bought INSTANT NOODLE]")
    enter()
    letter("TOO UNHEALTHY",1)
    quit()

if choice4 == 3:
    print("[you talked to the staff]")
    enter()
    letter("LANGUAGE BARRIER",1)
    quit()

if choice4 == 4:
    print("[you bought a sock]")
    enter()
    letter("SURVIVE",1)
    enter()

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
