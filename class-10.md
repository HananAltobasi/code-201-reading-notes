# ERROR HANDLING & DEBUGGING
## ORDER OF EXECUTION
* To find the source of an error, it helps to know how scripts are processed. 
* This script above creates a greeting message, then writes it to an alert box (see right-hand page).
* In order to create that greeting, two functions are used: 
  * greetUser ().
  * getName (). 

## EXECUT.ION CONTEXTS
* EXECUTION CONTEXT  
Every statement in a script lives in one of three 
execution contexts: 
  * GLOBAL CONTEXT.
  * Function CONTEXT.
  * Eval CONTEXT.

* VARIABLE SCOPE 
The first two execution contexts correspond with the notion of scope:
  * Q GLOBAL SCOPE.
  * FUNCTION-LEVEL SCOPE.

## the stack
![image](https://user-images.githubusercontent.com/79087406/110704402-94515800-81fd-11eb-8ac4-2fb1c79e283e.png)
![image](https://user-images.githubusercontent.com/79087406/110704511-b8149e00-81fd-11eb-98cf-35ca109a231c.png)

## EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:

1) PREPARE
  • The new scope is created. 
  • Variables, functions, and arguments are created.
  • The value of the this keyword is determined.
  
2) EXECUTE 
  • Now it can assign values to variables. 
  • Reference functions and run their code. 
  • Execute statements.
  
## UNDERSTANDING SCOPE
* each execution context has its own va ri ables object. 
* It holds the variables, functions, and parameters available within it. 
* Each execution context can also access its parent's v a ri ables object. 

## ERROR OBJECTS
![image](https://user-images.githubusercontent.com/79087406/110705076-88b26100-81fe-11eb-827b-aa1d1b56d731.png)

## HOW TO DEAL WITH ERRORS
there are two things you can do with the errors:

1) DEBUG THE SCRIPT TO FIX ERRORS.
2)  HANDLE ERRORS GRACEFULLY.

## A DEBUGGING WORKFLOW
![image](https://user-images.githubusercontent.com/79087406/110705345-f2cb0600-81fe-11eb-82c9-9fdcb23d65b0.png)

## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE

* The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 
* These two pages show instructions for opening the console in all of the main browsers.
* Browser manufacturers occasionally change how to access these tools. 
* CHROM E/ OPERA 
  * On a PC, press the F12 key or: 
    1. Go to the options menu (or three line menu icon).
    2. Select Toots or More tools. 
    3. Select JavaScript Console or Developer Tools.
  * On a Mac press Alt + Cmd + J. Or:
  
    4. Go to the View menu. 
    5. Select Developer. 
    6. Open the JavaScript Console or Developer Tools option and select Console. 

* INTERNET EXPLORER 
  * Press the F12 key or: 
  
    1. Go to the settings menu in the top-right. 
    2. Select developer tools. 
## BREAKPOINTS
![image](https://user-images.githubusercontent.com/79087406/110706038-ea26ff80-81ff-11eb-8ca2-a32f1cd0bdcf.png)

## CONDITIONAL BREAKPOINTS
![image](https://user-images.githubusercontent.com/79087406/110706147-12aef980-8200-11eb-949c-8cf1af932e9c.png)

## THROWING ERRORS 
* If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them. 
* If you are working with data from a third party, you may come across problems such as: 
  • JSON that contains a formatting error.
  • Numeric data that occasionally has a non-numeric value. 
  • An error from a remote server. 
  • A set of information with one missing value.
  
## DEBUGGING TIPS  
![image](https://user-images.githubusercontent.com/79087406/110706439-818c5280-8200-11eb-8031-ab8f571c0ea0.png)

## COMMON ERRORS 
* GO BACK TO BASICS:

  JavaScript is case sensitive so check your capitalization. 
* MISSED/ EXTRA CHARACTERS: 

  Every statement should end in a semicolon. 
* DATA TYPE ISSUES: 

  Using= rather than == will assign a value to a variable, not check that the values match. 




