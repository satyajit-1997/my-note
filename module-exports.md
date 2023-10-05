# Module Exports

add.js

```javascript
const add = (a,b) => {
    return a + b;  
};
module.exports = add;
```

index.js

```javascript
const add = require ('./add');
console.log("hello world");
const sum = add(4,8);
const sum2 = add(3,5);
console.log(`sum is ${sum}`);
console.log(`sum is ${sum2}`);
```

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>





