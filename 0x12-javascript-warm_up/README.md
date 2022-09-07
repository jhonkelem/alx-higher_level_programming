JavaScript Warm Up

js-semistandard-style



This project contains some tasks for learning the basics of JavaScript.



Tasks To Complete

 0. First constant, first print

0-javascript_is_amazing.js contains a script that prints "JavaScript is amazing":



You must create a constant variable called myVar with the value "JavaScript is amazing".

You must use console.log(...) to print all output.

You are not allowed to use var.

 1. 3 languages

1-multi_languages.js contains a script that prints 3 lines:



The first line: "C is fun".

The second line: "Python is cool".

The third line: "JavaScript is amazing".

You must use console.log(...) to print all output.

You are not allowed to use var.

 2. Arguments

2-arguments.js contains a script that prints a message depending on the number of arguments passed:



If no arguments are passed to the script, print "No argument".

If only one argument is passed to the script, print "Argument found".

Otherwise, print "Arguments found".

You must use console.log(...) to print all output.

You are not allowed to use var.

 3. Value of my argument

3-value_argument.js contains a script that prints the first argument passed to it:



If no arguments are passed to the script, print "No argument".

You must use console.log(...) to print all output.

You are not allowed to use var.

You are not allowed to use length.

 4. Create a sentence

4-concat.js contains a script that prints the two arguments passed to it in the following format: <first argument> is <second argument>



You must use console.log(...) to print all output.

You are not allowed to use var.

 5. An Integer

5-to_integer.js contains a script that prints My number: <first argument converted in integer> if the first argument can be converted to an integer.



If the argument can’t be converted to an integer, print "Not a number".

You must use console.log(...) to print all output.

You are not allowed to use var.

You are not allowed to use try/catch.

 6. Loop to languages

6-multi_languages_loop.js contains a script that prints 3 lines: (like 1-multi_languages.js) but by using an array of strings and a loop.



The first line: "C is fun".

The second line: "Python is cool".

The third line: "JavaScript is amazing".

You must use console.log(...) to print all output.

You are not allowed to use var.

You are not allowed to use any if/else statement.

You can use only one console.log.

You must use a loop (while, for, etc.).

 7. I love C

7-multi_c.js contains a script that prints "C is fun" x times.



Wherex is the first argument of the script.

If the first argument can’t be converted to an integer, print "Missing number of occurrences".

You must use console.log(...) to print all output.

You are not allowed to use var.

You can use only two console.log.

You must use a loop (while, for, etc.).

 8. Square

8-square.js contains a script that prints a square.



The first argument is the size of the square.

If the first argument can’t be converted to an integer, print "Missing size".

You must use the character X to print the square.

You must use console.log(...) to print all output.

You are not allowed to use var.

You must use a loop (while, for, etc.).

 9. Add

9-add.js contains a script that prints the addition of 2 integers.



The first argument is the first integer.

The second argument is the second integer.

You have to define a function with this prototype: function add(a, b).

You must use console.log(...) to print all output.

You are not allowed to use var.

 10. Factorial

10-factorial.js contains a script that computes and prints a factorial.



The first argument is integer (argument can be cast as integer) used for computing the factorial

Factorial of NaN is 1.

You must do it recursively.

You must use a function.

You must use console.log(...) to print all output.

You are not allowed to use var.

 11. Second biggest!

11-second_biggest.js contains a scrpt that searches the second biggest integer in the list of arguments.



You can assume all arguments can be converted to integer.

If no argument passed, print 0.

If the number of arguments is 1, print 0.

You must use console.log(...) to print all output.

You are not allowed to use var.

 12. Object

12-object.js updates a script to replace the value 12 with 89:



You are not allowed to use var.

The script to update:

#!/usr/bin/node

const myObject = {

  type: 'object',

  value: 12

};

console.log(myObject);

/*

YOUR CODE HERE

*/

console.log(myObject);

 13. Add file

13-add.js contains a function that returns the addition of 2 integers.



The function must be visible from outside.

The name of the function must be add.

You are not allowed to use var.

 14. Const or not const

100-let_me_const.js contains a file that modifies the value of myVar to 333.



 15. Call me Moby

101-call_me_moby.js contains a function that executes a function x times.



The function must be visible from outside.

Prototype: function (x, theFunction).

You are not allowed to use var.

 16. Add me maybe

102-add_me_maybe.js contains a function that increments a number and calls a function with the number as its argument.



The function must be visible from outside.

Prototype: function (number, theFunction).

You are not allowed to use var.

 17. Increment object

103-object_fct.js updates a script by adding a new function incr that increments the integer value.



You are not allowed to use var.

The script to update:

#!/usr/bin/node

const myObject = {

  type: 'object',

  value: 12

};

console.log(myObject);

/*

YOUR CODE HERE

*/

myObject.incr();

console.log(myObject);

myObject.incr();

console.log(myObject);

myObject.incr();

console.log(myObject);
