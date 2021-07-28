# Classes and Objects

    Objects are an encapsulation of variables and functions into a single entity.

    Classes are essentially a template to create your objects.

    Objects get their variables and functions from classes.

    Example Class

            class MyClass: variable = “blah”

def function(self): print(“This is a message inside the class.”)

    Notes:
        self in Python is equivalent to this in JavaScript
        class in Python is equivalent to the Constructor(blueprint) in JavaScript
        variable in Python is equivalent to the property in JavaScript (accessed through dot)
        function in Python is equivalent to the method in JavaScript (accessed through dot)

# Thinking Recursively in Python

    typical structure of a recursive algorithm. If the current problem represents a simple case, solve it. If not, divide it into subproblems and apply the same strategy to them
    A recursive function: is a function defined in terms of itself via self-referential expressions.
    This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result

When dealing with recursive functions, keep in mind that each recursive call has its own execution context

    Recursive Data Structures in Python

    A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure

# Python Testing with pytest: Fixtures and Coverage

    Fixtures
        When you're writing tests, you're rarely going to write just one or two. Rather, you're going to write an entire "test suite", with each test aiming to check a different path through your code. In many cases, this means you'll have a few tests with similar characteristics, something that pytest handles with "parametrized tests".

    -But in other cases, things are a bit more complex. You'll want to have some objects available to all of your tests. Those objects might contain data you want to share across tests, or they might involve the network or filesystem. These are often known as "fixtures" in the testing world, and they take a variety of different forms.
        In pytest, you define fixtures using a combination of the pytest.fixture decorator, along with a function definition

    Coverage
        This is all great, but if you've ever done any testing, you know there's always the question of how thoroughly you have tested your code. After all, let's say you've written five functions, and that you've written tests for all of them. Can you be sure you've actually tested all of the possible paths through those functions?
