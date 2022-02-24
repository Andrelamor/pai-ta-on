# Arithmetic

So, you have learned that in Python programming language you have 2 types of numbers: 
- integers, wich are whole numbers like 10, they don't have a decimal point, 
- and floating point numbers or floats, which are numbers with a decimal point.

Now, in this tutorial, you're going to look at the arithmetic operations supported in Python language.
These are the same arithmetic operations that we have in Math, we can add numbers, multiply them and so on.
So let's look at a few examples:

We can print 10 plus 3, so this is the addition operator:
````python
print(10 + 3)
````  
We also have subtraction, we have multiplication:
````python
print(10 * 3)
```` 
We have two kinds of division:
````python
print(10 / 3)
print(10 // 3)
```` 
The first one, with a forward slash, wich results a floating point number.
But we also have another division operator for getting an integer. 
So, if we add another slash and run the command, we get an integer.

We also have another operator called modulis, wich is a percent sign:
````python
print(10 % 3)
```` 
And this returns the remainder of the division.
So, when we run this command, we should get 1. 

And one last operator we have here is exponent which is the power.
So, that is indicated with 2 asterisks and this will return 10 to the power of 3.
We get 1000:
 ````python
print(10 ** 3)
````
So, these are the arithmetic operators in Python programming language. 

Now, for all these operators that you learned, we have an augmented assignment operator.
That is very useful, let me show you.
So, let's say we have a variable called 'x', we set it to 10. Now we want to increment this by  3, we'll have to code like this:
 ````python
x = 10
x = 10 + 3
print(x)
````
So, Python add 3 to 10 and it get stored into 'x' again.
So, when we print 'x' we should see '13'.
This is how you can increment a number, right?
Augmented assign operator is a way to write the same code, but in a shorter form.
This is how it works: we type 'x' plus equals 3. 
What we have on line 3 is exactly like what we have on line 2:
 ````python
x = 10
x = 10 + 3
x += 3
print(x)
````
So this is what we call the **augment assignment operator**. 
We have augmented or enhanced the assignment operator.
In this particular case, we are incrementing a number using the augmented assignment operator, but we can also subtract or multiply a number by a given value.
For example, let's delete what we have on line 2, we can type subtract equals 3:
 ````python
x = 10
x -= 3
print(x)
````

# Operator Precedence

What do you think is the result of this expression?
 ````python
x = 10 + 3 * 2
print(x)
````
This is a very basic Math question that unfortunately a lot of people fail to answer.
The answer is 16. Because in Math we have this concept called operator precedence which means the order of operations.
So, the multiplication operator has a higher precedence, which means it's applied first.
This is what we call operator precedence, it's just a Math concept, it's not about python programming language.
So, all the other programming languages behave the same way.

Here is the order:

1. exponentiation 
2. multiplication or division
3. addition or subtraction

Let's see another example: we're gonna add the exponentiation operator:
 ````python
x = 10 + 3 * 2 ** 2
print(x)
````
Once again, what do you think is the result of this expression?
The answer is 22. Because the exponentiation operator takes precedence, so first 2 to the power of 2 is executed. The result is 4, and then it is multiplied by 3, wihch give us 12, and then the final addition with 10 that results 22.

We can also use parenthesis to change the order of operations.
So, if we have parenthesis, it always takes priority.
In the example above we can add parenthesis around 10 plus 3, so this piece of code will be executed first.
 ````python
x = (10 + 3) * 2 ** 2
print(x)
````
The result is 13, then the exponentiation operator will be executed, so 2 to the power of 2 is 4, and finally 4 is multiplied by 13.
Now here is a little exercise for you:

 ````python
x = (2 + 3) * 10 - 3
print(x)
````
What is the result of this?

# Math Functions

We are going to look at a few useful functions for working with numbers.
Let's start by defining a variable like 'x' and set it to 2.9.
To round this number, we can use the built in round function:

````python
x = 2.9
print(round(x))
````
We have another useful built in function called _abs_, which is short for _absolute_, and this returns the positive representation of this value, even it is negative.
````python
x = -2.9
print(abs(x))
````
Technically, in Python we have a handful built in functions for performing mathematical operations.
The Math module could be imported to perform complex mathematical operations.
A module in Python is a separate file with some reusable code.
We use these modules to organize our code into different files.
Each module contains a bunch of reusable functions for performing mathematical calculations.

To use Math module, we type 'import math' on the top, all in lower case.
````python
import math
x = -2.9
print(abs(x))
````
Now math is an object like a string, so we can access it's functions, or more accurately, it's methods using the _dot_ operator:
For example, we can call the ceil method, to get the ceiling of a number:
````python
import math
x = math.ceil(2.9)
print(x)
````
Another useful method is the floor method:
````python
import math
print(math.floor(2.9)
````
To search for all the math methods: https://docs.python.org/3/library/math.html
