Python OOP: Encapsulation with Private Members


🎯 AIM

To implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth.


🧠 ALGORITHM

Define the Class:

Create a class Rectangle with two private attributes: __length and __breadth.
Initialize Variables:

Use the __init__() constructor to set initial values for __length and __breadth.
Print Values:

Display the private variables from within the class to demonstrate access.
Instantiate the Object:

Create an object of the Rectangle class to trigger the constructor.

💻 Program
  class Rectangle:
  
    __length = 0 
    __breadth = 0
    def __init__(self):
      self.__length = 5
      self.__breadth = 3
      print(self.__length)
      print(self.__breadth)
   
  obj = Rectangle()

Output

<img width="305" height="146" alt="image" src="https://github.com/user-attachments/assets/366052a0-a5e9-4d2d-9074-095e3b35fee1" />


Result

Thus the program to implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth is executed successfully.
