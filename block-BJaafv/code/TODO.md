1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
sum(2,3)

// second
function sum(a, b) {
  console.log(a + b);
}
sum (6,3)
```

In the first function we are calling returning the parameters 
In the second function we directly priting the value of sum by giving orguments 

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

The first value is 5
The second value is 9 and undefined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

  function sayHello(){
    return  `Hellow Arya`
  }
  sayHello()

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage(); // output is `Hello John` . Here calling to return the function showMessage().
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1  'John'

showMessage(); // Output 2   'hello John'

alert(userName); // Output 3   in alert box output is 'john'
```

8. What is a Anonymous Function give example of three functions.

1)  function addNumbers = function(numA , numB){
      return numA + numB
    }
    let message = addNumbers(3,8)
    console.log(message) or alert(message)

2)  function addNumbers = function(numA , numB){
      return numA * numB
    }
    let message = addNumbers(3,3)
    console.log(message) or alert(message)

3)  function addNumbers = function(numA , numB){
      return numA + numB
    }
    let message = addNumbers(10/2)
    console.log(message) or alert(message)

9. Can function declaration be a Anonymous Function? Explain

A) If you want to create a function and execute it immediately after declaration, you can use the anonymous function

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
