# assignment
n = 10
x = 0 
y = 1 
print(x)
print(y)
next_fib_value = 0
z = 0 

while (z<n-2) :
    next_fib_value = x+y
    print(next_fib_value)
    x = y 
    y = next_fib_value
    z = z + 1
