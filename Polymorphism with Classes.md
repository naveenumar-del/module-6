Polymorphism with Classes


🎯 AIM

To create two specific classes — Beans and Mango. Then, create a generic function that can accept any object and determine its type (Fruit or Vegetable) and color, using polymorphism.


🧠 ALGORITHM

Create Class Beans:


Define type() method that prints "Vegetable".

Define color() method that prints "Green".

Create Class Mango:

Define type() method that prints "Fruit".

Define color() method that prints "Yellow".

Define Generic Function func(obj):

Call obj.type() and obj.color() — this works with both Beans and Mango objects, showcasing polymorphism.

Create Objects:

Instantiate Beans and Mango.

Pass them to func() and execute the program.


💻 Program
  class Beans ():
  
     def type(self):
        print("Vegetable")
     def color(self):
        print("Green")

  class Mango ():
  
     def type(self):
        print("Fruit")
     def color(self):
        print("Yellow")

     def func(obj):
        obj.type()
        obj.color()

  obj_beans = Beans()
  obj_mango = Mango()
  func(obj_beans)
  func(obj_mango)

Output

<img width="530" height="304" alt="image" src="https://github.com/user-attachments/assets/7513afb7-f801-4a5a-8ecd-4f51053e952d" />


Result

Thus the program To create two specific classes — Beans and Mango. Then, create a generic function that can accept any object and determine its type (Fruit or Vegetable) and color, using polymorphism is executed successfully.
