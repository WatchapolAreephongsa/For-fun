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
