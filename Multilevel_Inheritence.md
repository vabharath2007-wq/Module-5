# Multilevel Inheritance Example in Python

## 🎯 Aim

Write a Python program to Get the name, age and salary of a person and display using Multilevel inheritance.

## 🧠 Algorithm

1. create a class name having a method get that gets the user input for name
2. create a class age inheriting the class name that gets the age user input
3. create a class salary inheriting class age that gets the salary as user input
4. class salary has another method show to print name,age,and salary
5. call the salary class and call all the methods using salary class


## Program

class name:
    
    def get(self):
        
        self.name=input()
        
class age(name):
    
    def ag(self):
        
        self.age=int(input())
        
class salary(age):
    
    def sal(self):
        
        self.salary=int(input())

    def show(self):
        
        print(f"{self.name} {self.age} {self.salary}")
        
o=salary()

o.get()

o.ag()

o.sal()

o.show()

## Sample Output

<img width="588" height="168" alt="image" src="https://github.com/user-attachments/assets/8bb02f58-a8bc-4752-ba4f-dd9d46d1f876" />

## Result
Thus the program is simulated sucessfully
