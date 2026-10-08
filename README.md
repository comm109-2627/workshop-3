# Python Week 3 Assessed Workshop

You may use the following cheat sheets if you need to look up any Python commands.

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week1_cheatsheet.md

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week2_cheatsheet.md

You should not need to use any other websites. 

---

## TASKS


### Part 1: 

Work in a code file called `workshop3_part1.py`. It should start with the following line of code:

```python
print("Part 1:")
```

Next we are going to store some information about a pet dog called `gnasher`. 

**i)** Write a Python comment line containing: `Author: XXXXXXXX`

**ii)** Write code to set up four variables as described in the table below using appropriate data types (i.e. do not store the numbers as strings):

| variable name | stored data |
|---------------|-------------|
| dog           | gnasher     |
| owner         | dennis      |
| age_year      | 4           |
| h_cm          | 51.2        |

Write Python code to do the following, so that each creates one line of output:

**iii)** Display the name of the owner, in title case (first letter capitalised).

**iv)** Display the name of the dog in upper case (all letters capitalised).

**v)** Display the dogs height in inches (found by dividing its height in cm by 2.54)

**vi)** Use an f-string to display the following message:

`The dog called ______ is _______ years old.`

Where the correct values are inserted in to the sentence usign the stored variables. You can leave the name in lowerr-case.

Run the code file in the terminal using command:

```
python workshop3_part1.py
```

It should produce exactly 5 lines of output, with first line `Part 1:`, followed by lines that show the output created from the instructions above.

Run the command:

```
git_helper --save
```

in the terminal to save your work to GitHub.

### Part 2: 

Work in a code file called `workshop3_part2.py`

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
python workshop3_part2.py
```

It should produce exactly 3 lines of output that show the output created from the instructions above.

Run the command:

```
git_helper --save
```

in the terminal to save your work to GitHub.

***

### Part 3: 

Work in a code file called `workshop3_part3.py`

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
python workshop3_part3.py
```

It should produce exactly 7 lines of output, with first line `Part 3:`, followed by lines that show the output created from the instructions above.

Run the command:

```
git_helper --save
```

in the terminal to save your work to GitHub.

### Part 4: While loops 

Work in a code file called `workshop3_part4.py`

This should start with the following lines of code:

```python
print("Part 4:")
x = 2
for i in range(15):
    print(x)
    x = x*2
```

The starter code uses a `for` loop to generate 15 values in a sequence. 

Try the code out to see its output.

Start beneath this existing code. Write code that generates the same sequence but using a while loop. Set the condition to stop looping once `x` is greater or equal to 2000.

(i.e. so the last value printed is the last one in the sequence that is below 2000).

The condition should work to stop the loop whatever value of `x` is set on the first line. 

(If you try different values remember to change it back to `2` before submission).

---

### Part 5: If statements  

A company are writing software to run a bike hire company.

The software stores information on the customer in three variables as shown below:

```python
fullname = "A N Other"
age = 23
height_cm = 155
```

**2. i** 

*If you are working in CodeSpaces work in file **`4b_part2_i.py`***

To rent a bike customers have to be 18 or over.

Start your file by copying in the code section that sets up the three customer variables.

Write code that displays the message: 

```
checking age
```

Then write an `if` statement that displays a message based on their stored age.

This should display:

 - `deny rental` if the customer is under 18
 - `approve rental` if the customer is 18 or over

Test your code with different values, but set the age back to `23` before submission.

---

**2. ii**

*If you are working in CodeSpaces work in file **`4b_part2_ii.py`***

The bike rental company have three sizes of bike they hire out to customers

**`S`** for customers smaller than 140cm
**`M`** for customers between 140cm and 160cm inclusive
**`L`** for customers larger than 160cm

Start your file by copying in the code section that sets up the three customer variables.

Write code that displays the message: 

```
finding size
```

Then write an `if`-`elif`-`else` block that displays the appropriate message from the below according to the stored height.

 - **`rent S bike`** 
 - **`rent M bike`**
 - **`rent L bike`**

Test your code with different values, but set the height back to `155` before submission.

---

### Part 3: Dictionaries

**3. i**

*If you are working in CodeSpaces work in file **`4b_part3_i.py`***

Start with the following lines of code:

```python
customer_data = []
```

Now add code lines to:

 - create an empty Python dictionary called: `customer`
 - store the following customer data into the dictionary:
 
   key `fullname`, value `B Wiggins`
   key `age`, value `45`
   key `height_cm`, value `190`

 - add the dictionary you created into the `customer_data` list
 - print the list to screen

---

**3. ii**

*If you are working in CodeSpaces work in file **`4b_part3_ii.py`***

The bike rental company store the level of stock in a python dictionary like the one below:

```python
stock_levels = { "S": 10, "M": 23, "L": 17 }
```

a) Starting with this line that defines the dictionary, write Python code that loops over the entries to produce a stock report in the following format:

```
number of bikes in stock
S 10
M 23
L 17
```

b) Edit your code so that it can also add the number of each type of the three bikes and display a final line:

```
total 50
```

---

### Submitting your work

