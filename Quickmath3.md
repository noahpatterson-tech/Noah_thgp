Define what Object-Oriented Programming (OOP) is in your own words.
Object-Oriented Programming (OOP) is a way of writing programs by creating objects that contain both data (attributes) and actions (methods). It helps organize code and makes it easier to reuse and maintain.
How many pillars are there in OOP? Name all of them.
There are 4 pillars of Object-Oriented Programming:
Encapsulation
Abstraction
Inheritance
Polymorphism
What are the main parts of a class?
The main parts of a class are:
Attributes (variables) – store information about the object.
Methods (functions) – define what the object can do.
Constructor (__init__) – initializes the object's attributes when it is created.
How do we create a class in Python?
We create a class in Python using the class keyword.
Example:

class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def drive(self):
        print("The car is driving.")
What is the difference between a class and an object?
A class is a blueprint or template for creating objects.
An object is a real instance of a class with its own data and behavior.
Example:
class Car:
    pass

my_car = Car()  # my_car is an object created from the Car class
