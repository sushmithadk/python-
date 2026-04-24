def calculator():
    """Simple command-line calculator."""
    ops = {'+': lambda x, y: x + y,
           '-': lambda x, y: x - y,
           '*': lambda x, y: x * y,
           '/': lambda x, y: x / y if y != 0 else "Error!"}

    print("Options: +, -, *, /")
    try:
        n1 = float(input("First number: "))
        op = input("Operation: ")
        n2 = float(input("Second number: "))
        result = ops.get(op)(n1, n2)
        print(f"Result: {result}")
    except (ValueError, TypeError, ZeroDivisionError):
        print("Invalid input.")

# To run: calculator()
