# manage-zoo
---
### A zoo wants to create an animal management system. You need to design this system using object-oriented programming (OOP) in Python.
### 1. Introduction to Object-Oriented Programming (OOP)
### Your task:
 Define a class called Animal that has the following properties:

 name (animal name)

 species (animal species)

 age (animal age)

 sound (animal sound)

 Then create an instance of this class for a "lion" and print its properties.
***
Class and Function definition:

````
class Animal:
    def __init__(self, name, species, age, sound):
        self.name = name
        self.species = species
        self.age = age
        self.sound = sound

    def print_info(self):
        print("Name:", self.name)
        print("Species:", self.species)
        print("Age:", self.age, "years")
        print("Sound:", self.sound)

lion = Animal("Leo", "Lion", 5, "Roar")
lion.print_info()
````