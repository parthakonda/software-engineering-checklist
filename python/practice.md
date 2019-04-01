# Practice questions for understanding python

# Runway
1. Install `virtualenv` and create virtualenv's for both 2.7 and 3.5.
2. Install package `pytz` in both above created virtualenvs
3. Create a python module and name it as `module1.py`
4. Place the above created module (`module1.py`) in package call `mypackage`.
5. Create another package called `anotherpackage` at same level where `mypackage` created.
6. Create `module1.py` in `anotherpackage`.
7. Define varible `my_awesome_variable=20` in `module1.py` in `mypackage`.
8. Import `my_awesome_variable` in `anotherpackage` inside `module1.py`

# Variables
1. Create module and define variables for all type of data such as `integer`, `float`, `string`, `bytes`, `boolean` and do not initialize them.
2. Print all default values of the above defined variables.
3. Create a list and assign different values.
4. Iterate through a list
5. Access any specific element in the list
6. Add item to the list
7. Take another list and try to add both lists as single list

# String formatting
1. create a string variable.
2. Assign variable with value i.e., `my awesome string`
3. Try to access last `5` letters
4. Print string in reverse order
5. Print string as length of `20`, where as if string should be middle aligned.
Example:
--------------------
*my awesome string**

However, the value of string can be changed later.
6. Update the above string value of last `5` letters into `python` i.e., `my awesome python`

# List & its operations
1. Create a list of unsorted numbers.
```
Example:
    li = [14, 2, 44, 22]
```
2. Check if the given list of items are only type of numbers.
```
Example: 
    Wrong: li = [12. '2', 'asdf']
Hint:
isinstance(li[0], int) # you can programatically iterate through all items
```
3. Find duplicates in the list
4. Find unique items in the list.
5. Sort the given list
6. Print the list in reverse order
7. Print Last `3` values in the list in reverse order
```
Example:
li = [ 34, 2, 9, 45, 89, 123, 890]

Expected output:
890, 123, 89
```
8. Merge two lists into another list

# Tuples
1. Create a tuple with `2` numbers.
2. Add 3rd element to the Tuple
3. Access specific element in the tuple
4. Update specific element in the tuple
