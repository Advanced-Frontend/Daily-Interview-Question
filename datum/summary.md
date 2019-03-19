<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [前端面试题及答案汇总](#%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%8A%E7%AD%94%E6%A1%88%E6%B1%87%E6%80%BB)
  - [第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么](#%E7%AC%AC-1-%E6%9C%9F%E5%86%99-react--vue-%E9%A1%B9%E7%9B%AE%E6%97%B6%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%9C%A8%E7%BB%84%E4%BB%B6%E4%B8%AD%E5%86%99-key%E5%85%B6%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)
  - [第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?](#%E7%AC%AC-2-%E6%9C%9F1-2-3mapparseint-what--why-)
  - [第 3 期：什么是防抖和节流？有什么区别？如何实现？](#%E7%AC%AC-3-%E6%9C%9F%E4%BB%80%E4%B9%88%E6%98%AF%E9%98%B2%E6%8A%96%E5%92%8C%E8%8A%82%E6%B5%81%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？](#%E7%AC%AC-4-%E6%9C%9F%E4%BB%8B%E7%BB%8D%E4%B8%8B-setmapweakset-%E5%92%8C-weakmap-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？](#%E7%AC%AC-5-%E6%9C%9F%E4%BB%8B%E7%BB%8D%E4%B8%8B%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 6 期：请分别用深度优先思想和广度优先思想实现一个拷贝函数？](#%E7%AC%AC-6-%E6%9C%9F%E8%AF%B7%E5%88%86%E5%88%AB%E7%94%A8%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E6%8B%B7%E8%B4%9D%E5%87%BD%E6%95%B0)
  - [第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？](#%E7%AC%AC-7-%E6%9C%9Fes5es6-%E7%9A%84%E7%BB%A7%E6%89%BF%E9%99%A4%E4%BA%86%E5%86%99%E6%B3%95%E4%BB%A5%E5%A4%96%E8%BF%98%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
  - [第 8 期：setTimeout、Promise、Async/Await 的区别](#%E7%AC%AC-8-%E6%9C%9Fsettimeoutpromiseasyncawait-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 9 期：Async/Await 如何通过同步的方式实现异步](#%E7%AC%AC-9-%E6%9C%9Fasyncawait-%E5%A6%82%E4%BD%95%E9%80%9A%E8%BF%87%E5%90%8C%E6%AD%A5%E7%9A%84%E6%96%B9%E5%BC%8F%E5%AE%9E%E7%8E%B0%E5%BC%82%E6%AD%A5)
  - [第 10 期：异步笔试题](#%E7%AC%AC-10-%E6%9C%9F%E5%BC%82%E6%AD%A5%E7%AC%94%E8%AF%95%E9%A2%98)
  - [第 11 题：算法手写题](#%E7%AC%AC-11-%E9%A2%98%E7%AE%97%E6%B3%95%E6%89%8B%E5%86%99%E9%A2%98)
  - [第 12 题：JS 异步解决方案的发展历程以及优缺点。](#%E7%AC%AC-12-%E9%A2%98js-%E5%BC%82%E6%AD%A5%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88%E7%9A%84%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B%E4%BB%A5%E5%8F%8A%E4%BC%98%E7%BC%BA%E7%82%B9)
  - [第 13 题：Promise 构造函数是同步执行还是异步执行，那么 then 方法呢？](#%E7%AC%AC-13-%E9%A2%98promise-%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0%E6%98%AF%E5%90%8C%E6%AD%A5%E6%89%A7%E8%A1%8C%E8%BF%98%E6%98%AF%E5%BC%82%E6%AD%A5%E6%89%A7%E8%A1%8C%E9%82%A3%E4%B9%88-then-%E6%96%B9%E6%B3%95%E5%91%A2)
  - [第 14 题：情人节福利题，如何实现一个 new](#%E7%AC%AC-14-%E9%A2%98%E6%83%85%E4%BA%BA%E8%8A%82%E7%A6%8F%E5%88%A9%E9%A2%98%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-new)
  - [第 15 题：简单讲解一下http2的多路复用](#%E7%AC%AC-15-%E9%A2%98%E7%AE%80%E5%8D%95%E8%AE%B2%E8%A7%A3%E4%B8%80%E4%B8%8Bhttp2%E7%9A%84%E5%A4%9A%E8%B7%AF%E5%A4%8D%E7%94%A8)
  - [第 16 题：谈谈你对TCP三次握手和四次挥手的理解](#%E7%AC%AC-16-%E9%A2%98%E8%B0%88%E8%B0%88%E4%BD%A0%E5%AF%B9tcp%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%92%8C%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B%E7%9A%84%E7%90%86%E8%A7%A3)
  - [第 17 题：A、B 机器正常连接后，B 机器突然重启，问 A 此时处于 TCP 什么状态](#%E7%AC%AC-17-%E9%A2%98ab-%E6%9C%BA%E5%99%A8%E6%AD%A3%E5%B8%B8%E8%BF%9E%E6%8E%A5%E5%90%8Eb-%E6%9C%BA%E5%99%A8%E7%AA%81%E7%84%B6%E9%87%8D%E5%90%AF%E9%97%AE-a-%E6%AD%A4%E6%97%B6%E5%A4%84%E4%BA%8E-tcp-%E4%BB%80%E4%B9%88%E7%8A%B6%E6%80%81)
  - [第 18 题：React 中 setState 什么时候是同步的，什么时候是异步的？](#%E7%AC%AC-18-%E9%A2%98react-%E4%B8%AD-setstate-%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E6%98%AF%E5%90%8C%E6%AD%A5%E7%9A%84%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E6%98%AF%E5%BC%82%E6%AD%A5%E7%9A%84)
  - [第 19 题：React setState 笔试题，下面的代码输出什么？](#%E7%AC%AC-19-%E9%A2%98react-setstate-%E7%AC%94%E8%AF%95%E9%A2%98%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
  - [第 20 题：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？](#%E7%AC%AC-20-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B-npm-%E6%A8%A1%E5%9D%97%E5%AE%89%E8%A3%85%E6%9C%BA%E5%88%B6%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BE%93%E5%85%A5-npm-install-%E5%B0%B1%E5%8F%AF%E4%BB%A5%E8%87%AA%E5%8A%A8%E5%AE%89%E8%A3%85%E5%AF%B9%E5%BA%94%E7%9A%84%E6%A8%A1%E5%9D%97)
  - [第 21 题：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣](#%E7%AC%AC-21-%E9%A2%98%E6%9C%89%E4%BB%A5%E4%B8%8B-3-%E4%B8%AA%E5%88%A4%E6%96%AD%E6%95%B0%E7%BB%84%E7%9A%84%E6%96%B9%E6%B3%95%E8%AF%B7%E5%88%86%E5%88%AB%E4%BB%8B%E7%BB%8D%E5%AE%83%E4%BB%AC%E4%B9%8B%E9%97%B4%E7%9A%84%E5%8C%BA%E5%88%AB%E5%92%8C%E4%BC%98%E5%8A%A3)
  - [第 22 题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化](#%E7%AC%AC-22-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B%E9%87%8D%E7%BB%98%E5%92%8C%E5%9B%9E%E6%B5%81repaint--reflow%E4%BB%A5%E5%8F%8A%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8C%E4%BC%98%E5%8C%96)
  - [第 23 题：介绍下观察者模式和订阅-发布模式的区别，各自适用于什么场景](#%E7%AC%AC-23-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F%E5%92%8C%E8%AE%A2%E9%98%85-%E5%8F%91%E5%B8%83%E6%A8%A1%E5%BC%8F%E7%9A%84%E5%8C%BA%E5%88%AB%E5%90%84%E8%87%AA%E9%80%82%E7%94%A8%E4%BA%8E%E4%BB%80%E4%B9%88%E5%9C%BA%E6%99%AF)
  - [第 24 题：聊聊 Redux 和 Vuex 的设计思想](#%E7%AC%AC-24-%E9%A2%98%E8%81%8A%E8%81%8A-redux-%E5%92%8C-vuex-%E7%9A%84%E8%AE%BE%E8%AE%A1%E6%80%9D%E6%83%B3)
  - [第 25 题：说说浏览器和 Node 事件循环的区别](#%E7%AC%AC-25-%E9%A2%98%E8%AF%B4%E8%AF%B4%E6%B5%8F%E8%A7%88%E5%99%A8%E5%92%8C-node-%E4%BA%8B%E4%BB%B6%E5%BE%AA%E7%8E%AF%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 26 题：介绍模块化发展历程](#%E7%AC%AC-26-%E9%A2%98%E4%BB%8B%E7%BB%8D%E6%A8%A1%E5%9D%97%E5%8C%96%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B)
  - [第 27 题：全局作用域中，用 const 和 let 声明的变量不在 window 上，那到底在哪里？如何去获取？。](#%E7%AC%AC-27-%E9%A2%98%E5%85%A8%E5%B1%80%E4%BD%9C%E7%94%A8%E5%9F%9F%E4%B8%AD%E7%94%A8-const-%E5%92%8C-let-%E5%A3%B0%E6%98%8E%E7%9A%84%E5%8F%98%E9%87%8F%E4%B8%8D%E5%9C%A8-window-%E4%B8%8A%E9%82%A3%E5%88%B0%E5%BA%95%E5%9C%A8%E5%93%AA%E9%87%8C%E5%A6%82%E4%BD%95%E5%8E%BB%E8%8E%B7%E5%8F%96)
  - [第 28 题：cookie 和 token 都存放在 header 中，为什么不会劫持 token？](#%E7%AC%AC-28-%E9%A2%98cookie-%E5%92%8C-token-%E9%83%BD%E5%AD%98%E6%94%BE%E5%9C%A8-header-%E4%B8%AD%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E4%BC%9A%E5%8A%AB%E6%8C%81-token)
  - [第 29 题：聊聊 Vue 的双向数据绑定，Model 如何改变 View，View 又是如何改变 Model 的](#%E7%AC%AC-29-%E9%A2%98%E8%81%8A%E8%81%8A-vue-%E7%9A%84%E5%8F%8C%E5%90%91%E6%95%B0%E6%8D%AE%E7%BB%91%E5%AE%9Amodel-%E5%A6%82%E4%BD%95%E6%94%B9%E5%8F%98-viewview-%E5%8F%88%E6%98%AF%E5%A6%82%E4%BD%95%E6%94%B9%E5%8F%98-model-%E7%9A%84)
  - [第 30 题：两个数组合并成一个数组](#%E7%AC%AC-30-%E9%A2%98%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E5%90%88%E5%B9%B6%E6%88%90%E4%B8%80%E4%B8%AA%E6%95%B0%E7%BB%84)
  - [第 31 题：改造下面的代码，使之输出0 - 9，写出你能想到的所有解法。](#%E7%AC%AC-31-%E9%A2%98%E6%94%B9%E9%80%A0%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E4%BD%BF%E4%B9%8B%E8%BE%93%E5%87%BA0---9%E5%86%99%E5%87%BA%E4%BD%A0%E8%83%BD%E6%83%B3%E5%88%B0%E7%9A%84%E6%89%80%E6%9C%89%E8%A7%A3%E6%B3%95)
  - [第 32 题：Virtual DOM 真的比操作原生 DOM 快吗？谈谈你的想法。](#%E7%AC%AC-32-%E9%A2%98virtual-dom-%E7%9C%9F%E7%9A%84%E6%AF%94%E6%93%8D%E4%BD%9C%E5%8E%9F%E7%94%9F-dom-%E5%BF%AB%E5%90%97%E8%B0%88%E8%B0%88%E4%BD%A0%E7%9A%84%E6%83%B3%E6%B3%95)
  - [第 33 题：下面的代码打印什么内容，为什么？](#%E7%AC%AC-33-%E9%A2%98%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E6%89%93%E5%8D%B0%E4%BB%80%E4%B9%88%E5%86%85%E5%AE%B9%E4%B8%BA%E4%BB%80%E4%B9%88)
  - [第 34 题：简单改造下面的代码，使之分别打印 10 和 20。](#%E7%AC%AC-34-%E9%A2%98%E7%AE%80%E5%8D%95%E6%94%B9%E9%80%A0%E4%B8%8B%E9%9D%A2%E7%9A%84%E4%BB%A3%E7%A0%81%E4%BD%BF%E4%B9%8B%E5%88%86%E5%88%AB%E6%89%93%E5%8D%B0-10-%E5%92%8C-20)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->





## 前端面试题及答案汇总



### 第 1 期：写 React / Vue 项目时为什么要在组件中写 key，其作用是什么

解析：[第一题：key的作用是为了在diff算法执行时更快的找到对应的节点，提高diff速度。](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)



### 第 2 期：`['1', '2', '3'].map(parseInt)` what & why ?

解析：[第二题：['1', '2', '3'].map(parseInt) 解析](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/4)



### 第 3 期：什么是防抖和节流？有什么区别？如何实现？

解析：[第三题：节流和防抖的个人见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/5)



### 第 4 期：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？

解析：[第四题：Set、Map、WeakSet 和 WeakMap](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/6)



### 第 5 期：介绍下深度优先遍历和广度优先遍历，如何实现？

解析：[关于第五题我的一些见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/9)



### 第 6 期：请分别用深度优先思想和广度优先思想实现一个拷贝函数？

解析：[第六题 实现深度拷贝](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/10)



### 第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？

解析：[第 7 期：ES5/ES6 的继承除了写法以外还有什么区别？解答与一个疑惑](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/20)



### 第 8 期：setTimeout、Promise、Async/Await 的区别

解析：[第八题：setTimeout、Promise、Async/Await 的区别](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/33)





### 第 9 期：Async/Await 如何通过同步的方式实现异步

欢迎在 Issue 区留下你的答案。





### 第 10 期：异步笔试题

> 请写出下面代码的运行结果

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





### 第 11 题：算法手写题

> 已知如下数组：
>
> var arr = [ [1, 2, 2], [3, 4, 5, 5], [6, 7, 8, 9, [11, 12, [12, 13, [14] ] ] ], 10];
>
> 编写一个程序将数组扁平化去并除其中重复部分数据，最终得到一个升序且不重复的数组

解析：[第11题：将数组扁平化并去除其中重复数据，最终得到一个升序且不重复的数组](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/8)





### 第 12 题：JS 异步解决方案的发展历程以及优缺点。

解析：[第十二题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/11)





### 第 13 题：Promise 构造函数是同步执行还是异步执行，那么 then 方法呢？

解析：[关于第13题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/19)



### 第 14 题：情人节福利题，如何实现一个 new

解析：[14题 情人节快乐！](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/12)



### 第 15 题：简单讲解一下http2的多路复用

解析：[第15题：简单讲解一下http2的多路复用](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/14)



### 第 16 题：谈谈你对TCP三次握手和四次挥手的理解

解析：[关于第16题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/15)



### 第 17 题：A、B 机器正常连接后，B 机器突然重启，问 A 此时处于 TCP 什么状态

> 如果A 与 B 建立了正常连接后，从未相互发过数据，这个时候 B 突然机器重启，问 A 此时处于 TCP 什么状态？如何消除服务器程序中的这个状态？（超纲题，了解即可）

解析：[关于17题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/21)





### 第 18 题：React 中 setState 什么时候是同步的，什么时候是异步的？

解析：[第18题：React 中 setState 什么时候是同步的，什么时候是异步的？](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/17)





### 第 19 题：React setState 笔试题，下面的代码输出什么？

```js
class Example extends React.Component {
  constructor() {
    super();
    this.state = {
      val: 0
    };
  }
  
  componentDidMount() {
    this.setState({val: this.state.val + 1});
    console.log(this.state.val);    // 第 1 次 log

    this.setState({val: this.state.val + 1});
    console.log(this.state.val);    // 第 2 次 log

    setTimeout(() => {
      this.setState({val: this.state.val + 1});
      console.log(this.state.val);  // 第 3 次 log

      this.setState({val: this.state.val + 1});
      console.log(this.state.val);  // 第 4 次 log
    }, 0);
  }

  render() {
    return null;
  }
};
```

解析：[关于第19题的见解](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/18)



### 第 20 题：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？

解析：[第20题：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/22)





### 第 21 题：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣

> Object.prototype.toString.call() 、 instanceof 以及 Array.isArray() 

解析：[第21题：介绍它们之间的区别和优劣](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/23)





### 第 22 题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化

解析：[第22题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/24)





### 第 23 题：介绍下观察者模式和订阅-发布模式的区别，各自适用于什么场景

解析：[第 23 题：介绍下观察者模式和订阅\-发布模式的区别，各自适用于什么场景](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/25)





### 第 24 题：聊聊 Redux 和 Vuex 的设计思想

解析：[第 24 题：聊聊 Redux 和 Vuex 的设计思想](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/45)





### 第 25 题：说说浏览器和 Node 事件循环的区别

解析：[第25题：浏览器和Node 事件循环的区别](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/26)

 



### 第 26 题：介绍模块化发展历程

可从IIFE、AMD、CMD、CommonJS、UMD、webpack(require.ensure)、ES Module、`<script type="module">` 这几个角度考虑。

解析：[第26 题: 前端中的模块化开发](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/28)





### 第 27 题：全局作用域中，用 const 和 let 声明的变量不在 window 上，那到底在哪里？如何去获取？。

解析：[第27题：关于 const 和 let 声明的变量不在 window 上](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/30)





### 第 28 题：cookie 和 token 都存放在 header 中，为什么不会劫持 token？

解析：[第28题：cookie 和 token 都存放在 header 中，为什么不会劫持 token？](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/31)





### 第 29 题：聊聊 Vue 的双向数据绑定，Model 如何改变 View，View 又是如何改变 Model 的

解析：[第29题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/34)





### 第 30 题：两个数组合并成一个数组

请把两个数组 ['A1', 'A2', 'B1', 'B2', 'C1', 'C2', 'D1', 'D2'] 和 ['A', 'B', 'C', 'D']，合并为 ['A1', 'A2', 'A', 'B1', 'B2', 'B', 'C1', 'C2', 'C', 'D1', 'D2', 'D']。

解析： [第 30 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/39)





### 第 31 题：改造下面的代码，使之输出0 - 9，写出你能想到的所有解法。

```js
for (var i = 0; i< 10; i++){
	setTimeout(() => {
		console.log(i);
    }, 1000)
}
```

解析：[第 31 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/43)





### 第 32 题：Virtual DOM 真的比操作原生 DOM 快吗？谈谈你的想法。

解析：[第 32 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/47)





### 第 33 题：下面的代码打印什么内容，为什么？

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

解析：[第 33 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/48)





### 第 34 题：简单改造下面的代码，使之分别打印 10 和 20。

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

解析：[第 34 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/51)

