# JS-ASSIGNMENT
Q1-Digit Gatekeeper
Approach:
It uses a for loop to iterate through every integer x from L to R inclusive. 
It first filters numbers using the modulo operator to ensure they are divisible by K, and converts the number to a string to verify it does not contain the character "0". 
Then for valid candidates, it calculates the digitSum by iterating through the string characters and then calls a helper function to determine if that sum is a prime number. 
If all criteria are met, a counter is incremented and the final result is displayed via an alert().
