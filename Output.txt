Outputs of Each Program

Program1: 
Develop a Program in C for the following:
a)    Declare a calendar as an array of 7 elements (A dynamically Created array) to represent 7 days of a week. Each Element of the array is a structure having three fields. The first field is the name of the Day (A dynamically allocated String), The second field is the date of the Day (A integer), the third field is the description of the activity for a particular day (A dynamically allocated String).
b) Write functions create(), read() and display(); to create the calendar, to read the data from the keyboard and to print weeks activity details report on screen

Filename: prgm1.c

Output:
enter weekdayMonday
Enter the date 11
Enter the activityYoga
enter weekdayTuesday
Enter the date 12
Enter the activityYoga
enter weekdayWednesday
Enter the date 13
Enter the activityHIT
enter weekdayThursday
Enter the date 14
Enter the activityStrengthTraining
enter weekdayFriday
Enter the date 15
Enter the activityWeightTraining
enter weekdaySaturday
Enter the date 16
Enter the activityRest
enter weekdaySunday
Enter the date 17
Enter the activityMarathonRun
Weekly Calendar of Activities
-------------------------------------------------------------------------------
Date			 Weekday			 Activity
--------------------------------------------------------------------------------

 11			 Monday			   Yoga

 12			 Tuesday			 Yoga

 13			 Wednesday		 HIT

 14			 Thursday			 StrengthTraining

 15			 Friday			   WeightTraining

 16			 Saturday			 Rest

 17			 Sunday			 MarathonRun


 Program2:
 Develop a Program in C for the following operations on Strings.
a.     Read a main String (STR), a Pattern String (PAT) and a Replace   String (REP)
b.      Perform Pattern Matching Operation: Find and Replace all occurrences of PAT in STR with REP if PAT exists in STR. Report suitable messages in case PAT does not exist in STR

Support the program with functions for each of the above operations. Don't use Built-in functions.

Filename: prgm2.c

Output:
****Run1
Enter a main string 
apple is an apple
Enter a pattern string 
app
Enter a replace string 
coup
The resultant string is
 couple is an couple
Run1

Enter a main string 
apple is an apple
Enter a pattern string 
dfg
Enter a replace string 
coup
Pattern string NOT found**


Program3:
Design, Develop and Implement a menu driven Program in C for the following operations on STACK of Integers (Array Implementation of Stack with maximum size MAX) 
        a. Push an Element on to Stack 
        b. Pop an Element from Stack 
        c. Demonstrate how Stack can be used to check Palindrome 
        d. Demonstrate Overflow and Underflow situations on Stack 
        e. Display the status of Stack 
        f. Exit Support the program with appropriate functions for each of the above operations. 

Filename: prgm3.c

**Output:
STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice1
Enter element  to pushed11
STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice1
Enter element  to pushed22
STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice1
Enter element  to pushed33
STACK OPERATIONS
1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
5.EXIT
 
Enter your choice1
Enter element  to pushed44


STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice1
Enter element  to pushed55
STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice1
Stack Ovreflow
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice3
55
44
33
22
11
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice
2
Element popped 55


 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice2
Element popped 44
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice2
Element popped 33
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice2
Element popped 22
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice2
Element popped 11
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 Enter your choice2
Stack  Underflow
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice4
Enter a number1221
No is palindrome
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice
4
Enter a number1234
No is not a plaidrome
 STACK OPERATIONS

 1. PUSH
 2.POP
 3.DISPLAY
 4.PALINDROME
 5.EXIT
 
Enter your choice
5
**

Program4:
Develop a Program in C for converting an Infix Expression to Postfix   Expression. Program should support for both parenthesized and free parenthesized expressions with the operators: +,-,*,/,%(Remainder),^(Power)  and alphanumeric operands.

Filename: prgm4.c

**Output:

Enter infix expression
((a+b)*c^d)

Postfix ab+cd^***

Program5:
Design,Develop and Implement a Program in C for he following Stack Applications:
a. Evaluation of Suffix expression with single digit operands 
and operators:+,-,*,/,%,^
  b.Solving Tower of  Hanoi problem with n disks.

a.EvaluationofSuffixexpressionwithsingledigitoperandsandoperators:+,-,*,/,%,^

Filename: prgm5a.c

**Output:
Enter the postfix Expression: 62+5*
62+5*
Given sufffix Expression n: 62+5*

Result after Evaluation:40**

Filename: prgm5b.c

**Output:
Enter number of disks
3
 Move disk 1 from S to D
 Move disk 2 from S to T
 Move disk 1 from D to T
 Move disk 3 from S to D
 Move disk 1 from T to S
 Move disk 2 from T to D
 Move disk 1 from S to D**





