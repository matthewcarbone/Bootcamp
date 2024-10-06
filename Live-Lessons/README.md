# Introduction to Python: 10-week bootcamp

## Week 1 - Introduction to programming and Python basics

- What is programming?
	- Basic introduction to programming conceptually: "Tell me how to make a peanut butter and jelly sandwich".
	- What is an algorithm? Why do we care about algorithms?
- Why do we use Python, and how does it compare to other programming languages? What advantages does Python have?
	- Python is syntactically simple. It is easy to read and easy to write.
	- Python is incredibly popular and has a very large open source and support community.
	- Python is applied in many fields. It is the premier machine learning language, and is incredibly popular in scientific computing _unless_ raw speed/power is required.
- What are the disadvantages of Python?
	- It's slow when used improperly.
	- It does not (easily) support type checking.

### Jupyter notebooks 
- What is a Jupyter notebook?
- How to use Google Colab (you'll need to make a Google account).

### Basic syntax and operations
- Starting simple: printing strings.
	- What is `print`?
	- What is a string?
- What is a comment, and why are comments important?
- Basic arithmetic, specifically addition, subtraction, multiplication, division, exponentiation and modulus.

### Activities summary
- "Hello world"
- Simple arithmetic
- Comments
- Markdown in Jupyter notebooks

## Week 2 - Variables and types

### Variables
- What is a variable? Why do we need variables?
- How do we assign variables? We probably did this in the last lesson, but let's go over it again!
- How do we name variables? Why is variable naming important? What are the standard conventions for naming variables?

### Data types
- What is a data type, and what kinds of data exist in Python?
	- There are four primary data types when it comes to computing, `int`, `float`, `string`, and `bool`
	- There are other data types, but we'll focus on these for now.
- How do data types "transform" ("cast") into each other?

### Basic operations with variables
- Arithmetic operations with variables, and why it's important.
- Operations with strings, specifically concatenation and replication.
- Order of operations.
- f-strings
- Getting user input using `input`.

### Activities summary
- Variable assignment.
- Build a calculator that takes two numbers and performs basic addition, subtraction, multiplication, etc.
- String manipulation, specifically using `*`.

## Week 3 - Control flow
- What actually is control flow?

### Logical expressions
- Logical comparisons: `==`, `!=`, `>`, `<`, `>=`, `<=`. What do these do?
- Logical operators: `and`, `or` and `not`. What do these do?

### Conditional expressions
- Core control flow using `if`, `elif` and `else` statements.
- Indentation in Python and why it's important.
- Nesting conditionals.

### Activities summary
- Write a program to check whether a number is even or odd.
- Write a program to check whether someone's age is greater or less than some number ("age verification").
- Write a program to calculate someone's letter grade based on a percentage of questions correct on an exam.

## Week 4 - Control flow continued

### Loops
- What is a `for` loop?
- Why do we care about for loops, and what are they used for?
- The `range` function.
- What is a `while` loop? How do we loop based on a condition?
- `break` and `continue`

### Activities summary
- Write a `for` loop to print numbers between `n0` and `n1`.
- Create a countdown timer using a `while` loop.

## Week 5 - Functions
- What is a function, and why do we need them? Note, we might have covered this earlier, but we're going to go through it again!
- Definition of functions using `def`.
- Parameters, optional parameters, default parameters.
- Return values.
- Built-in vs. user-defined functions.
	- Showcase examples of functions we've been using all along! For example, `print`.

### Variable scope
- What is variable scope?
- What is a global vs. local variable, and why do they matter in functions?

### Importing functions
- Using `import` to import new functions from the Python standard library.
- What is the Python standard library?

### Activities summary
- Write a function to calculate the area of a circle as a function of its radius. Note, we might need to import the value for `pi` (unless you want to approximate it by e.g. 3.14).
- Create a function that checks if a number is prime (challenging! Might require some extra Googling).
- Use the `math` library (part of the Python standard library) to perform some advanced mathematical operation, such as the logarithm.
- Rewrite the calculator from before to use functions.
