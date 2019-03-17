A module that does https://github.com/bermi/password-generator#example-with-custom-validation-rules, with `isStrongEnough` and `customPassword` exported

Password:

* Must contain at least two numbers
* Must contain at least three uppercase letters
* Must contain at least three lowercase letters
* Must contain at least two special characters
* Must NOT contain sequences of two or more repeated characters

```js
const generateStrongPassword = require('generate-strong-password');
console.log(generateStrongPassword()); // => 2hP5v?1KKNx7_a-W
```
