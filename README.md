<img width="750" height="606" alt="image" src="https://github.com/user-attachments/assets/de50689d-41f4-42d0-8237-1df89bad3476" />

# Using a virtual environment to resolve package version conflicts

Package version conflicts can become an issue when running Python's scripts on a local machine. 

Package version conflicts occur when local package versions don't match script requirements.

One can solve this by creating a virtual environment to run Python's scripts that require packages.

A virtual environment is a directory which holds a Python Interpreter and a set of installed packages.

In many instances, there is a requirements.txt file that keeps track of the script's required packages.

Otherwise remove the third line below and install the packages manually by using '```pip install PACKAGE_NAME```'

Below are a set of commands to run a virtual environment on a local machine and install the dependencies.

Commands for Linux and Mac:
```
python3 -m venv venv
source venv/bin/activate
python -m pip install -r requirements.txt
```

Commands for Windows (Command Prompt):
```
python -m venv venv
venv\scripts\activate
python -m pip install -r requirements.txt
```

<img width="554" height="554" alt="image" src="https://github.com/user-attachments/assets/e760f150-b075-48a1-a48d-41661e7747b2" />

<b>POOP</b> is not a technical term

# Object Oriented Programming

Objects - defines a set of attributes (variables) and methods (functions) that all objects created from it will share.

```
dog = Dog("Buddy", "Golden Retriever")
print(dog.name) # Output: Buddy
print(dog.breed) # Output: Golden Retriever
print(dog.bark()) # Output: Buddy says Woof!
 ```
       
Classes - is an individual instance of a class.

```
class Dog:
    # The initializer method sets up the object's attributes
    def __init__(self, name, breed):
        self.name = name          # Instance attribute
        self.breed = breed        # Instance attribute

    # A method (a function belonging to the class)
    def bark(self):
        return f"{self.name} says Woof!"

 ```

Encapsulation - the process of hiding complex implementation details and exposing only the essential features of an object

Abstraction - the process of hiding complex implementation details and exposing only the essential features of an object

Polymorphism - allows different classes to have methods with the same name, but with behaviors tailored to each specific class

Inheritance - allows a new class (child class) to adopt the attributes and methods of an existing class (parent class)

<img width="500" height="375" alt="image" src="https://github.com/user-attachments/assets/060863b6-df58-4d6e-afc8-1b8475b017ef" />

# Data Structures 

Built-in Core Data Structures
List ([]) - An ordered, mutable collection that allows duplicate elements. Great for general-purpose sequential data

Tuple (()) - An ordered, immutable collection that allows duplicates. Ideal for fixed data that shouldn't change (e.g., coordinates)

Dictionary ({key: value}): An insertion-ordered, mutable collection of key-value pairs. Keys must be unique and hashable. Perfect for fast lookups

Set ({}) - An unordered, mutable collection of unique elements. Highly optimized for mathematical operations like unions, intersections, and membership testing

<img width="497" height="665" alt="image" src="https://github.com/user-attachments/assets/a634eda0-1e0f-40ad-829d-0f8c978b3df7" />

# Sorting Algorithms
