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



# Math Functions