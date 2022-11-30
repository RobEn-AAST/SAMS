# Challenges To Do
(**ctd** for short)


**The highlight of this CTD is to try to write the solution as pythonic as possible, research how can you make your initial solution better.**

## Challenges
---

### Life is randomness

You are making a collection of games.
Make a program that takes input from user to choose which simple game to play, then plays that game and loop over to let him choose again, unless the user enters 'exit' then the program may exit.

- take input as number to specify which game to play then loop over until the user types 'exit'
- make sure to handle the input and any error that might occur (never trust the user)
- don't repeat yourself: reuse code and don't repeat any segment again
- include 3 games: coin toss, random number generator and a choice maker that chooses for you randomly
- as before, keep your code the cleanest you can

**Hint**: RTFD is a common abbreviation in software development that stands for Read The Fucking Docs, as you should in fact read the documentation before using a library, like the random library for instance.

_game 1 example:_
```
Choose the game you want to start or enter 'exit' to exit:
1 - Toss a coin
2 - Get a random number
3 - Random choice
Your choice : 1

> A coin was tossed and landed on: Heads

Choose the game you want to start or enter 'exit' to exit:
1 - Toss a coin
2 - Get a random number
3 - Random choice
Your choice : exit
GoodBye
```
_game 2 example:_
```
Choose the game you want to start or enter 'exit' to exit:
1 - Toss a coin
2 - Get a random number
3 - Random choice
Your choice : 2

> choose the range of numbers: 0,99
> A random number between 0 and 99 is: 47

Choose the game you want to start or enter 'exit' to exit:
1 - Toss a coin
2 - Get a random number
3 - Random choice
Your choice : exit
GoodBye
```
- the range of numbers should be taken in the same line separated by a comma

_game 3 example:_
```
Choose the game you want to start or enter 'exit' to exit:
1 - Toss a coin
2 - Get a random number
3 - Random choice
Your choice : 3

> Enter list of choices: Mcdonalds KFC Kansas Willis Hardees PapaJohns 
> Your random choice is: PapaJohns

Choose the game you want to start or enter 'exit' to exit:
1 - Toss a coin
2 - Get a random number
3 - Random choice
Your choice : exit
GoodBye
```
Hint: Papa Johns is always the best (half smokey\half ranch)

---
Roben's Software & AI team 