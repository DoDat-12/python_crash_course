# Chapter 09 Code Note
## Classes
### Functions
### Syntax
1. Define class from scratch
    ```
   class Dog:
      """A simple attempt to model a dog"""
      def __init__(self, name, age):
         """Initialize name and age attributes"""
         self.name = name
         self.age = age
   
      def sit(self):
         """Simulate a dog sitting in response to a command"""
         print(f'{self.name} is now sitting')
   
   my_dog = Dog('Willie', 6)
   print(f'My dog's name is {my_dog.name}')  # access attributes
   my_dog.sit()  # calling methods
   ```
   > The `self` parameter is required in the method definition, must come first before the other parameters

