# Random-numbers-generator
import random

num1 = int(input("Enter a number: "))
num2 = int(input("Enter a number: "))
target = 0

while target < 6:    
    target += 1
    print(random.randrange(num1,num2), end=" ")
