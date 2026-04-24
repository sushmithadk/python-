#number comparision grading system and decision making
# Number comparison
x = int(input("Enter first number: "))
y = int(input("Enter second number: "))
if x > y:
    print("First number is greater")
elif x < y:
    print("Second number is greater")
else:
    print("Both are equal")
print()
# Grading system
marks = int(input("Enter marks: "))
if marks >= 90:
    print("Grade: A")
elif marks >= 75:
    print("Grade: B")
elif marks >= 50:
    print("Grade: C")
else:
    print("Grade: F")
/// output
Enter first number: 8
Enter second number: 9
Second number is greater
Enter marks: 91
Grade: A  ///
