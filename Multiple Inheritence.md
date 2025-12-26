# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm
1. create a class add with an method addition with instance 'a,b' and return a+b
2. create a class sub with an method subtraction with instance 'a,b'  and return a-b
3. create a class div with an method division with instance 'a,b'  and return a/b
4. create a class clac inheriting classes'add,sub,and div' and pass
5. get user input for a and b
6. call the clac class
7. print the addition,subtraction and division method by calling them



## 💻 Program 

class add:
    
    def addition(self,a,b):
    
        return a+b
    
class sub:
    
    def subtraction(self,a,b):
    
        return a-b
        
class div:
    
    def division(self,a,b):
    
        return a/b
        
class clac(add,sub,div):
    
    pass

a=int(input())

b=int(input())

c=clac()

print(c.addition(a,b))

print(c.subtraction(a,b))

print(c.division(a,b))

## Output Example

<img width="355" height="168" alt="image" src="https://github.com/user-attachments/assets/4efb2bef-24c0-4c13-bdd1-614da11113ae" />

## Result
Thus the program is simulated sucessfully
