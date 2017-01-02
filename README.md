# JavaScript-Curry
Currying in JavaScript is a mechanism to partially evaluate the functions.
currying is a way of constructing functions that allows partial application of a function’s arguments. What this means is that you can pass all of the arguments a function is expecting and get the result, or pass a subset of those arguments and get a function back that’s waiting for the rest of the arguments. It really is that simple.

Lets say we have a function myFunc, it takes two arguments, and adds these. I will now show some JavaScript, but not give the code to myFunc (that'll come later). This is just so you can get an idea, what it does.

```
alert(myFunc(2,2));      // alerts 4
var adds4 = myFunc(4);   // adds4, is now a function,
                         // which adds 4, to it's argument.
alert(adds4(5));         // alerts 9.
```


It's the second line, which is the key. If you give a curried function, less arguments, then it expects, it will give you back, a function, which has been fed the arguments you gave it, and will accept the remaining ones. In the example above, we first gave it 4 (myFunc(4)), and it was waiting for another number, and we gave it 9.

This is all about JavaScript Curry.

Hoping this will help you :)
