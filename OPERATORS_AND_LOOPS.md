# Operators and Loops
## Chapter 4: Decisions & Loops (pages 150,151,156,157)
You can  evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: true or false. **Comparison operator** examples:
- equal to:`==`
- strict equal to: `===`
- is not equal to: `!=`
- strict not equal to: `!==`
- greater than: `>`
- greater than or equal to: `>=`
- less than: `<`
- less than or equal to: `<=`

Comparison operators usually return single values of true or false. **Logical operators** allow you to compare the results of more than one comparison operator. Logical operator examples:
- (and) tests more than one condition: `&&`
- (or) tests at least one conditon: `||`
- (not) inverts boolean value: `!`

Logical expressions are evaluated left to right. If the first condition can provide enough information to get the answer, then there is no need to evaluate the second condition. If the first condition is false the entire expression is false.
## Chapter 4 (pages 170-173, 176)
Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false.

There are 3 common types of loops:
- **For** loops: If you need to run code a specific number of times, use for loops. The condition is usually a counter which is used to tell how many times the loop should run.  They will always operate with a numeric counter.
- **While** loops: The condition can be something other than a counter and the code will continue to loop for as long as the condition is true.
- **Do While** loops: Very similar to the while loop, but has one key difference: it will always run the statements inside the curly braces at least once, even if the condition is false. 
 
 A for loop uses a counter as a condition. This instructs the code to run a specified number of times. The condition is made up of 3 statements:
 - **Initialization**: crieate a variable and set it to 0. The variable is commonly called **i**(sometimes called index) and it acts as the counter. Ex: `var i = 0;`. The variable is only created the first time the it is run.
 - **Condition**: The counter should run until it reaches a specified number. Ex. `i < 10;`. If the value was initially set at 0 it will run 10 times before stopping. 
 - **Update**: Every time the loop has run the statements in the curly braces, it adds one to the counter. Ex `i++`. One is added to the counter using the increment (++) operator. It is also possible for loops to count downwards using the decrement operator(--).
- [Back To Home](/README.md) 