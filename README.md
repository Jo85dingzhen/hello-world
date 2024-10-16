# hello-world



# Yundi Zhang write
# Import the random module to generate random numbers(write by Andre Juntao Hu)
import random

name = input("Enter your name: ")

favorite_number = int(input(f"Hi {name}, what's your favorite number? "))
# Generate a random integer between 1 and 10 and store it(write by Andre Juntao Hu)
random_multiplier = random.randint(1, 10)  

result = favorite_number * random_multiplier
# Check if favorite_number is even or odd(write by Andre Juntao Hu)
if favorite_number % 2 == 0:
    number_type = "even"
else:
    number_type = "odd"

print(f"Nice to meet you, {name}!")

print(f"Your favorite number, {favorite_number}, is {number_type}.")

print(f"By the way, if we multiply your favorite number by {random_multiplier}, we get {result}. Cool, right?")

