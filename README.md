# CMPINF-0010-LAB-6 Group Members: Chase Marsalko and Luia Castro

Overview:
This lab introduces how to use user input and string concatenation in Python. The program asks the user for their name and a number, then prints both together as one string.

Code:

name = input("What is your name?")
num = input("Type out a number.")
print(name + num)


How It Works:

The program asks the user to enter their name using the input() function.

It then asks the user to enter a number, which is also stored as a string.

The print() statement combines the name and number using the + operator and displays them together.

Example Output:

What is your name? Chase
Type out a number. 6
Chase6


Key Concepts:

The input() function always returns a string.

The + operator joins (concatenates) two strings.

To use the number in calculations, you would need to convert it with int() or float().

Example Extension:

name = input("What is your name? ")
num = int(input("Type out a number: "))
print(name, num + num)
