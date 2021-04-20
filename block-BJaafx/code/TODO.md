1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
function input(total){
  // let NoInputs = 10
  let sum = 0;
  for(let i=0; i<=total; i++){
    let value = +prompt("Enter input");
    sum += value;
  } 
  let avg = sum / total
  return avg
}
input(10)
```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

Ans) println is not defined

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
Ans)
```js
function getEvenSum(max){
  let sum = 0;
  for(let i=0; i<= max; i++){
    if(i % 2 == 0){
      sum += i
    }
  }
  return sum;
}
getEventSum(50)
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
Ans)
```js
function getOddSum(max){
  let sum = 0;
  for(let i=0; i<= max; i++){
    if(i % 2 != 0){
      sum += i
    }
  }
  return sum;
}
getOddSum(50)
```
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
Ans) 
```js
function getProductOfDigits(num){
  let product = 1;
  while(num > 0){
    product = product * (num % 10);
    num = Math.floor(num / 10);
  }
  return product;
   if(num < 0){
    return "not a valid input" ;
  }
}
getProductOfDigits(373)
```

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // Bigger than 5
check(1); // Smaller than 5
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // Yor are arya
getOutput('John'); // you are John
getOutput(); // Who are you
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // it will print You are arya and it will also return who are you
getOutput('John'); // it will print You are John and it will also return who are you
getOutput(); // it will return who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Ans) Yes we can give multiple return statements
```js
  function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}
getOutput('Arya'); //  you are arya
getOutput('John'); // you are John
```

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
