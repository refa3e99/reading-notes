# Read: class04
## classes
Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.
The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.
![download](https://user-images.githubusercontent.com/95183257/172267109-25713ea1-d70b-472c-a39c-d0fcbeb3a93d.jpg)

this is what a class looks like : 
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age
    
To understand the meaning of classes we have to understand the built-in __init__() function.

All classes have a function called __init__(), which is always executed when the class is being initiated.

Use the __init__() function to assign values to object properties, or other operations that are necessary to do when the object is being created.

You can delete properties on objects by using the del keyword.
## recursion
Problems (in life and also in computer science) can often seem big and scary. But if we keep chipping away at them, more often than not we can break them down into smaller chunks trivial enough to solve. This is the essence of thinking recursively, and my aim in this article is to provide you, my dear reader, with the conceptual tools necessary to approach problems from this recursive point of view.
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function. Using a recursive algorithm, certain problems can be solved quite easily.
## pytest
 pytest, a library for testing Python code
 pytest has become quite popular, in no small part because it's so easy to write tests and integrate those tests into your software development process.
 In pytest, you define fixtures using a combination of the pytest.fixture decorator, along with a function definition.
 
 In testing, a fixture provides a defined, reliable and consistent context for the tests. This could include environment (for example a database configured with known parameters) or content (such as a dataset).

Fixtures define the steps and data that constitute the arrange phase of a test (see Anatomy of a test). In pytest, they are functions you define that serve this purpose. They can also be used to define a test’s act phase; this is a powerful technique for designing more complex tests.

The services, state, or other operating environments set up by fixtures are accessed by test functions through arguments. For each fixture used by a test function there is typically a parameter (named after the fixture) in the test function’s definition.
pytest does its best to put all the fixtures for a given test in a linear order so that it can see which fixture happens first, second, third, and so on. If an earlier fixture has a problem, though, and raises an exception, pytest will stop executing fixtures for that test and mark the test as having an error.

When a test is marked as having an error, it doesn’t mean the test failed, though. It just means the test couldn’t even be attempted because one of the things it depends on had a problem.

This is one reason why it’s a good idea to cut out as many unnecessary dependencies as possible for a given test. That way a problem in something unrelated isn’t causing us to have an incomplete picture of what may or may not have issues.
