### Chapter 10 (Error handling and Debugging):
##### JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.
##### The stack: the JavaScript interpreter processes one line of code at a time. When a statement needs data from another function. It stacks (or piles) the new function on the top of the current task.
##### understanding scope: in the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent’s variables object.
##### Understanding errors: if JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.
##### How to deal with errors: Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.
##### A debugging workflow: debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.
##### How to look at errors in chrome: the console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.
