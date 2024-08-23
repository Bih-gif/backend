import math

def is_prime(number):
    if number <= 1:
        return False
    for i in range(2, int(math.sqrt(number)) + 1):
        if number % i == 0:
            return False
    return True

#example usage
number=13
result =is_prime(number)
print(result)
# backend
backend project
