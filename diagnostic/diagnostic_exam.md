## Software Design Mid-Semester Diagnostic Self-Exam


1. **`print` vs `return`**

	Modify this function to satisfy the following conditions:

	- Print the input
	- Return the input multiplied by 4

	```python
	def print_and_return(input):
		print "I'm a string!"
		return None
	```

	- What is the difference between return and print? 
	- How many things can we print in a function? 
	- How many things can we return?
	- What happens if your input is a string?

1. **Conditional Statements**

	Modify this function to satisfy the following conditions:

	- Return `True` if `number1` is greater or equal to `number2`
	- Print "Big input!" if either number is greater than 10
	- If an input is not a number, return `False`
	
	```python
	def conditional_statements(number1, number2):
		pass
	```
	
	- What is the difference between `if`, `elif`, and `else`?

1. **List operations**

	Modify this function to satisfy the following conditions:

	- Print the length of the list
	- Check if the input is in the list, append it to the list if it isn't, print "Already here!" if it is
	- Print the first 3 values of the list
	- Return the last value of the list
	
	```python
	def list_operations(input):
    	test_list = [20,1,3,24,6,9]
		return None
	```
	
	- How is a list indexed?
	- How do we remove and add items from a list?

1. **Loops**

	Modify this function to satisfy the following conditions (you can assume `input` is an iterable):
	
	- Create a while loop what will print every value in the input
	- Create a for loop that will print every value in the input. Do not use `range(len(input))`
	- Return a value randomly chosen from the input
	
	```python
	def for_vs_while_loops(input):
	    pass
	```
    
    - What is the difference between a for loop and a while loop? 
    - In what situation should you use each?
    
1. **Lists, dictionaries, and tuples**

	A. What data structure are each of the following?
		1. `a = {"duck" : 1, "dog" : 5, "goose" : 3}`
		1. `b = ("duck", 2)`
		1. `c =  ["duck", "dog", "goose"]`
	
	B. Determine the output of the code snippet. Assume the that a, b, and c are all as above at the start of each question. If it would cause an error, write "ERROR" and what data structure you could use to make it run correctly.
		1. 
			```python
			a[1] = "duck"
			print a
			```
		1. 
			```python
			b[1] = "duck"
			print b
			```
		1. 
			```python
			c[1] = "duck"
			print c
			```
		1. 
			```python
			a["duck"] = "turtle"
			print a["duck"] + "duck"
			```
		1. 
			```python
			print b[a["duck"]]
			```
		1. 
			```python
			b.append("cat")
			print b
			```
		1.
			```python
			c.append("cat")
			print c
			```

1. ** File operations and dictionaries**

	A. Read in the file duck_colors.txt. It consists of random colors, with each color separated by a comma and then a space. 
	A. Use this data to create a dictionary where the keys are the colors and the values are the number of times the color occured.
	A. Write this data to a file called counted_colors.txt in the format: 
		
		`color, occurrences`
		
		For example:
		
		```
		green, 4
		purple, 91
		red, 18
		```

1. **Classes - attributes, methods, and inheritance**

	Fill in water_animal.py according to the comments.

1. **Coding style and etiquette**

	Rewrite bad_code.py to be more readable, extendable, concise, and efficient. 
	
	Try skimming through the [Python Style Guide](http://docs.python-guide.org/en/latest/writing/style/) and/or [PEP8](https://www.python.org/dev/peps/pep-0008/). These are both reasonably long, just read the sections that look interesting or relevant. Talk to a NINJA if you have questions.







