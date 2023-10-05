# Module Scope

Each loaded module in Node.js is Wrapped with an IIFE that provides private scoping of code

IIFE allows you to repeat variable of function names without any conflicts

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### Immediately Invoked Function Expression (IIFE) in Node.JS

```javascript
(function(){
    //Module code actually lives in here
})();
```

Before a module's code is executed, Node.JS will wrap it with a function wrapper that provides module scope

This saves us from having to worry about conflicting variables or functions

There is proper encapsulation and reusability is unaffected

Example

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>
