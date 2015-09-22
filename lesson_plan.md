## Javascript Functions

### Materials:
* Students' Laptops
* [In-class IDE](https://repl.it/languages/javascript)
* [Slides](http://slides.com/lizh/functions-in-js/live)
* [livecoding](livecoding.md)

### Requirements:
Students should be able to:  

* Execute statements
* Declare and Initialize variables
* Store the result of an expression in a variable
* Use `console.log()` to see outputs


### Objectives:
Students will write functions that:  

* Execute statements
* Have parameters that change the behavior of the function
* Have properly scoped variables
* Use the return keyword to return an expression
* Students will be able to call functions:
	* That have any number of parameters
	* For use in expressions
	* By composing other function calls as arguments- eg. sum(sum(5,10), 100)


### Assessments:
Accomplish the following and [send it to me](mailto:lizthedeveloper@gmail.com):  
(Use [this link](https://repl.it/languages/javascript) to write your code- then click 'save' and send me the link)

- [ ] Start with by writing a *function* that greets you
- [ ] Modify your function so that it can greet anyone, using a *parameter*
- [ ] Create a function that adds two numbers together, from *arguments*, and then prints the answer (call it **addTwo**)
- [ ] Modify your function so that it can be called as an argument to itself, using the *return* statement
- [ ] Create a new function that calculates the average of 6 numbers(called avg6), using the addTwo function (** use 5, 7, 9, 4, 5, 6 - you should get 6 as a result **) and returns them
- [ ] Calculate the average of 18 numbers (use 5, 7, 9, 4, 5, 6, 19, 22, 33, 26, 27, 30, 44, 44, 45, 44, 46, 41 which is 25.389) and print it using console.log(). Use only function *calls*, with no variable assignment outside of the function calls.


#### In-Class Questions:
* What happens if we choose to use global variables rather than local variables? What if some other code uses the same variable names you do? (eg. name, location)
* Why don't we just console.log everything, rather than using return?
* What would happen if we tried to call a function inside of another function?
* Even if we're defining a function that is only one line, how might this make our code easier to read?


