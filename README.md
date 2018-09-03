# Random Number Generator

You are provided this flip function:
```javascript
function flip() {
    returnMath.random() >=0.5;
}
```
You must implement a randomNumber(n) function that generates a random number greater than or equal to 0, and less than input n.

Constraints:
1. n must be greater than 0
1. n must be less than 1,000,000
1. Your only source of randomness must be the provided flip() function
1. You cannot use Math.random in your implementation
1. You can use Google to figure out how to do this

An example execution of your function:
```javascript
randomNumber(500) // returns 123
randomNumber(1) // returns 0
randomNumber(500) // returns 466
randomNumber(1000001) // throw error
```

Please fork and send a pull request with your solution.
