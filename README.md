# Javascript variables, constants and console.log

## What is this demo?

Variables random ideas demo.

## What are the objectives?

- Understanding what's a variables, how does the computer stores information, why is it uself
- Understanding naming abstraction
- Understanding types (strings, numbers)
- Understanding naming convention and rules 
- Understanding the assignment symbol and how it is different from the equal sign, and how mathmaticians will go crazy if they see programmers using the `=` sign as an assignment sign
- Understanding the right side of the assignment operator and how is it calculated before we assign the value to the variables
- Understanding the constants 
- Understanding how you shouldn't use a variable before giving it a value


## Keywords
- let
- const
- var (optional in case any one asked)


## Steps
- Open a new folder on Desktop call it variables-intro
- Install shell from code `cmd + p` `type shell`
- `code .`
- make a new file `index.js`
- write down the demo 
- open terminal in VSCode 
- `pwd` make sure you are in the right working directory
- `node index.js`


```js
  // 1. variables simple 
  let name = "Ahmad"
  let age = 20
  console.log(name)
  console.log(age)
  
  // show them we can change variables
  name = "Ali"
  age = 22
  console.log(name)
  console.log(age)
  
  
  // show them we can't change constants after we assign them
  const pi = 3.14 
  console.log("Pi is", pi)
  pi = 55
  console.log("Pi now is", pi)
  
  
  // 2. String concatenation and naming convention
  let firstName = "Harry"
  let lastName = "Potter"
  let fullName = `${firstName} ${lastName}`
  let birthYear = 1980
  
  // 3. Operations inside string 
  console.log(`I am ${fullName} and I am ${2021 - age} years old`)
```


