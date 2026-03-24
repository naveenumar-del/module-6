 Method Overriding-Fish and Shark Class Inheritance in Python

🧠 AIM:

To write a Python program that demonstrates class inheritance by creating a parent class Fish with a method type, and a child class Shark that overrides the type method.


📋 ALGORITHM:

Define the Fish class with a method named type() that prints "fish".

Define the Shark class as a subclass of Fish, and override the type() method to print "shark".

Create an instance of the Fish class named obj_goldfish.

Create an instance of the Shark class named obj_hammerhead.

Use a for loop to iterate over both objects.

Within the loop, call the type() method using the loop variable.

Output will demonstrate method overriding: printing "fish" and "shark" accordingly.


💻 PROGRAM:
class Fish:

    def type(self):
        print("fish")

class Shark:

	def type(self):
	    print("shark")

seas=(Fish(),Shark())

for sea in seas:

    sea.type()

OUTPUT

<img width="842" height="311" alt="image" src="https://github.com/user-attachments/assets/ea9d763a-f8e0-4d74-801d-a38c1a538714" />


RESULT

Thus the program that demonstrates class inheritance by creating a parent class Fish with a method type, and a child class Shark that overrides the type method is executed successfully.
