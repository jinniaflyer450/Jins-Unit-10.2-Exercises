# Jins-Unit-10.2-Exercises
The exercises for Unit 10.2 of a course I'm taking. The answers to the written quiz are in the readme.

Quiz:

1. There are several differences between var and let; the most important are that var can be redeclared, while let can’t, and var is scoped to functions only, 
while let is scoped to any code block it is declared in (a code block generally meaning code inside a set of curly braces that isn’t an object literal). 
Also, variable declarations with var are hoisted, while variable declarations with let are not.

2. The differences between var and const are almost identical to the differences between var and let—var can be redeclared, unlike const, 
and var is scoped to functions while const is scoped to the code block it is declared in. The added difference between var and const that does not exist between var and let 
is that const also cannot be reassigned, while var can.

3. The variable declarations let and const are almost identical; both cannot be redeclared and both are block-scoped. The main difference between the two is that 
const cannot be reassigned, while let can.

4. “Hoisting” is the process by which variable declarations with var are read during compilation of code before their corresponding initializations—
that is, when the code runs, variables declared with var exist but are undefined before the portion of the code where they are initialized/assigned a value is run, 
which means they can be accessed as undefined anywhere in the code before they are properly initialized. Variables declared with let and const are not hoisted, and in fact 
const variables cannot be declared without being initialized at all. 
