# Multiplication table
n = int(input("Enter a number: "))
for i in range(1, 11):
    print(f"{n} x {i} = {n * i}")

# Sequence sum
m = int(input("Enter a number: "))
total = 0
for i in range(1, m + 1):
    total += i
print("Sum of sequence =", total)

/// output
Enter a number: 20
20 x 1 = 20
20 x 2 = 40
20 x 3 = 60
20 x 4 = 80
20 x 5 = 100
20 x 6 = 120
20 x 7 = 140
20 x 8 = 160
20 x 9 = 180
20 x 10 = 200
Enter a number: 10
Sum of sequence = 55 ///
