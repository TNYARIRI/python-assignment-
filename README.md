# python-assignment-



a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
op = input("Enter operation (+, -, *, /): ")

if op == '+':
    print(f"{a} + {b} = {a + b}")
elif op == '-':
    print(f"{a} - {b} = {a - b}")
elif op == '*':
    print(f"{a} * {b} = {a * b}")
elif op == '/':
    if b != 0:
        print(f"{a} / {b} = {a / b}")
    else:
        print("Error: Division by zero")
else:
    print("Invalid operation")

                          
