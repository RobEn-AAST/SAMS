# Challenges To Do - Special edition
(**ctd** for short)

## Challenges
---
### 1 - Randomness is the enemy
It is very important to take some time to read the question twice.
This challange takes on average 2.5 hours to complete.

You are supposed to implement a game, where one of the players is the computer and the other is a human. We are having three bags 1,2,3. Each player takes turn and removes between 1 and 5 objects from one of the three bags. The player who removes the last object(s) wins the game. Here are the rules:

- Each bag contains 10 objects in the beginning of the game.
- The furst turn is for the human then comes the computer's turn.
- The player can remove object(s) from a single bag at a time.
- The player can not choose to remove 0 object(s), at least one object should be removed each turn.
- The number of objects to be removed by the computer or the human should be between 1 and 5 (inclusive).
- The player has to enter the bag first (1 or 2 or 3) and then the number of object(s) to be removed from the bag.
- You have also to check whether the human's input is valid. That is it a valid bag number (1 to 3)? is it a valid number of objects (1 to 5)? also are there enough objects in the bag left to remove? If any of these conditions are not met, then the user should be asked for input again. (bag and number of objects) .
- Note that you need to make sure that the computer's selection is valid too, the computer's turn should always guess a correct bag number, number of objects and for the bag to contain at least that number of objects when selected. _(Hint: Use the random library in python)_.
- Once the computer has removed objects from the bag the game should tell the user how many objects where removed from what bag, then it's the human's turn to start removing again.
- The game ends when all three bags are empty.
- The player who was the last to remove objects from any bag wins the game (computer or human).
- The game should tell you the user which player won by displaying any picture that describes the winner. _(Hint: use the Opencv library to load the image in code and display it when needed, search youtube for loading images with opencv or read tutorials on how to install opencv using pip install)_.

_examples:_
example input and output from the game. 
```bash
10 - 10 - 10
select a bag: 3
select number of objects: 4
you removed 4 from bag 3
10 - 10 - 6
the computer removed 2 from bag 3
---------------------------------------------------
10 - 10 - 4
select a bag: 5
select number of objects: 3
please select a correct number.

select a bag: 3
select number of objects: 4
you removed 4 from bag 3
10 - 10 - 0
the computer removed 4 from bag 2
---------------------------------------------------
10 - 6 - 0
select a bag: 2
select number of objects: 5
you removed 5 from bag 2
10 - 1 - 0
computer removed 2 from bag 1
---------------------------------------------------
8 - 1 - 0
select a bag: 1
select number of objects: 5
you removed 5 from bag 1
3 - 1 - 0
computer removed 3 from bag 1
---------------------------------------------------
0 - 1 - 0
select a bag: 2
select number of objects: 1
you removed 1 from bag 1
0 - 0 - 0
Congratulations, the user won!!!
```
---
Roben's AI team 