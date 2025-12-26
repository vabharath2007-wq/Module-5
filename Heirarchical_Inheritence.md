# Hierarchical Inheritance in Python

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program

class details:
    
    def get_basic(self):
        self.id=int(input())
        self.name=input()
        self.gender=input()
        
class employee(details):
    
    def get_employee_details(self):
        self.company=input()
        self.department=input()
        
    def display_employee(self):
        print("Employee Object")
        print(f"Id:  {self.id}")
        print(f"Name:  {self.name}")
        print(f"Gender:  {self.gender}")
        print(f"Company:  {self.company}")
        print(f"Department:  {self.department}")
        print()

class patient(details):
    
    def get_patient_details(self):
        self.hospital=input()
        self.department=input()
        
    def display_patient(self):
        print("Patient Object")
        print(f"Id:  {self.id}")
        print(f"Name:  {self.name}")
        print(f"Gender:  {self.gender}")
        print(f"Hospital:  {self.hospital}")
        print(f"Department:  {self.department}")
        
        
emp=employee()

emp.get_basic()

emp.get_employee_details()

emp.display_employee()

pat=patient()

pat.get_basic()

pat.get_patient_details()

pat.display_patient()
      

## Sample Output

<img width="551" height="408" alt="image" src="https://github.com/user-attachments/assets/880c5b76-d94d-4cdb-8cc4-076aa11ee088" />

## Result
Thus the program is simulated sucessfully
