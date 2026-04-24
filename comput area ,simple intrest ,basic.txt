#comput area ,simple intrest ,basic arithmatic operation

# Area of a rectangle
length = float(input("Enter length: "))
width = float(input("Enter width: "))
print("Area =", length * width)
print()
# Simple Interest
p = float(input("Enter principal: "))
r = float(input("Enter rate of interest: "))
t = float(input("Enter time in years: "))
print("Simple Interest =", (p * r * t) / 100)
print()
# Arithmetic expression
a = int(input("Enter a number: "))
b = int(input("Enter another number: "))
print("Expression result =", (a + b) * (a - b))
print()

///output
Enter length: 20
Enter width: 7
Area = 140.0
Enter principal: 100
Enter rate of interest: 10
Enter time in years: 2
Simple Interest = 20.0
Enter a number: 3
Enter another number: 5
Expression result = -16///
