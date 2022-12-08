# Challenges To Do
(**ctd** for short)

The highlight of this CTD is:
- writing repetitive code in functions and in other files to import it later
- error handling and never letting the program error out
- using python 3.9 or later in VScode

If the code does not meet our standards, it would not be accepted and must be redone.

## Challenges
---

### RobEnDB

create a database using python dictionaries to store names, birthdays and ages of people, then retrieve or delete entries whenever the user wants to.

- Should be a continuously running program in a loop until the user exits
- give the user the option to input or read entries to/from the database
- take in input in the same line not in repeating input lines
- create a function that would calculate the age of the entry based on their birthday, use string manipulation to get the necessary data from the input string of (username, date)
- the age calculation should be dynamic (to be correct even if the current year changes, Hint: using the datetime library)
- write any repeating code in functions in another file then importing said file in the main file
- capitalize the first letter of each name in an entry
- use any approach for the database (create a list, write to a file or even upload to the cloud for all i care)
- the program should NEVER give out an error under any circumstances

_example:_
```
> what do you want to do: input
> input your entry: omar melegy, 22/9/2000
> successfully entered: Omar Melegy, 22 years old

> what do you want to do: input
> input your entry: suzy adel, 19/4/2003
> successfully entered: Suzy Adel, 19 years old

> what do you want to do: input
> input your entry: amr maghraby, 9/2/2004
> successfully entered: Amr Maghraby, 18 years old

> what do you want to do: read
> List of entries:
> Omar Melegy, 22 years old
> Suzy Adel, 19 years old
> Amr Maghraby, 18 years old

> what do you want to do: exit
> goodbye
```

---
Roben's Software & AI team 