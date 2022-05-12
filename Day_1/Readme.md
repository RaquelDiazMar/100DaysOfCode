## Working with Variables in Python to Manage Data - Beginner

print(len("95637+12"))
Output: 8


score = 67
if score < 80 and score > 70:
    print("A")
elif score < 90 or score > 80:
    print("B")
elif score > 60:
    print("C")
else:
    print("D")
Output: B


def a_function(a_parameter):    
    a_variable = 15    
    return a_parameter 
a_function(10)
print(a_variable)

Output: NameError


def outer_function(a, b):
    def inner_function(c, d):
        return c + d
    return inner_function(a, b)
 
result = outer_function(5, 10)
print(result)

Output: 15


def foo(a, b=4, c=6):
    print(a, b, c)
 
foo(20, c=12)
Output: 20, 4, 12


numbers = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]
result = [num + 3 for num in numbers if num % 2 == 0]
print(result)
Output: [5, 11, 37]
