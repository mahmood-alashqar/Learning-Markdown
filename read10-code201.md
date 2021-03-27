# JavaScript can be hard to learn and everyone makes mistakes when writing it.
## learn DEBUGGER will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully. 

## When you are writing JavaScript, do not expect to write it perfectly the first time.
### Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it. too.


## When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it. In learn Debbuger you will learn about:
# THE CONSOLE & DEV TOOLS
Tools built into the browser
that help you hunt for errors.
 ERROR HANDLING & DEBUGGING
# COMMON PROBLEMS
Common sources of errors,
and how to solve them.
# HANDLING ERRORS
How code can deal with
potential errors gracefully.



 # ORDER OF EXECUTION 
 ### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run: 

 ```
function greetUser () {
 return 'He 11 o ' + getName ();

function getName() {
var name= 'Molly ' ;
return name;
}
 var greeting= greetUser();
 alert(greeting); 
 ```


# EXECUT.ION CONTEXTS
### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. 

# summery 
* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
* Debugging is the process of finding errors. It involves a process of deduction.
* The console helps narrow down the area in which the error is located, so you can try to find the exact error.
* JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 
