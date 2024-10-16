# hello-world
import random(Yundi Zhang write
name = input("Enter your name: ")

favorite_number = int(input(f"Hi {name}, what's your favorite number? "))

random_multiplier = random.randint(1, 10)  # Get a random number between 1 and 10
result = favorite_number * random_multiplier

if favorite_number % 2 == 0:
    number_type = "even"
else:
    number_type = "odd"

print(f"Nice to meet you, {name}!")
print(f"Your favorite number, {favorite_number}, is {number_type}.")
print(f"By the way, if we multiply your favorite number by {random_multiplier}, we get {result}. Cool, right?")
