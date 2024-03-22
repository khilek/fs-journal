# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > LET and CONST and VAR

02. What is the definition of a function?

    > A subprogram designed to perform a particular task.
    

03. What are the `SOLID` principles?

    > Single Responsibility 
      Open-closed 
      Liskov-substitution
      Interface segregation
      Dependency inversion


04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > delete fruit[2];

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

    > let friends = you.concat(them)

06. Give an example of a JavaScript `Conditional`:

function serveAlcohol() {
    let person = person
     if (person >= 21) {
    return true;
} else if (person < 21 ) {
    return false
}
}


07. What is the main difference between `parameters` and `arguments`?

    > Param's are used when defining a function or like a placeholder
    Argu's are the values the function receives from each param. 

08. Instead of writing everything to the console, what is a better way to debug your code?

    > Using DevTools and the sources tab can be handy

09. What is the difference between a `primitive` value and a `reference` value?

    > primitive values are info stored as the value of a variable
    reference value holds a reference to info related to that variable

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (let i = -100; i <= 100; i++){
        console.log(i);
    }

