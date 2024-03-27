# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    Var, let and const

02. What is the definition of a function?

    A subprogram designed to perform a particular task

03. What are the `SOLID` principles?

   S - Single Responsibility a class should be having one and only one responsibility
O - Open / Closed classes should be open for extension but closed for modification
L - Liskov Substitution parent classes should be easily substituted with their child classes without blowing up the application
I - Interface Segregation many client specific interfaces are better than one general interface
D - Dependency Inversion classes should depend on abstraction but not on concretion

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    let pineapple=fruit.pop();
    

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

    let friends=you.concat(them);
    console.log(friend)

06. Give an example of a JavaScript `Conditional`:

    > | ANSWER HERE |

07. What is the main difference between `parameters` and `arguments`?

    > | ANSWER HERE |

08. Instead of writing everything to the console, what is a better way to debug your code?

   you can use the Sources tab or chrome developer tools

09. What is the difference between a `primitive` value and a `reference` value?

    > | ANSWER HERE |

10. Demonstrate a loop that prints the numbers between -100 and 100?

   
