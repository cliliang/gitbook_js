1、默认值
在ES6以前，是不能直接对方法传默认值的，只能用变通的方法，但ES6中，可以直接对方法函数传默认值
```js
function log(x, y = 'world'){
    console.log(x ,y);
}
```