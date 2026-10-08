# Python Week 3 Workshop

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

Where the correct values are inserted into the sentence using the stored variables. You can leave the name in lower-case.

Run the code file in the terminal using command:

```
python workshop3_part1.py
```

It should produce exactly 5 lines of output, with first line `Part 1:`, followed by lines that show the output created from the instructions above.


Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

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


Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

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

Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

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

(If you try different values remember to change it back to `2` before saving on GitHub.)


Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

---

### Part 5: if-else statements  

Work in a code file called `workshop3_part5.py`

This should start with the following lines of code:

```python
print("Part 5:")
```

A company are writing software to run a bike hire company.

The software stores information on the customer in three variables as illustrated in the example code below:

```python
fullname = "A N Other"
age = 23
height_cm = 155
```

To rent a bike customers have to be 18 or over.

Copying in the code section that sets up the three customer variables.

Write code that displays the message: 

```
checking age
```

Then write an `if` statement that displays a message based on their stored age.

This should display:

 - `deny rental` if the customer is under 18
 - `approve rental` if the customer is 18 or over

Test your code with different values, but set the age back to `23` before saving on GitHub.


Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

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

The bike rental company have three sizes of bike they hire out to customers

**`S`** for customers smaller than 140cm
**`M`** for customers between 140cm and 160cm inclusive
**`L`** for customers larger than 160cm

Add code to the file that displays the message: 

```
finding size
```

Then write an `if`-`elif`-`else` block that displays the appropriate message from the below according to the stored height.

 - **`rent S bike`** 
 - **`rent M bike`**
 - **`rent L bike`**

Test your code with different values, but set the height back to `155` before saving to GitHub.

Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```



---

### Part 7: Storing information in a Dictionary

Work in a code file called `workshop3_part7.py`

This should start with the following lines of code:

```python
print("Part 7:")
customer_data = []
```

Start with the following lines of code:

```python
customer_data = []
```

Now add code lines to:

 - create a Python dictionary called: `customer1` storing the following customer data:
 
   key `fullname`, value `Ms Tall`
   key `age`, value `23`
   key `height_cm`, value `189`
   
 - create an **empty** Python dictionary called: `customer2`
 - store the following customer data into the dictionary:
 
   key `fullname`, value `Mr Small`
   key `age`, value `25`
   key `height_cm`, value `132`

 - store both dictionaries you created into the `customer_data` list
 - print the list to screen

Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

---

### Part 8: Accessing information in a Dictionary

Work in a code file called `workshop3_part8.py`

This should start with the following line of code:

```python
print("Part 8:")
```

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

b) Edit your code so that it can also add up the number of each type of the three bikes and display a final line:

```
total 50
```

Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

### Extension: Updating information in a Dictionary

Work in a code file called `workshop3_part9.py`

This should start with the following line of code:

```python
print("Part 9:")
stock_levels = { "S": 10, "M": 23, "L": 17 }
customer_list = []
```

Copy in the code to create customers 1 and 2 dictionaries you created earlier and store them in the customer list.

Beneath this write Python code that processes each customer in the list, according to the following:

 - display the stock levels e.g.

```
number of bikes in stock
S 10
M 23
L 17
total 50
```

- examine the customer information and allocate a bike from the stock if the rental is allowed.

e.g. if a customer meets the age requirement and has height matching a medium bike, the code should decrease the count of `M` bikes in the stock level dictionary by 1, and add a `rental` entry to the customer dictionary in a new key

`{ full name: ..., age: ..., height_cm: ..., rental: "M"}`

- A rental registered in this way should be logged by the code displaying a message:

`Rented ___ bike to ___.` inserting the bike size and customer name.

- Where the rental is unsuccessful due to the age rule, your code should log either

`No rental to ___ as they are under 18.` inserting the customer name.

- Where the rental is unsuccessful due to the stock levels, your code should log

`No rental to ___ as we have no ___ bikes in stock.` inserting the customer name and bike size.

- After processing all the customers you should display the updated stock levels using the format above.

Save your work to GitHub by running the command below in the terminal:

```
git_helper --save
```

### Submitting your work

Use the following command to build a zip of work you completed in the workshop that you can download to your computer.

```
git_helper --zip
```
