# Error Handling and Debugging
Notes from Jon Duckett’s JS book, Chapter 10

## If you understand execution contexts  and stacks, you’re more likely to find bugs.
## The console helps narrow down the area in which the error is located so you can try to find the extract error
## There are 7 different types of errors in JavaScript. Each can create its own error object and tell you which line number its on and give a description of the error
## Using the try, catch, throw, and finally statements, you can handle errors gracefully and give users helpful feedback
# Functions in JavaScript are said to have lexical scope. They are linked to the object they were defined within. So, for each execution context, the scope is the current execution context variables object, plus the variables object for each parent execution context
## If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception handling code
## Error objects can help you find where your mistakes are and browsers have tools to help you read them
## There are two ways to handle errors
  -Debug the script to fix the error
  -Handle the errors with grace
## Debugging is pretty self explanatory, handling the errors with grace simply means that if for what ever reason the code doesn’t work and its not possible to debug, (maybe the code is requesting something from a third party site and their servers are down) you can use your code to create an error message for the user