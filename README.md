# exp-7

# Aim

The objective of this experiment is to understand and implement the while loop in Python.
The while loop is used to repeatedly execute a block of code as long as a given condition remains true.

This notebook demonstrates different practical applications of the while loop including:

1]Iteration and counting

2]Factorial calculation

3]Fibonacci series

4]Number reversal

5]Palindrome checking

6]Break statement usage

7]Searching elements in a list

# Program Descriptions & Algorithms

1) Cell 1 – Print Numbers from 1 to 5

Explanation:
Initializes i to 1 and prints numbers until i becomes 6.

Algorithm:

1]Start with i = 1

2]Check if i < 6

3]Print i

4]Increment i

5]Repeat until condition fails

2) Cell 2 – Print Numbers from 1 to N

Explanation:
Prints numbers dynamically based on user input.

Algorithm:

1]Input value of N

2]Initialize i = 1

3]While i ≤ N:

4]Print i

5]Increment i

3) Cell 3 – Factorial of a Number

Explanation:
Computes factorial using repeated multiplication.

Algorithm:

1]Input number n

2]Initialize fact = 1

3]While n > 0:

4]Multiply fact by n

5]Decrement n

7]Display result

4) Cell 4 – Fibonacci Series(Fixed Terms)

Explanation:
Generates Fibonacci numbers up to n terms.

Algorithm:

1]Initialize a = 0, b = 1

2]Repeat n times:

3]Print a

4]Compute next term c = a + b

5]Update values

5) Cell 5 – Fibonacci Series (Limit Based)

Explanation:
Stops when values exceed user-defined limit.

Algorithm:

1]Input limit

2]While Fibonacci value ≤ limit:

3]Print value

4]Update sequence

6) Cell 6 – Reverse a Number

Explanation:
Extracts digits and rebuilds reversed number.

Algorithm:

1]Input number

2]While number > 0:

3]Extract last digit

4]Append to reversed number

5]Remove last digit

7) Cell 7 – Palindrome Check (Number)

Explanation:
Reverses number and compares with original.

Algorithm:

1]Store original number

2]Reverse digits using loop

3]Compare original and reversed

4]Display result

8) Cell 8 – Palindrome Check (String – Positive Case)

Uses two-pointer comparison.

Algorithm:

1]Set i = 0, j = length - 1

2]While i < j:

3]Compare characters

4]If mismatch → Not palindrome

5]Otherwise → Palindrome

9) Cell 9 – Palindrome Check (String – Negative Case)

Same logic, different input.

10) Cell 10 & 11 – Palindrome Using Slicing

Explanation:
Python slicing reverses string instantly.

Algorithm:

1]Input string

2]Reverse using slicing

3]Compare strings

11) Cell 12 – Count Digits in a Number

Logic Issue Note:
count variable must be incremented (missing in code).

Correct Algorithm:

1]Initialize count = 0

2]While number > 0:

3]Divide number by 10

4]Increment count

5]Print count

12) Cell 13 – Break Statement Demo

Explanation:
Loop terminates when condition met.

Algorithm:

1]Start loop

2]Print values

3]If i == 3 → break

13) Cell 14 – Linear Search Using While Loop

Explanation:
Searches list until element found.

Algorithm:

1]Input key

2]Start index i = 0

3]While i < length:

4]Compare element

5]If match → print & break

6]Else → Not found

# Conclusion

This experiment successfully demonstrates how the while loop can be used for:

 Repetitive computations
 Sequence generation
 Digit manipulation
 Conditional termination
 Searching operations

The while loop provides flexible control when the number of iterations is not known beforehand.
