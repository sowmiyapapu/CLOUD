# CLOUD# Addition and subtraction function
def add_subtract(a, b):
    addition = a + b
    subtraction = a - b
    return addition, subtraction

# Example usage
num1 = 10
num2 = 5

add, sub = add_subtract(num1, num2)
print("Addition:", add)
print("Subtraction:", sub)
