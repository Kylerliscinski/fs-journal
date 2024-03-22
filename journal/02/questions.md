# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > Let, Const, and Var. Var was the original command. Let & Const were added more recently to help fix some of the issues with var. 

02. What is the definition of a function?

    > Functions are designed to do one particular task. They are used to return values.

03. What are the `SOLID` principles?

    > S - Single-responsiblity Principle - Responisble for creating a class that has 'one' job
    > O - Open-closed Principle - Functions that you can add onto but not change the function as a whole
    > L - Liskov Substitution Principle - The ability to use the space inside the parens. of a function
    > I - Interface Segregation Principle - You cannot use functions that clash inside other functions
    > D - Dependency Inversion Principle - Allows you to abstraact out of the functions

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit[2] 

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    >for (let i = 0; i < length; i++){
    > you[i] + them[i]
    >}

06. Give an example of a JavaScript `Conditional`:

    > if statements
    > if(i > 0){
    > console.log(bananas)
    > }

07. What is the main difference between `parameters` and `arguments`?

    > Paramaters are listed inside of functions. Arguments are values that are passed through functions

08. Instead of writing everything to the console, what is a better way to debug your code?

    > using the debugger tool. This will allow you to pause your code whenever the tool comes up and go through it step by step.

09. What is the difference between a `primitive` value and a `reference` value?

    > Primitive values are stored inside the value of a variable. Reference values hold specific information that relates to variables.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (let i = 0; i < length; i++){
    > console.log(i)
    > }
