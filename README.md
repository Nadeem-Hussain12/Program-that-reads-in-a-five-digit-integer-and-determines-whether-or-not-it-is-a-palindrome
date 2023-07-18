# Program-that-reads-in-a-five-digit-integer-and-determines-whether-or-not-it-is-a-palindrome
The code prompts the user to enter a number by displaying the message "Enter a five-digit number: " using the input() function. The entered value is stored in the variable number.

The [::-1] slicing syntax is used to reverse the string representation of number. It creates a new string that is the reverse of the original input.

The code then checks if number is equal to its reverse by comparing it with number[::-1].

If the comparison (number == number[::-1]) evaluates to True, it means the number is a palindrome because it reads the same forwards and backwards.

In that case, the code block under the if statement is executed.

Inside the if block, the code prints a message indicating that the entered number is a palindrome using the print() function. It includes the original number value in the output message.

If the comparison (number == number[::-1]) evaluates to False, it means the number is not a palindrome because it does not read the same forwards and backwards.

In that case, the code block under the else statement is executed.

Inside the else block, the code prints a message indicating that the entered number is not a palindrome using the print() function. It also includes the original number value in the output message.
