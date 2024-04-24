# Python-Functions

Exercise 1 – Datetime
You received the following date in string format.
date_string = "Feb 25 2018 6:30PM"
Please convert it into Python’s DateTime object and print it to the console.
Expected Output:
2018-02-25 18:30:00
After converting it, do the following:
1. Find the day of the week of this given date
2. Add a week (7 days) and 12 hours to this given date, and convert it back to the original string
format.

Exercise 2 – Rock, Paper, Scissors
In this exercise, you are going to practice using conditionals (if, elif, else). You will write a small program that
will determine the result of a rock, paper, scissors game, given Player 1 and Player 2’s choices. Your program
will print out the result. Here are the rules of the game:
First create a truth table for all the possible choices for player 1 and 2, and the outcome of the game. This
will help you figure out how to code the game!
The program should ask the user for 2 inputs (what python function can take inputs?). For example, after
running your code, the console should first print
Player 1?
for the first input. After you enter the “rock”, and similarly repeat for the second input, the console should
display the answer as follows:
Player 1? rock
Player 2? scissors
Player 1 wins.
The only valid inputs are rock, paper, and scissors. If you enter anything else, your program should output
“This is not a valid object selection”. Use the truth table you created to help with creating the conditions for
your if statement(s).
Note: If you have a long condition in your if statement, and you want to split it into multiple lines, you can
either enclose the entire expression in parenthesis, e.g.
if (player1 == ‘rock’ and
player2 == ‘scissors’):
print ‘Player 1 wins.’
Or, you can use the backslash symbol to indicate to Python that the next line is still part of the previous line
of code, e.g.
if player1 == ‘rock’ and\
player2 == ‘scissors’:
print ‘Player 1 wins.’
Use whichever form you feel comfortable using. When you are done coding, please run a few tests to make
sure your program runs correctly.

Exercise 3 – For & While Loops
1. Using a for loop, write a program that prints out the decimal equivalents of 1/2, 1/3, 1/4, . . . ,
1/10.

2. Create a for loop script with exactly 2 lines of code that generate a sequence of integer numbers
starting from 2 up to (and including) 26 incremented by 2 (look up the range() function).
Expected output:

3. Complete the following code block to calculate the sum of all the integer multipliers of 11 between
(and including) the number 0 and up to (not including) the number 10, i.e.,
Here is a code template:
Expected output:
Exercise 4 – Encoding & Decoding
You are analyzing an unstructured text dataset that contains a cluster of comments by 31 million fans on an
online soccer forum about the 2018 FIFA World Cup (host nation is Russia). Using market research, the
cluster of comments has been summarized into a single representative comment and provided to you in a
file using the Python byte native format as follows (for your convenience, the message is:
b'\xd0\x9f\xd0\xb5\xd1\x80\xd1\x83 \xd0\xbf\xd0\xbe\xd0\xb1\xd0\xb5\xd0\xb4\xd0\xb8\xd1\x82!'):
You need to decode the above message to Russian to create a report for your consulting project. Then, you
need to copy and paste the Russian characters for this message into Google Translate
(https://translate.google.com/) in order to translate the comment into English. Can you find out what the
message says in English? Write your answer as a Python comment statement.
Hint: Create a variable name and assign its value as the Python byte format message. Then use the decode()
function using Unicode format as seen in class lectures. You can then follow the remaining instructions in
this question to arrive at the correct English translation. How do you know you got it right? The correct
answer contains three English words (written in English) and one exclamation point.
