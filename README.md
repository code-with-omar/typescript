### Introduction to Typescript

What is TypeScript?

- In a simple words, Additional Types (tuples, enum, interfaces, generics etc)  + JavaScript = TypeScript
- It is a superset of JS
- developed (2012) and maintained by Microsoft
- we can use typeof to check data type
- Js is dynamically types -> let x = 20;
- Typescript add static typing to js -> let x: number = 20;

Why TypeScript?

- JS Check types in run time while typescript add static typing to JS so we can handle errors before running the program. We can handle errors beofre running the program.
- increase readability and code quality
- We can use it React, Vue, popular JS libraray Angular use TypeScript.
- It can be used in both: client and server side.
- Intellisense IDE Support while coding: code completion, content assist and code hinting

TS Versions

- earlier versions
- TypeScript 1.0 October 2014
- TypeScript 2.0 September 2016
- TypeScript 3.0 July 2018
- TypeScript 4.0 - latest release August 2020
- TypeScript 5.4 - 2024
How does typescript work?

- index.ts -> tsc index.ts -> index.js
Environment setup

- Install node & typescript

- Install node & typescript

  ```js
      local installation: npm intsall typescript --save-dev
      Or
      global installation: npm install -g typescript
  ```
- Example 1
  ```typescript
    let userName: string
    userName = "Omar Faruk"
    console.log(userName)
  ```
- Example 2
  ``` typescript  
      function addNumbers(num1: number, num2: number) {
        return num1 + num2;
      }
      const result = addNumbers(10, 20)
  ```
### Data Types: Built-in / Basic Types
- Any(Super type)
  - Built in types: number, string, boolean,void,null,undefined etc
  - user-defined types:Arrays, Enums, Classes, interfaces etc.

1.Number: Represents both integer and floating-point numbers

  ```typescript
      let userId: number
      let age:number = 15
      userId = 190605
  ```