# Unit 2 - JavaScript Foundations

## Short Response Questions

**Directions:**
Write your responses directly below in this document without removing the questions. Your answers must be properly formatted. You should preview this markdown file before submitting. When you commit and push your changes, you will also be able to see your rendered markdown on GitHub.


### Types, Values, Operators
1. What are the seven primitive data types in JavaScript? What is the last non-primitive data type?

2. What does it mean to be truthy or falsy? What are all the primitive falsy values?

3. For each example, evaluate the expression and in one sentence, explain what coercions were applied and why:

* `8 * null`
* `"5" - 1`
* `"5" + 1`
* `true + false`
* `"i am" + undefined`


### Variables and Control Flow

4. **What does the code below log? Why?**
   ```javascript
   {
      let singer = 'Omar Apollo';
   }

   console.log(`My favorite singer is ${singer}`);

   ```
5. **What happens when we run the following code? Why?**
   ```javascript
   const favorite = 'Juan Pablo';
   console.log(`Our favorite Marcy Lab family member is ${favorite}!`);

   favorite = 'Maya';
   console.log(`Actually, ${favorite} is my favorite.`);
   ```
   
6. **The following code causes an infinite loop. Why?**
   ```javascript
   let counter = 0;

   while (counter <= 5) {
     counter = 1;
     console.log(`count: ${counter}`);
     counter += 1;
   }
   ```

### Functions

7. Define _hoisting_. What impact does hoisting have on the way that we structure our JavaScript programs?

8. Which type(s) of functions are hoisted? Which type(s) are not?
