# class09
## What Are Dunder Methods?
In Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.

As it quickly became tiresome to say under-under-method-under-under Pythonistas adopted the term “dunder methods”, a short form of “double under.”
### Object Initialization: ```__init__```
- for initailizing and construct objects
### Object Representation: ```__str__, __repr__``` 
- __repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous.

- __str__: The “informal” or nicely printable string representation of an object. This is for the enduser.

### Iteration: ```__len__, __getitem__, __reversed__```

### Operator Overloading for Comparing Accounts: ```__eq__, __lt__```

### Operator Overloading for Merging Accounts: ```__add__```

### Callable Python Objects: ```__call__```
- You can make an object callable like a regular function by adding the ```__call__``` dunder method.

### Context Manager Support and the With Statement: ```__enter__, __exit__```

## What is probability?

At the most basic level, probability seeks to answer the question, “What is the chance of an event happening?” An event is some outcome of interest. To calculate the chance of an event happening, we also need to consider all the other events that can occur. The quintessential representation of probability is the humble coin toss.


