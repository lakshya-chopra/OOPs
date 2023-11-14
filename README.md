# OOPs
This is a small documentation listing major Object oriented programming concepts and keywords with brief explanations (with codes implemented in python).

- **Class** : A Class is a blueprint/design having methods, variables and (or) other properties of an object of a particular kind. Ex: a Dog class which defines the properties of a dog, such as it's breed, height, weight, age, name and more. Every dog associated with this class will use the same properties but with different attributes, thus, here we utilised classes to organize and list all the dogs in a proper manner.

- **Constructor** : This is a special method used inside classes to create an object, it also takes in arguments to define the properties of that object. In python, the "__new__" method is given the task of creating an instance/object, whereas the __init__ method is used to initialise the instance's attributes.

- **Object** : An object is an actual implementation of a class with defined attributes.

# Pillars of OOPS  

  - **Encapsulation** : It is a way of packaging all the related functions and variables together and not exposing it to other parts of the code, essentially the data is encapsulated i.e. hidden from the world.     Thus, it doesn't affect the methods and variables in other parts of the code and also keeps the internals (i.e. the data encapsulated) safe! It binds the data to a single place/unit.
  - **Abstraction** : This is a process in which we display only the relevant information and hide the unneccesary or irrelevant details from the user. Thus, it focuses on only the output of a function, and not how the task is done inside.
  - **Inheritance** : This allows a class (child class) to inherit properties and methods from a parent class, which allows us to reduce redundancy and duplication in the code, and benefits in  organizing the things better.
  - **Polymorphism** : This means that the same interface can perform different operations, for ex: two functions may have the same name but different number of paramaters (method overloading) or they may have the same name and parameters, but different body (method overriding).

# Basic Implementation in Python:
  ```bash
  class Dog: #class

    def __init__(self, name, breed, colour, age): #not a constructor, '__new__' is, which is not called explicitily here.

        #Attributes of the object
        self.name = name

        self.breed = breed

        self.colour = colour

        self.age = age

    def print_details(self): #instance method

        print(f'Hi, my name is {self.name}, and I am {self.age} years old')


d1 = Dog('Joey','Labrador','Brown',5)
#calling the constructor (Explicit Call)
#d1 is the reference to the object.

d1.print_details() #calling the instance method

    
```

  **Helpful links**: <br>
    [1.](https://stackoverflow.com/questions/16014290/simple-way-to-understand-encapsulation-and-abstraction)\
    [2.](https://www.reddit.com/r/explainlikeimfive/comments/yoy3f/eli5_the_difference_between_abstraction_and/)
  
