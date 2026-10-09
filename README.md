# Python Week 3 Workshop

This workshop is focused the Python skills we have covered so far:

 - strings and string formatting
 - lists and dictionaries
 - for and while loops
 - conditional statements

You should attempt the workshop tasks without using any external web sites or GenAI.

Use the following cheat sheets if you need to look up any Python commands.

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week1_cheatsheet.md

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week2_cheatsheet.md

https://github.com/phil-lewis-exe/PythonCheatSheets/blob/main/Week3_cheatsheet.md

To test your code as you write it, run the following command in the lower terminal panel (change to the filename you are testing):

```
python workshop3_part1.py
```

After each task save your work to GitHub by running the command below in the terminal:

```
git_helper --commit
```

---

## Tasks


### Part 1: Variables and strings

Work in a code file called `workshop3_part1.py`. It should start with the following line of code:

```python
print("Part 1:")
```

Next we are going to store some information about a pet dog called `gnasher`. 

**i)** Write a Python comment line containing: `Author: XXXXXXXX`

**ii)** Write code that sets up four variables as described in the table below using appropriate data types (i.e. do not store the numbers as strings):

| variable name | stored data |
|---------------|-------------|
| dog           | gnasher     |
| owner         | dennis      |
| age_year      | 4           |
| h_cm          | 51.2        |

Write code that does the following, so that each instruction creates one line of output:

**iii)** Display the name of the owner in title case (first letter capitalised).

**iv)** Display the name of the dog in upper case (all letters capitalised).

**v)** Display the dog's height in inches (found by dividing its height in cm by 2.54).

**vi)** Use an f-string to display the following message:

`The dog called ______ is _______ years old.`

inserting the correct values from your stored variables. You can leave the name in lower case.

Run the code file in the terminal using the command:

```
python workshop3_part1.py
```

It should produce exactly 5 lines of output, with first line `Part 1:`, followed by the output from the instructions above.


Remember to save your code to GitHub using `git_helper --commit` in the terminal before starting the next task. 


---

### Part 2: Lists

Work in a code file called `workshop3_part2.py`

This should start with the following lines of code:

```python
print("Part 2:")
people = ['fred', 'greta', 'hetty' ]
```

Write four lines of code that do the following:

**i)** Write code that adds another item `sam` at the end of the list.

**ii)** Write code that displays the list `people` using the `print()` function.

**iii)** Write code that displays the length of the list.

**iv)** Write code that displays the second item in the list.

Run the code file using the command:

```
python workshop3_part2.py
```

It should produce exactly 4 lines of output, with first line `Part 2:`, followed by the output from the instructions above.


Once your code is working save it to GitHub.

---

### Part 3: For loops

Work in a code file called `workshop3_part3.py`

This should start with the following lines of code:

```python
print("Part 3:")
values = [ 9, 33, 6, 21 ] 
```

Write code that does the following:

**i)** Insert the value `12` at the start of the list and display the updated list using the `print()` function, to confirm it has been updated and now stores `[12, 9, 33, 6, 21]`.

**ii)** Use a `for` loop to run over the list and display the result of dividing each item by 3, so that it displays the values 4.0, 3.0, 11.0, 2.0, 7.0 each on a separate line.

Run the code file using the command:

```
python workshop3_part3.py
```

It should produce exactly 7 lines of output, with first line `Part 3:`, followed by the output from the instructions above.

Once your code is working save it to GitHub.

---

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

Start beneath this existing code. Notice that the `for` loop has changed the value stored in `x`, so first add a line  `x = 2` to set the starting value back to `2`. 

Next write code that generates the same sequence using a `while` loop, stopping once `x` is greater than or equal to 2000, so that the last value displayed is below 2000.

The condition should ensure that for any positive starting value of `x` the code will generate a doubling sequence that continues until the stopping condition is met (next `x` would be greater or equal to 2000). 

Run the code file using the command:

```
python workshop3_part4.py
```

Once your code is working save it to GitHub. If you tried different starting values, remember to change them back to `2` before saving on GitHub.


---

### Part 5: if-else statements  

Work in a code file called `workshop3_part5.py`

This should start with the following line of code:

```python
print("Part 5:")
```

A bike hire company is developing software to manage its rentals.

The software stores information on each customer in three variables, as illustrated in the example code below:

```python
fullname = "A N Other"
age = 23
height_cm = 155
```

To hire a bike, customers must be 18 or over.

Copy the code that sets up the three customer variables into your file.

Write code that displays the message: 

```
checking age
```

Then write an `if` statement that displays a message based on the customer's stored age.

This should display:

 - `deny rental` if the customer is under 18
 - `approve rental` if the customer is 18 or over

Run the code file using the command:

```
python workshop3_part5.py
```

Test your code with different values, but set the age back to `23` before saving on GitHub.

---

### Part 6: if-elif-else statements  

Work in a code file called `workshop3_part6.py`

This should start with the following lines of code:

```python
print("Part 6:")
fullname = "A N Other"
age = 23
height_cm = 155
```

The bike hire company has three sizes of bike to hire out to customers:

 - **`S`** for customers smaller than 140cm
 - **`M`** for customers between 140cm and 160cm inclusive
 - **`L`** for customers larger than 160cm

Write code that displays the message: 

```
finding size
```

Then write an `if`-`elif`-`else` block that displays the appropriate message below according to the stored height:

 - **`rent S bike`** 
 - **`rent M bike`**
 - **`rent L bike`**

Run the code file using the command, and save your work to GitHub when completed.

```
python workshop3_part6.py
```


---

### Part 7: Storing information in a Dictionary

Work in a code file called `workshop3_part7.py`

This should start with the following lines of code:

```python
print("Part 7:")
customer_data = []
```

Write code that does the following:

**i)** Create a Python dictionary called `customer1` storing the following customer data:
 
   key `fullname`, value `Ms Tall`
   key `age`, value `23`
   key `height_cm`, value `189`
   
**ii)** Create an **empty** Python dictionary called `customer2`.

**iii)** Add the following customer data to `customer2`, one key at a time:
 
   key `fullname`, value `Mr Small`
   key `age`, value `25`
   key `height_cm`, value `132`

**iv)** Store both dictionaries in the `customer_data` list.

**v)** Display the list using the `print()` function.

As in Part 1, use appropriate data types (i.e. do not store the numbers as strings).

Run the code file using the command, and save your work to GitHub when completed.

```
python workshop3_part7.py
```


---

### Part 8: Accessing information in a Dictionary

Work in a code file called `workshop3_part8.py`

This should start with the following line of code:

```python
print("Part 8:")
```

The bike hire company stores its stock levels in a Python dictionary like the one below:

```python
stock_levels = { "S": 10, "M": 23, "L": 17 }
```

**i)** Starting with this line that defines the dictionary, write code that loops over the entries to produce a stock report in the following format:

```
number of bikes in stock
S 10
M 23
L 17
```

**ii)** Edit your code so that it also calculates the total number of bikes in stock and displays a final line:

```
total 50
```

Run the code file using the command, and save your work to GitHub when completed.

```
python workshop3_part8.py
```


---

### (Optional) Extension: Updating information in a Dictionary

Work in a code file called `workshop3_extension.py`

This should start with the following lines of code:

```python
print("Extension:")
stock_levels = { "S": 10, "M": 23, "L": 17 }
customer_data = []
```

Copy the code that creates the `customer1` and `customer2` dictionaries from Part 7 into your file, and store them in the `customer_data` list.

Also create a third customer dictionary `customer3` with key `fullname`, value `Miss Young`, key `age`, value `16` and key `height_cm`, value `150`, and add it to the end of the list.

Beneath this, write code that does the following:

**i)** Display the stock levels, for example:

```
number of bikes in stock
S 10
M 23
L 17
total 50
```

**ii)** Process each customer in the list, allocating a bike from the stock if the hire is allowed. Check the age rule first, then the stock levels.

For example, if a customer meets the age requirement and has a height matching a medium bike, the code should decrease the count of `M` bikes in the stock level dictionary by 1, and add a new key `rental` to the customer dictionary:

`{ fullname: ..., age: ..., height_cm: ..., rental: "M"}`

Your code should log the outcome for each customer by displaying one of the following messages:

 - Where the hire is successful:

   `Rented ___ bike to ___.` inserting the bike size and customer name.

 - Where the hire is unsuccessful due to the age rule:

   `No rental to ___ as they are under 18.` inserting the customer name.

 - Where the hire is unsuccessful due to the stock levels:

   `No rental to ___ as we have no ___ bikes in stock.` inserting the customer name and bike size.

**iii)** After processing all the customers, display the updated stock levels using the format above.

You can test your code by setting one of the stock levels to `0`, and changing customer details but set them back to the values above before saving on GitHub.


---

### (Optional) Challenge: Coding a stock management system for bike hire

Work in a code file called `workshop3_challenge.py`

Write a Python program that can track bike hire. 

It should have a dictionary to store the stock of bikes, a list of current customers, and a list of past customers.

You should use a `while` loop that runs continually to register hires and returns, taking input from a store assistant, e.g.

```
user_input = input( "Enter mode: [ 1 - renting ] or [ 2 - returning ]" )
mode = int(user_intput)
customer_name = input("What is the customer name?") 
```

Think about the needs of a real shop and decide what customer information would need to be stored, and what the shop needs to track.

Hint: your loop will need a way for the store assistant to quit (e.g. typing `q`), and your code should check the input it is given so that a typing mistake does not crash the program.

---

### Submitting your work

Use the following command to build a zip of the work you completed in the workshop. 

You will see the created file in the file panel. 

Right click on the zip file to download a copy to your computer.

```
git_helper --zip
```
