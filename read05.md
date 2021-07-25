# Expressions and operators
### This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more

# Operators
### JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence

Return value and chaining
Like most expressions, assignments like x = y have a return value. It can be retrieved by e.g. assigning the expression or logging it:

const z = (x = y); // Or equivalently: const z = x = y;

console.log(z); // Log the return value of the assignment x = y.
console.log(x = y); // Or log the return value directly.
The return value matches the expression to the right of the = sign in the “Meaning” column of the table above. That means that (x = y) returns y, (x += y) returns the resulting sum x + y, (x **= y) returns the resulting power x ** y, and so on.

In the case of logical assignments, (x &&= y), (x ||= y), and (x ??= y), the return value is that of the logical operation without the assignment, so x && y, x || y, and x ?? y, respectively.

Note that the return values are always based on the operands’ values before the operation.

When chaining these expressions, each assignment is evaluated right-to-left. Consider these examples:

w = z = x = y is equivalent to w = (z = (x = y)) or x = y; z = y; w = y
z += x *= y is equivalent to z += (x *= y) or tmp = x * y; x *= y; z += tmp (except without the tmp).

[Expressions and operators ]
(https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

# Loops and iteration
### Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

for (let step = 0; step < 5; step++) {

  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

#### There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

#### The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others

# while statement
while (condition)

  statement

  #### If the *condition *becomes false, statement within the loop stops executing and control passes to the statement following the loop.

#### The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following whil
# break statement
Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.

When you use break without a label, it terminates the innermost enclosing while, do-while, for, or switch immediately and transfers control to the following statement.
When you use break with a label, it terminates the specified labeled statement.
The syntax of the break statement looks like this:

break;

break [label];

Copy to Clipboard
The first form of the syntax terminates the innermost enclosing loop or switch.
The second form of the syntax terminates the specified enclosing labeled statement.

[loops]
(https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)