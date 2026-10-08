# Python Week 3 Assessed Workshop

You may use the following cheat sheets if you need to look up any Python commands.

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week1_cheatsheet.md

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week2_cheatsheet.md

You should not need to use any other websites. 

---

## TASKS


### Part 1: 

Work in a code file called `workshop3b_part1.py` and start with the following code:

```python
print("Part 1:")
```

We are going to store some information about a pet dog called `gnasher`. 

**i)** Complete the comment line to write your full name into the file

**ii)** Write code to store set up the following variables using appropriate data types (i.e. do not store the numbers as strings):

| variable name | stored data |
|---------------|-------------|
| dog           | gnasher     |
| owner         | dennis      |
| age_year      | 4           |
| h_cm          | 51.2        |

Using the variables write Python code to:

**iii)** Display the name of the owner, in title case (first letter capitalised).

**iv)** Display the name of the dog in upper case (all letters capitalised).

**v)** Display the dogs height in inches (found by dividing its height in cm by 2.54)

**vi)** Use an f-string to display the following message:

`The dog called ______ is _______ years old.`

Where the correct values are inserted in to the sentence usign the stored variables. You can leave the name in lowerr-case.

Run the code file in the terminal using command:

```
python workshop3b_part1.py
```

It should produce exactly 5 lines of output, with first line `Part 1:`, followed by lines that show the output created from the instructions above.

### Part 2: 

Work in a code file called `workshop3b_part2.py`

This should start with the following lines of code:

```python
print("Part 2:")
people = ['fred', 'greta', 'hetty' ]
```

Add four lines of code that do the following:

**i)** Write code to add another entry `sam` at the end of the list.

**ii)** Write code to print the list `people` to screen.

**iii)** Write code to display the length of the list.

**iv)** Write code to display the second item in the list.

Run the code file using command. 

```
python workshop3b_part2.py
```

It should produce exactly 4 lines of output, with first line `Part 2:`, followed by lines that show the output created from the instructions above.

***

### Part 3: 

Work in a code file called `workshop3b_part3.py`

This should start with the following lines of code:

```python
print("Part 3:")
values = [ 9, 33, 6, 21 ] 
```

Now add code lines to do the following. 

**i)** Insert the value `12` at the start of the list and display the updated list using the `print()` function, to show it has been updated and now stores `[12, 9, 33, 6, 21]`.

**ii)** Use a `for` loop to run over the list and display the result of dividing each entry by 3. so that it displays the values 4, 3, 11, 2, 7 each on a separate line

Run the code file using command. 

```
python workshop3b_part3.py
```

It should produce exactly 7 lines of output, with first line `Part 3:`, followed by lines that show the output created from the instructions above.

### Part 4: 

Run the following lines in the terminal to stage, commit and push your code back to your GitHub repository:

```
git add .
git commit -m "completed workshop 3b"
git push
```

To check your work has been saved you can run the line of code below in the terminal to get the web address of the repository in GitHub. Goto the repository and check the completed code files are stored.

```
git config --get remote.origin.url
```
