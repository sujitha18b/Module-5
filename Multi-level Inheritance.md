# Exp.No: 5D
## Multi-level Inheritance


### AIM  
To write a Python program to get the name, age, and ID of a person and display them using multilevel inheritance.


### ALGORITHM

1. Define the `Person` class:
   - Inside the `Person` class, define the `__init__` method (constructor) with two parameters: `name` and `age`.
   - Inside the `__init__` method, assign the `name` to `self.name` and `age` to `self.age`.

2. Define the `PersonDetails` class that inherits from the `Person` class:
   - Inside the `PersonDetails` class, define the `__init__` method (constructor) with three parameters: `name`, `age`, and `person_id`.
   - Inside the `__init__` method, call the `__init__` method of the `Person` class using `super()` to initialize `name` and `age`.
   - Assign `person_id` to `self.person_id`.

3. Define the `DisplayDetails` class that inherits from the `PersonDetails` class:
   - Inside the `DisplayDetails` class, define the `__init__` method (constructor) with three parameters: `name`, `age`, and `person_id`.
   - Inside the `__init__` method, call the `__init__` method of the `PersonDetails` class using `super()` to initialize `name`, `age`, and `person_id`.

4. Inside the `DisplayDetails` class, define the `show_details` method:
   - Inside the `show_details` method, return a formatted string with `self.name`, `self.age`, and `self.person_id`.

5. Prompt the user to enter `name` (string), `age` (integer), and `person_id` (integer).

6. Create an instance `person` of the `DisplayDetails` class, passing `name`, `age`, and `person_id` to the constructor.

7. Call the `show_details` method on the `person` object and print the result.

8. Terminate the program.


### PROGRAM

class A:         <br />
    def get(self):      <br />
        self.a = input()  <br />
        self.b = int(input())    <br />
        self.c = int(input())   <br />
        self.d = int(input())  <br />
        self.e = int(input())    <br />
        self.f = int(input())   <br />
class B(A): <br />
    def display(self): <br />
        A.get(self) <br />
        print("Name: ",self.a, end = " ") <br />
        print("Rollno: ",self.b,end = " ")  <br />
        self.tot = self.c + self.d + self.e + self.f <br />
        print("Total Marks out of 400: ",self.tot) <br />
obj = B() <br />
obj.display()

### OUTPUT

![Screenshot 2025-05-01 123652](https://github.com/user-attachments/assets/7b846805-5274-45e2-a9f9-3a5b3520c3ac)

### RESULT

Thus, the given python program is implemented and executed sucessfully.
