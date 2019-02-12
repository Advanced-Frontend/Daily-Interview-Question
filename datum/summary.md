<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [前端面试题汇总](#%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%A2%98%E6%B1%87%E6%80%BB)
  - [第10期：异步笔试题](#%E7%AC%AC10%E6%9C%9F%E5%BC%82%E6%AD%A5%E7%AC%94%E8%AF%95%E9%A2%98)
  - [第 8 期：setTimeout、Promise、Async/Await 的区别](#%E7%AC%AC-8-%E6%9C%9Fsettimeoutpromiseasyncawait-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？](#%E7%AC%AC-7-%E6%9C%9Fes5es6-%E7%9A%84%E7%BB%A7%E6%89%BF%E9%99%A4%E4%BA%86%E5%86%99%E6%B3%95%E4%BB%A5%E5%A4%96%E8%BF%98%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
  - [第 6 期：请分别用深度优先思想和广度优先思想实现一个拷贝函数？](#%E7%AC%AC-6-%E6%9C%9F%E8%AF%B7%E5%88%86%E5%88%AB%E7%94%A8%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E6%8B%B7%E8%B4%9D%E5%87%BD%E6%95%B0)
  - [第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？](#%E7%AC%AC-5-%E6%9C%9F%E4%BB%8B%E7%BB%8D%E4%B8%8B%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？](#%E7%AC%AC-4-%E6%9C%9F%E4%BB%8B%E7%BB%8D%E4%B8%8B-setmapweakset-%E5%92%8C-weakmap-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 3 期：什么是防抖和节流？有什么区别？如何实现？](#%E7%AC%AC-3-%E6%9C%9F%E4%BB%80%E4%B9%88%E6%98%AF%E9%98%B2%E6%8A%96%E5%92%8C%E8%8A%82%E6%B5%81%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?](#%E7%AC%AC-2-%E6%9C%9F1-2-3mapparseint-what--why-)
  - [第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么](#%E7%AC%AC-1-%E6%9C%9F%E5%86%99-react--vue-%E9%A1%B9%E7%9B%AE%E6%97%B6%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%9C%A8%E7%BB%84%E4%BB%B6%E4%B8%AD%E5%86%99-key%E5%85%B6%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->





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

解析：[第六题 实现深度拷贝](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/10)



### 第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？

解析：[关于第五题我的一些见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/9)



### 第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？

解析：[第四题：Set、Map、WeakSet 和 WeakMap](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/6)



### 第 3 期：什么是防抖和节流？有什么区别？如何实现？

解析：[第三题：节流和防抖的个人见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/5)



### 第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?

解析：[第二题：['1', '2', '3'].map(parseInt) 解析](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/4)



### 第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么

解析：[第一题：key的作用是为了在diff算法执行时更快的找到对应的节点，提高diff速度。](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)

