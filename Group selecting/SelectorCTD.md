# Challenges To Do
(**ctd** for short)
_This is a special CTD for helping select a group for each members_

If you can't do any of the CTD's it's totally ok just send a message saying so to the person collecting the results or finish the survey by stating that you are in group 0 and don't upload a code file.
However if you attempt the questions please answer each problem in a separate function and upload only one file containing the three problems.


## Challenges
---
### 0.1 - can you math?
Take a number N from the user ranging from 1 to 942 and don't allow any less or any more, use this number to count how many '1's would appear while counting from 1 to the N like so

_example:_
user input: 13
```
input number N: 13
from 1 to 13 the number '1' shows up : 5 times
```

_hint: be ware of user input and don't allow the user to destroy the program with unsafe input_

### 1.2 - 8 of game
Make a bag that the user can use to store numbers in and remove numbers from whenever he wants, the user can choose what number to remove from the bag or to add a number to the bag and display the result of contents in the bag after each interaction with the user. the bag must contain more than 5 numbers at all times and does not allow user to remove from it if it will have less than 5. you can start the list with random numbers in code at the start.
- make list in code called **_bag_** which contains at least 5 numbers **at all times**
- check that user input is clean 
- print out the contents of the list **bag** in the beginning and after each update
- give the user the ability to enter numbers into the bag after saying _enter_
- give the user the ability to remove numbers from the bag after saying _remove_
- don't let the bag have less than 5 numbers at any time

_example:_
this is an example scenario for user input against the desired program behavior
```
program output : [6, 22, 10, 999, 76, 43]
user : remove
user : 10
program output : [6, 22, 999, 76, 43]
user : remove
program output : cannot remove, bag is at minimum capacity
program output : [6, 22, 999, 76, 43]
user : enter
user : 30
program output : [6, 22, 999, 76, 43, 30]
user : enter
user : 420
program output : [6, 22, 999, 76, 43, 30, 420]
```

### 2.3 - Show me
Use a GUI in python to make a window that has 3 buttons which when pressed either shows the user a picture of a car, a person and a dog 
- the program should have only one window
- minimum of 3 buttons
- text in buttons is: "Show Car", "Show Person", "Show Dog" respectively
- you can show the images from the internet or save them in the same folder (no need to upload them when submitting)

---
Roben's Software & AI team 