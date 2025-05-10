"""
Basic Python Programs Usinf ifeles
-----------------------------------

Problem Statement-1:
Write a Python program that:
1. Takes an integer input from the user.
2. Checks whether the number is even or odd using an if-else statement.
3. Displays the result accordingly.

Problem Statement-2:
Write a Python program that:
1. Uses a for loop to iterate over numbers from 1 to 50.
2. Calculates the sum of all integers in this range.
3. Displays the final sum.
"""

# ----------------------------
# Problem 1: Even or Odd Check
# ----------------------------

# Take input from the user
number = int(input("Enter a number: "))

# Check if the number is even or odd
if number % 2 == 0:
    print(f"{number} is even.")
else:
    print(f"{number} is odd.")

# Sample Output for Problem-1:
# ----------------------------
# Enter a number: 10
# 10 is even.
#
# Enter a number: 7
# 7 is odd.


# ---------------------------------------
# Problem 2: Sum from 1 to 50 Using Loop
# ---------------------------------------

# Initialize sum variable
sum_of_integers = 0

# Loop through numbers from 1 to 50
for num in range(1, 51):
    sum_of_integers += num

# Display the final result
print(f"The sum of integers from 1 to 50 is: {sum_of_integers}")

# Sample Output for Problem-2:
# ----------------------------
# The sum of integers from 1 to 50 is: 1275

                                                      
                                                      




