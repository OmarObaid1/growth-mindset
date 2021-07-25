# Expressions and operators
## Short-circuit evaluation

As logical expressions are evaluated left to right, they are tested for possible "short-circuit" evaluation using the following rules:

false && anything is short-circuit evaluated to false.

true || anything is short-circuit evaluated to true.



## String operators
In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.

For example,

console.log('my ' + 'string'); 

 console logs the string "my string".


 ## Conditional (ternary) operator
The conditional operator is the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition. The syntax is:

condition ? val1 : val2

#### Copy to Clipboard
If condition is true, the operator has the value of val1. Otherwise it has the value of val2. You can use the conditional operator anywhere you would use a standard operator.

For example,

var status = (age >= 18) ? 'adult' : 'minor';


## Comma operator
The comma operator (,) evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a for loop, to allow multiple variables to be updated each time through the loop. It is regarded bad style to use it elsewhere, when it is not necessary. Often two separate statements can and should be used instead.

For example, if a is a 2-dimensional array with 10 elements on a side, the following code uses the comma operator to update two variables at once. The code prints the values of the diagonal elements in the array:

var x = [0,1,2,3,4,5,6,7,8,9]

var a = [x, x, x, x, x];

for (var i = 0, j = 9; i <= j; i++, j--)

                               ^
  console.log('a[' + i + '][' + j + ']= ' + a[i][j]);

  [Expressions and operators] (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

  # Functions
  Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

See also the exhaustive reference chapter about JavaScript functions to get to know the details.

## Defining functions
Function declarations
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.

For example, the following code defines a simple function named square:

function square(number) {
  return number * number;
}
## Function expressions

While the function declaration above is syntactically a statement, functions can also be created by a function expression.

Such a function can be anonymous; it does not have to have a name. For example, the function square could have been defined as

const square = function(number) 

{ return number * number }

var x = square(4)

[function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
