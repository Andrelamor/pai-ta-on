Variables
===

In this Python tutorial, you're going to learn about variables, which are one of the most fundamental concepts in programming.
They're not specific to Python and exist in pretty much every programming language out there.

We use variables to temporarily store data the computer's memory. Here's an example, let's type:

```Python
>>> price = 10
```

When the Python interpreter executes this code, it will allocate some memory, then it will store the number 10 in that memory, and finally, it will attach this price label in that memory location.
As a metaphor imagine we have a box.
In that box, we have the number 10, and the price is the label that we put on the box.
Now we can use this label anywhere in our program to access the value that we have in that box.
This is a very simplified explanation!

Let's use our brand new variable to print its value on the terminal:

```Python
>>> print(price)
```

In review, we'll see 10 on the terminal.

```Python
>>> price = 10
>>> print(price)
10
```

So this is how we define variables, we start with **an identifier which is the name of our variable**, then, an equal sign, and finally a value.
More accurately, when this number 10 is about to be stored in the memory, first it will get converted to this binary form presentation.
The number 10 is in the [decimal system](https://en.wikipedia.org/wiki/Decimal){:target="_blank"} which has all the digits from 0 to 9.
Computers don't understand these digits, they only understand [bynary sistem](https://en.wikipedia.org/wiki/Binary_number){:target="_blank"}, which is a bunch of 0's and 1's.
So, to store the number 10 in the computer’s memory first will get [converted to its binary](https://www.khanacademy.org/math/algebra-home/alg-intro-to-algebra/algebra-alternate-number-bases/v/decimal-to-binary){:target="_blank"}.

Taking this program to the next level. Updating the value of this price variable to a new value, like 20, we should see 20 printed, because the Python interpreter executes our code line by line from the top.

```Python
>>> price = 10
>>> price = 20
>>> print(price)
20
```

We set the price to 10, then we reset it to 20, and finally, we print it on the terminal.

So far, the numbers that we have until now are whole numbers without a decimal point.
In programming, we refer to these numbers as integers.
We can also use numbers with a decimal point. These kind of numbers are called the floating-point number, or float for short.

```Python
>>> rating = 4.9
>>> print(price)
4.9
```

Now we defined another variable called rating, but this time the float number 4.9 was assigned to it.

We can also define a variable and set it to a [string](https://en.wikipedia.org/wiki/String_(computer_science)){:target="_blank"}, for example, name equals Paul.
In a very simplified way, in computer science, [strings](https://www.bbc.co.uk/bitesize/guides/zc6s4wx/revision/4#:~:text=Most%20programming%20languages%20have%20a,and%20characters%20may%20be%20repeated.&text=A%20string%20can%20be%20a%20constant%20or%20variable%20.){:target="_blank"} are ordered sequences of characters.

```Python
>>> name = 'Paul'
>>> print(name)
Paul
```

Above, the name variable was created and the value Paul was assigned to it.

We also have another kind of value called boolean which can be True or False. They are like yes and no in English. Below is an example. I'm going to define a variable, is_published and set it to True.

```Python
>>> is_published = True
>>> print(is_published)
True
```

Note that booleans must be capitalized.
Python will not understand if you spell it with a lowercase f r t an throw an error.

```Python
>>> is_published = true
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'true' is not defined
>>>
```
In summary, simple values can be numbers, which can be integers or floats, strings or booleans.
We can store complex values like lists and values, which we'll see in the future.
