# Experiment-07:
# Aim: Study of while loops in Python
# Theory:
The while loop in Python is used to execute a block of statements repeatedly as long as a given condition is true.
It is an entry-controlled loop because the condition is checked before the execution of the loop body.
If the condition evaluates to True, the statements inside the loop are executed.
If the condition becomes False, the loop terminates.
The syntax of a while loop begins with the keyword while followed by a condition and a colon.
Proper indentation is required to define the body of the loop.
Initialization of loop control variables is done before the loop starts.
Updation of the control variable is necessary inside the loop to avoid infinite loops.
An infinite loop occurs when the condition never becomes False.
The while loop is mainly used when the number of iterations is not known in advance.
It is suitable for problems like factorial calculation and Fibonacci series generation.
The loop can be controlled using break and continue statements.
The break statement terminates the loop immediately.
The continue statement skips the current iteration and moves to the next iteration.
Python also allows the use of an else block with a while loop.
The else block executes when the loop finishes normally without a break.
Nested while loops can also be used to solve complex problems.
Care must be taken to update the loop variable correctly.
While loops help in reducing code repetition and improving efficiency.
Thus, the while loop is an important control structure in Python programming.

# Algorithm:
1. Algorithm to Print Numbers from 1 to 5
Start
Initialize i = 1
While i <= 5, do:
Print i
Increment i by 1
Stop

 2. Algorithm to Print Numbers from 1 to N
Start
Read value of n
Initialize i = 1
While i <= n, do:
Print i
Increment i by 1
Stop

 3. Algorithm to Find Factorial of a Number
Start
Read number n
Set fact = 1
While n > 0, do:
fact = fact × n
Decrement n by 1
Print fact
Stop

4. Algorithm to Print Fibonacci Series (First N Terms)
Start
Read value n
Initialize a = 0, b = 1, i = 1
While i <= n, do:
Print a
c = a + b
a = b
b = c
Increment i by 1
Stop

 5. Algorithm to Print Fibonacci Series up to a Limit
Start
Read limit
Initialize a = 0, b = 1
While a <= limit, do:
Print a
Swap values: a = b, b = a + b
Stop

 6. Algorithm to Reverse a Number
Start
Read number n
Set rev = 0
While n > 0, do:
digit = n % 10
rev = rev × 10 + digit
n = n // 10
Print rev
Stop

 7. Algorithm to Check Number Palindrome
Start
Read number num
Store original value in temp
Set rev = 0
While num > 0, do:
rev = rev × 10 + (num % 10)
num = num // 10
If temp == rev
Print “Palindrome”
Else
Print “Not Palindrome”
Stop

 8. Algorithm to Check String Palindrome
Start
Read string st
Reverse the string
If original string equals reversed string
Print “Palindrome”
Else
Print “Not Palindrome”
Stop

 9. Algorithm to Count Number of Digits
Start
Read number num
Set count = 0
While num > 0, do:
Increment count
num = num // 10
Print count
Stop

 10. Algorithm to Search an Element in a List
Start
Initialize list nums
Read element key
Set i = 0
While i < length of list, do:
If nums[i] == key
Print index
Stop
Increment i
If element not found, print “Element not found”
Stop
 11. Algorithm to Print Odd Numbers from 1 to 10
Start
Set i = 1
While i <= 10, do:
If i is odd, print i
Increment i
stop


# Conclusion:
In conclusion we studied the use of while loops in python and used it programming and solving different questions.
