README 
This lab includes a collection of PHP scripts that practice expressions, branching, and loops, ending with a mini "Student Toolkit" that combines them all. 

How to Run:

Make sure PHP is installed 
(in bash) type "php -v"

Change directory to where you saved the files, from there type out  
"php -S localhost:63342"

open your browser and go to "http://localhost:63342/lab4/"

you can access each script from its path origin

/lab4/01_expressions.php

/lab4/02_branching.php

/lab4/03_loops.php

/lab4/04_grade_form/index.php

/lab4/05_toolkit/index.php

Sample Input/Outputs:

Expressions:
input
a=10 b=3
output
sum=13 prod=30 a=15
14
20
Hello Ada
bool(true)
bool(false)
Entry allowed
Result: Fail/NoScore
6

Branching:

input
http://localhost:63342/lab4/02_branching.php?role=editor&day=Sun&code=404
output
Welcome, editor. Enjoy your weekend! Not Found

Loops:

output
7 14 21 28 35 42 49 56 63 70
First n where sum>100 is 15, sum=105
do...while ran 1 time(s)
Subtotal (skip < 1): 15.7
1
2
Fizz
4
Buzz
...
FizzBuzz
Grade Form:
input
95
output
A

Notes on == vs ===:

== compares values and allows for different types. it will change one type to another allowing it to be compared with one another.

=== compares values and types. if a int and string are being compared it would come back 
