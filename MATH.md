import math

# 1. Basic Arithmetic (Built-in - No import needed)
x = 10
y = 5

print(f"Addition: {x + y}")        # 15
print(f"Subtraction: {x - y}")     # 5
print(f"Multiplication: {x * y}")  # 50
print(f"Division: {x / y}")        # 2.0 (Always returns a float)
print(f"Power (Simple): {x ** 2}") # 100 (x squared)

# 2. Advanced Math (Requires 'import math')
z = 25
negative_num = -10.5

print(f"Square Root: {math.sqrt(z)}")      # 5.0
print(f"Power (Function): {math.pow(2, 3)}") # 8.0 (2 raised to the power of 3)
print(f"Absolute Value: {abs(negative_num)}") # 10.5 (built-in)
print(f"Round Up: {math.ceil(2.1)}")       # 3 (Ceiling)
print(f"Round Down: {math.floor(2.9)}")    # 2 (Floor)
print(f"Value of Pi: {math.pi}")           # 3.14159...
