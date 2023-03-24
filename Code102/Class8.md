# Operators and Loops

*An **expression** is a unit of code that resolves to a value.  There are 2 types.  Those that have side effects, such as assigning values (example x=7), and those that purely evaluate (3+4).  The second type will be immediately discarded by a computer unless it gets placed inside of bigger construct like a variable declaration (`const z=3+4`).  All complex expressions are joined by operators. For example, the `=` or `+` signs in the examples above.*

Two such operators are:  Comparison Operators and Assignment Operators.

An **operand** is the piece of code that specifies what data is to be manipulated or operated on.  It also represents the data itself. 

A **comparison operator** compares the operands and returns a logical value based on whether the comparison is true.  The operands can be numerical, string, logical, or object values.  If the two operands are not the same type, JavaScript will attempt to convert them to an appropriate type for comparison.  This generally results in comparing the operands numerically.
For example, a `true` result would be given if the comparison operators are equal. ` 3 == var1 , "3" == var1 , 3 =='3' `

An **assignment operator** assign a value of what's on it's left to what's on its right.  So, for example, `x=f()` assigns the value of `f()` to `x`

There are several shorthand ways to write these in code.

**Loops** offer a quick and easy way to do something repeatedly.

There are many different kinds of loops, but they all essentially do the same thing.  They repeat an action some number of times.  That means that it's even possible for that number to be zero.  There are various situations that are more easily served by one type of loop over the others.

**A `for` loop** repeats until a specified condition returns as **false.**  It looks like the following:
`for (initialization; condition; afterthought)
statement`

**A `while` loop** keeps repeating itself as long as a specified condition returns as **true.** It looks like the following:
`while (condition)
statement`

If the `condition` becomes false, then `statement` within the `while` loop stops executing.  The test about whether or not the condition is true or false occurs before the `statement` in the `while` loop is executed.
