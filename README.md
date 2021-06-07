# Shank
def add(a, b):
    answer = a + b
    print("The Addition of the given inputs is", answer)

def sub(a, b):
    answer = a - b
    print("The Subtraction of the given inputs is", answer)

def mul(a, b):
    answer = a * b
    print("The Multiplication of the given inputs is",answer)

def div(a, b):
    answer = a / b
    print("The Division of the given inputs is,answer)

print("Welcome to Calculator")

a = int(input("Enter the first number:"))
b = int(input("Enter the second number:"))
print("Choose from the following. e.g. 1|2|3|4")
print("1,Addition")
print("2,Subtraction")
print("3,Multiplication")
print("4,Division")

o=int(input("Select an operation to perform"))

if o== 1:
   add(a,b)
elif o==2:
    sub(a,b)
elif o==3:
    mul(a,b)
else:
    div(a,b)
