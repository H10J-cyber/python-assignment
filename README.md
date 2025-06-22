# python-assignment
# Assignment 
# Step 1: Take input from user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Step 2: Perform operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

# Division with check for zero
if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined (cannot divide by zero)"
# Step 3: Show results
print("Results:")
print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Division:", division)
'''
Fname= input("Enter your name: ")
Lname= input("Enter your surname: ")
full_name= Fname + " " + Lname
print(f"\nHello, {full_name}!, Welcome to Python program." )
