# 🦜  Debugging and Error Handling 🦜

## 📝 Assigned Homework Questions:

❓ Name some key differences between a Syntax Error and a Logic Error.

**Syntax Errors** are errors in the symbols you used when trying to communicate to the computer.  They usually render the instructions impossible for the computer to read/understand, resulting in error messages.

**Logic Errors** are errors where the computer understood the sentence you said, but you told it to do the wrong thing.  They usually cause results that you weren't looking for.

❓ List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

One of the errors that I (and it sounds like a few of my classmates) encountered during the Lab 7 table creation was that we were telling the software to move the value of a variablb away to another variable (rendering the old one equal to zero, essentially) and then trying to multiply with the old one afterwards.  The software could still read the code with a zero value, but multiplying times zero equals zero, which is not a value ("Not A Number", as the software called it).  Changing the order the lines were ordered/read in (moving the multiplication line to before where the value of the variable had been taken away) solved the problem.

As a logic error, that was a LOT harder to figure out what was happening compared to the many, many syntax errors I have committed.  Because the console log pinpoints what line a syntax error occurred at, it's been fairly fast to see what was done wrong if the console log is looked at, that is.  Forgetting a single tiny symbol, or inserting an extra one, is an easy extremely common mistake to make.

❓ How will this topic continue to influence your long term goals?

Errors will continue to occur.  Hopefully, not the same ones, but rather new ones.  Mistakes are part of the learning process.  Mistakes are still a part of life even AFTER having learned how to do something as well, because that is the reality of being human.  "To err is human," as they say.

Becoming accustomed to using the console log to hunt down syntax errors has been great practice for when I will no longer be in school, no longer able to ask a TA for help.  Gaining practice with using the console log to be self-sufficient is a great habit for after graduation.  Also, the practice of reaching out for help from someone more skilled/knowledgeable is a good habit to be getting into as well.

<br>

❓ How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

A JavaScript debugger is a piece of software that pauses the execution of your instructions directly at the point where you made a mistake, so that you can look directly at where the problem is at.  An analogy would be that it's like having your own private detective for solving where the crime was committed.  It might not be able to tell you it was Mr. Green with the candlestick, but it can at least tell you it was in the study and show you who was nearby at the time it was committed and what they were holding!

❓ Define what a breakpoint is.

Places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

❓ What is the call stack?

It shows what code was executed upstream of the error line.

<br>

<br>

## 📚 Links to the Assigned Reading:

[What Went Wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

[The JavaScript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools#the_javascript_debugger)

[Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

[Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)
