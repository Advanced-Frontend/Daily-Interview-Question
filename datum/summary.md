

[TOC]



## 前端面试题汇总



### 第10期：异步笔试题

> 第 10 期：笔试题，请写出下面代码的运行结果

```js
async function async1() {
    console.log('async1 start');
    await async2();
    console.log('async1 end');
}
async function async2() {
    console.log('async2');
}
console.log('script start');
setTimeout(function() {
    console.log('setTimeout');
}, 0)
async1();
new Promise(function(resolve) {
    console.log('promise1');
    resolve();
}).then(function() {
    console.log('promise2');
});
console.log('script end');
```

解析：[关于第10题的一些见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/7)



###第 9 期：Async/Await 如何通过同步的方式实现异步

欢迎在 Issue 区留下你的答案。



### 第 8 期：setTimeout、Promise、Async/Await 的区别

欢迎在 Issue 区留下你的答案。



### 第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？

欢迎在 Issue 区留下你的答案。



### 第 6 期：请分别用深度优先思想和广度优先思想实现一个拷贝函数？

欢迎在 Issue 区留下你的答案。



### 第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？

解析：[关于第五题我的一些见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/9)



### 第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？

解析：[Set、Map、WeakSet 和 WeakMap](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/6)



### 第 3 期：什么是防抖和节流？有什么区别？如何实现？

解析：[节流和防抖的个人见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/5)



### 第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?

解析：[['1', '2', '3'].map(parseInt) 解析](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/4)



### 第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么

解析：[key的作用是为了在diff算法执行时更快的找到对应的节点，提高diff速度。](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)

