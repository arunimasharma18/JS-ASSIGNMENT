# JS-ASSIGNMENT
Q1-Digit Gatekeeper
# Approach:
It uses a for loop to iterate through every integer x from L to R inclusive. 
It first filters numbers using the modulo operator to ensure they are divisible by K, and converts the number to a string to verify it does not contain the character "0". 
Then for valid candidates, it calculates the digitSum by iterating through the string characters and then calls a helper function to determine if that sum is a prime number. 
If all criteria are met, a counter is incremented and the final result is displayed via an alert().
# 
Q2-Roll Seed Lock
# Approach:
Logic applies a mathematical transformation to an input N exactly three times, branching based on whether the number is even or odd. 
After loop, it uses Math.floor() and modulus to isolate the middle digit of the final result. 
The code then alerts YES only if the number is a three-digit integer and the middle digit matches the user's initial seed.
#
Q3-Mirror Corridor
# Approach:
The code finds the smallest non-negative integer $X$ by iterating through a loop from 0 to 100,000. 
Checking if N + X satisfies two conditions. It uses the modulus operator to verify divisibility by K and string methods to determine if the sum is a palindrome. Once the first valid X is identified, it is displayed via alert(); otherwise, -1 is returned.
#
Q4-Fare Calculator
# Approach:
The code calculates a ride fare by applying sequential conditional logic to a base calculation of base + 7 * distance.
It adjusts the total based on thresholds for lateness and distance, uses the modulus operator to either add or subtract the seed value.
It finally applies Math.ceil() to round the result to the nearest multiple of 5.
#
Q5-Skipping Numbers
# Approach:
This code uses a while loop to find the smallest integer m such that the sum of numbers from 1 to m reaches at least N. 
It utilizes an if statement and the modulo operator to skip any values of m that are divisible by seed + 2 before alerting the final count and sum.
#
Q6-Contest Score Judge
# Approach:
The code calculates a contest score using the weighted formula 3a + b - 2c and applies conditional rules to ensure the result is non-negative and penalized if total submissions exceed 50.
It then uses an if/else structure to compare the final score against a threshold of 60, alerting the score along with a "PASS" or "FAIL" status.
#
