![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)

## Error Handling & Debugging

*To find the source of an error, it helps to know the order of execution.*

### Execution Contexts

1. **Global Context** - There is only one global context in any page. It sits outside of a function and can be used anywhere. It is a global variable.

1. **Function Context** - Each function has its own context within itself. When a variable is declared within a function, it can only be used within that function.

**Hoisting** - The preparation and execution of functions within a script. 

1. *Prepare* - All the variable, functions, arguments and context scope are created.

1. *Execute* - Variables are assigned values, functions will execute and statements will run. 

## Error Objects

*Error objects help you find mistakes and errors. There are built in tools within browser consoles to help find and read errors.*

### Properties of an Error Object

1. **name** - Type of error.
1. **message** - Description.
1. **fileNumber** - Name of the JavaScript file.
1. **lineNumber** - Line number of the error.

*There are seven types of built-in error objects:*

1. **Error** - Generic error - all other errors are based on this specific error.
1. **SyntaxError** - Syntax has not been followed. Incorrect use of the rules of the language. Often a typo.
1. **RefereneError** - Unable to locate a variable. Variable may not be declared or within correct scope.
1. **TypeError** - An unexpected data type. Trying to use an object or method that does not exist.  
1. **RangeError** - Numbers are not in acceptable range.
1. **URIError** - encodeURI(), decodeURI() and similar methods used incorrectly.
1. **EvalError** - eval() function used incorrectly.

## How to deal with Errors

1. **Debug the Script** - Track down the source of the error and fix it.
1. **Handle Errors Gracefully** - Use *try*, *catch*, *throw* and *finally* statements.

**Narrow down the location of the issue and search for clues.**

- Where is the problem?
- What exactly is the problem?