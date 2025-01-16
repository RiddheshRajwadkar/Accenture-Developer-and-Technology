### Task 6: Code Debugging
The concept of code debugging goes back to the earliest days of computer science when computers were room sized machine and used vacuum tubes and electromechanical relays to switch between "1" and "0" instead of electronic.<br><br>
**There are three categories of common bugs or errors in computer code:**

- Logic errors. Errors in the logic of the algorithm itself. Not strictly speaking an error in the code itself so much as an error in the thinking behind the code. Common logic errors include missing or unusual conditions under which a THEN or an ELSE 
- should occur but the code does not include them because the algorithm was incompletely specified.
- Syntax errors. Errors in use of programming language vocabulary and grammar when writing code. These errors prevent the computer from correctly parsing and understanding the code as written, so the code will not run. Common syntax errors include 
- misspelling function or variable names and leaving out required parentheses or semicolons.
- Run-time errors. Errors that occur during the execution of the code. Either the code will run but the output is wrong, or the code stops running because a necessary condition doesn’t currently exist, like a file is missing or a database is inaccessible.

### How to debug code:
- Input simplification – input just one variable or bit of data at a time to see which input causes a problem
- Stepping – watch the code execute one line at a time to see which line causes a problem and what the computer was trying to do at the moment the problem occurred
- Backtracking – essentially stepping but stepping backwards from the point of error
- Output statement tracing – add code at various points in your program to print out status or values of variables, and use the printed values to trace where the program went wrong and why
- Divide and conquer – run only one section of code at a time (usually by “commenting out” the other sections so the computer doesn’t see them) to isolate the error systematically
