# Markdown File
Click here to skip to the footnote. [^1]

## What's your name?
My name is **Antonio**

## Where are you from?
==*Italy*==

## List of my family members
1. Mum
2. Dad
3. Brother

| Family members | Name |
| - | - |
| Mum | Katarina |
| Dad | Mario |
| Brother | Luca |
## How many of you are in total?

    - 4

> My family lives in Italy
>> I'm studying in Australia



`code i'm working on `

![python](s-python.png)
```
import random
print("The Guessing Game") #name of the game
print('')
credit= 0 #starting points
start=input('press Enter to start')
for counter in range(1,50):
    generator=random.randrange(1,3) #generate a random number between 1 and 3
    credit= credit
    print(f"Initial credit: {credit}")
    guess = input("Guess the number between 1 and 3: ") 
    guess = int(guess)
    if guess == generator:
        print ("Congratulations, you won!")
        credit=credit+150
        print ("You gained +150 points!")
        print('')
    elif guess > generator:
        print(guess, "that is a great guess, but your number is too big")
        credit=credit-50
        print ("-50 points")
        print('')
        
    else:
        print("You almost got it.")
        credit=credit-50
        print ("-50 points")
        print('')
```


[^1]: Why did you skip, keep reading.

