---
title: "Recursion, Is it importatnt to learn?"
date: 2023-11-21
---
Recursion is a programming concept where a function calls itself in its own definition. In other words, a recursive function is a function that solves a problem by 
solving smaller instances of the same problem. The process continues until a base case is reached, at which point the function returns a result without making a 
further recursive call.
Example:
```Javascript
function factorial(n) {
  // Base case: factorial of 0 or 1 is 1
  if (n === 0 || n === 1) {
    return 1;
  }
  // Recursive case: n! = n * (n-1)!
  else {
    return n * factorial(n - 1);
  }
}

// Example usage:
console.log(factorial(5)); // Output: 120
```
