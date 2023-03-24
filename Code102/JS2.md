# JavaScript Continued

*Control flow is the order that a computer executes its instructions. The standard order is to flow from the first line to the last line, unless the computer encounters instructions telling it to change the order of how its following things.  This means that the computer needs to read not only from start to finish but also pay attention to the program structure and how it affects the order of execution.  Control structures can dictate complex flows of processing even if they are only a few lines of code long. Three types of control structures are conditionals, loops, and functions.*

A conditional structure is one where an instruction (or set of instructions) is executed if a specific condition is fulfilled .  Otherwise another instruction is executed. It takes the form of: `if ... else` Conditional structures allow different series of codes/functions to run depending on the input.

Loops are sequences of instructions that repeat until a certain condtion is met.  They are a way to execute a set of instructions for a variable number of times.

**Functions** are code snippets that can be executed when called on (invoked) by other code or, alternatively, by either itself or a variable that refers to the function.  Arguments pass to the function as input, and then the function can return a value.  In JavaScript a function is called an **object**.  Essentially, it is a block of code designed to perform a particular task.  Functions can be used the same way as you use variables, in all types of formulas, assignments and calculations.

Functions allow us to reuse code.  The code can be defined once and then used may times.  It allows us to use the same piece of code to be used with different argument to produce different results.

The code inside of a function can be executed when something **invokes** (**calls**) the function.  Examples include when an event occurs (such as a user clicking a button), or when a piece of internal JavaScript code invokes it.  Alternatively, it can be automatically self-invoked.

In JavaScript, a function is defined using the `function` keyword.  That is then followed by a name.  Function names have the same rules as variables.  They can contain letters, digits, underscores, and dollar signs. The name is then followed by parentheses (the **operator**).  The parentheses include parameter names inside, separated by commas.  Inside the function, these arguments (parameters) behave as local variables.  To finish the line of code, any instructions to be executed by the function is then placed inside of curly brackets at the end.  So the line of code looks like the following:
`function name( parameter1, parameter2, parameter3 ){ //code to be executed }`

The `()` operator invokes/calls the function.  Accessing a function without () will return the function object instead of the function result.

Function arguments are the values received by the function when it is invoked.  Functions often compute a return value that is "returned" back to "the caller."

The JavaScript function knows to stop executing when it reaches a `return` statement.
