import math

n = int(input("Enter a number: "))
temp = n
sum = 0

while temp > 0:
    digit = temp % 10
    sum += math.factorial(digit)
    temp //= 10

if sum == n:
    print("Strong Number")
else:
    print("Not a Strong Number")
