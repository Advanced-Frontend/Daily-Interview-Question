<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [前端面试题及答案汇总](#%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%8A%E7%AD%94%E6%A1%88%E6%B1%87%E6%80%BB)
  - [第 1 题：写 React / Vue 项目时为什么要在列表组件中写 key，其作用是什么？](#%E7%AC%AC-1-%E9%A2%98%E5%86%99-react--vue-%E9%A1%B9%E7%9B%AE%E6%97%B6%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%9C%A8%E5%88%97%E8%A1%A8%E7%BB%84%E4%BB%B6%E4%B8%AD%E5%86%99-key%E5%85%B6%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)
  - [第 2 题：`['1', '2', '3'].map(parseInt)` what & why ?](#%E7%AC%AC-2-%E9%A2%981-2-3mapparseint-what--why-)
  - [第 3 题：什么是防抖和节流？有什么区别？如何实现？](#%E7%AC%AC-3-%E9%A2%98%E4%BB%80%E4%B9%88%E6%98%AF%E9%98%B2%E6%8A%96%E5%92%8C%E8%8A%82%E6%B5%81%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 4 题：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？](#%E7%AC%AC-4-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B-setmapweakset-%E5%92%8C-weakmap-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 5 题：介绍下深度优先遍历和广度优先遍历，如何实现？](#%E7%AC%AC-5-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E9%81%8D%E5%8E%86%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0)
  - [第 6 题：请分别用深度优先思想和广度优先思想实现一个拷贝函数？](#%E7%AC%AC-6-%E9%A2%98%E8%AF%B7%E5%88%86%E5%88%AB%E7%94%A8%E6%B7%B1%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%92%8C%E5%B9%BF%E5%BA%A6%E4%BC%98%E5%85%88%E6%80%9D%E6%83%B3%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E6%8B%B7%E8%B4%9D%E5%87%BD%E6%95%B0)
  - [第 7 题：ES5/ES6 的继承除了写法以外还有什么区别？](#%E7%AC%AC-7-%E9%A2%98es5es6-%E7%9A%84%E7%BB%A7%E6%89%BF%E9%99%A4%E4%BA%86%E5%86%99%E6%B3%95%E4%BB%A5%E5%A4%96%E8%BF%98%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
  - [第 8 题：setTimeout、Promise、Async/Await 的区别](#%E7%AC%AC-8-%E9%A2%98settimeoutpromiseasyncawait-%E7%9A%84%E5%8C%BA%E5%88%AB)
  - [第 9 题：Async/Await 如何通过同步的方式实现异步](#%E7%AC%AC-9-%E9%A2%98asyncawait-%E5%A6%82%E4%BD%95%E9%80%9A%E8%BF%87%E5%90%8C%E6%AD%A5%E7%9A%84%E6%96%B9%E5%BC%8F%E5%AE%9E%E7%8E%B0%E5%BC%82%E6%AD%A5)
  - [第 10 题：异步笔试题](#%E7%AC%AC-10-%E9%A2%98%E5%BC%82%E6%AD%A5%E7%AC%94%E8%AF%95%E9%A2%98)
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
  - [第 35 题：浏览器缓存读取规则](#%E7%AC%AC-35-%E9%A2%98%E6%B5%8F%E8%A7%88%E5%99%A8%E7%BC%93%E5%AD%98%E8%AF%BB%E5%8F%96%E8%A7%84%E5%88%99)
  - [第 36 题：使用迭代的方式实现 flatten 函数。](#%E7%AC%AC-36-%E9%A2%98%E4%BD%BF%E7%94%A8%E8%BF%AD%E4%BB%A3%E7%9A%84%E6%96%B9%E5%BC%8F%E5%AE%9E%E7%8E%B0-flatten-%E5%87%BD%E6%95%B0)
  - [第 37 题：为什么 Vuex 的 mutation 和 Redux 的 reducer 中不能做异步操作？](#%E7%AC%AC-37-%E9%A2%98%E4%B8%BA%E4%BB%80%E4%B9%88-vuex-%E7%9A%84-mutation-%E5%92%8C-redux-%E7%9A%84-reducer-%E4%B8%AD%E4%B8%8D%E8%83%BD%E5%81%9A%E5%BC%82%E6%AD%A5%E6%93%8D%E4%BD%9C)
  - [第 38 题：下面代码中 a 在什么情况下会打印 1？](#%E7%AC%AC-38-%E9%A2%98%E4%B8%8B%E9%9D%A2%E4%BB%A3%E7%A0%81%E4%B8%AD-a-%E5%9C%A8%E4%BB%80%E4%B9%88%E6%83%85%E5%86%B5%E4%B8%8B%E4%BC%9A%E6%89%93%E5%8D%B0-1)
  - [第 39 题：介绍下 BFC 及其应用。](#%E7%AC%AC-39-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B-bfc-%E5%8F%8A%E5%85%B6%E5%BA%94%E7%94%A8)
  - [第 40 题：在 Vue 中，子组件为何不可以修改父组件传递的 Prop](#%E7%AC%AC-40-%E9%A2%98%E5%9C%A8-vue-%E4%B8%AD%E5%AD%90%E7%BB%84%E4%BB%B6%E4%B8%BA%E4%BD%95%E4%B8%8D%E5%8F%AF%E4%BB%A5%E4%BF%AE%E6%94%B9%E7%88%B6%E7%BB%84%E4%BB%B6%E4%BC%A0%E9%80%92%E7%9A%84-prop)
  - [第 41 题：下面代码输出什么](#%E7%AC%AC-41-%E9%A2%98%E4%B8%8B%E9%9D%A2%E4%BB%A3%E7%A0%81%E8%BE%93%E5%87%BA%E4%BB%80%E4%B9%88)
  - [第 42 题：实现一个 sleep 函数](#%E7%AC%AC-42-%E9%A2%98%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-sleep-%E5%87%BD%E6%95%B0)
  - [第 43 题：使用 sort() 对数组 [3, 15, 8, 29, 102, 22] 进行排序，输出结果](#%E7%AC%AC-43-%E9%A2%98%E4%BD%BF%E7%94%A8-sort-%E5%AF%B9%E6%95%B0%E7%BB%84-3-15-8-29-102-22-%E8%BF%9B%E8%A1%8C%E6%8E%92%E5%BA%8F%E8%BE%93%E5%87%BA%E7%BB%93%E6%9E%9C)
  - [第 44 题：介绍 HTTPS 握手过程](#%E7%AC%AC-44-%E9%A2%98%E4%BB%8B%E7%BB%8D-https-%E6%8F%A1%E6%89%8B%E8%BF%87%E7%A8%8B)
  - [第 45 题：HTTPS 握手过程中，客户端如何验证证书的合法性](#%E7%AC%AC-45-%E9%A2%98https-%E6%8F%A1%E6%89%8B%E8%BF%87%E7%A8%8B%E4%B8%AD%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%A6%82%E4%BD%95%E9%AA%8C%E8%AF%81%E8%AF%81%E4%B9%A6%E7%9A%84%E5%90%88%E6%B3%95%E6%80%A7)
  - [第 46 题：输出以下代码执行的结果并解释为什么](#%E7%AC%AC-46-%E9%A2%98%E8%BE%93%E5%87%BA%E4%BB%A5%E4%B8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E7%9A%84%E7%BB%93%E6%9E%9C%E5%B9%B6%E8%A7%A3%E9%87%8A%E4%B8%BA%E4%BB%80%E4%B9%88)
  - [第 47 题：双向绑定和 vuex 是否冲突](#%E7%AC%AC-47-%E9%A2%98%E5%8F%8C%E5%90%91%E7%BB%91%E5%AE%9A%E5%92%8C-vuex-%E6%98%AF%E5%90%A6%E5%86%B2%E7%AA%81)
  - [第 48 题：call 和 apply 的区别是什么，哪个性能更好一些](#%E7%AC%AC-48-%E9%A2%98call-%E5%92%8C-apply-%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88%E5%93%AA%E4%B8%AA%E6%80%A7%E8%83%BD%E6%9B%B4%E5%A5%BD%E4%B8%80%E4%BA%9B)
  - [第 49 题：为什么通常在发送数据埋点请求的时候使用的是 1x1 像素的透明 gif 图片？](#%E7%AC%AC-49-%E9%A2%98%E4%B8%BA%E4%BB%80%E4%B9%88%E9%80%9A%E5%B8%B8%E5%9C%A8%E5%8F%91%E9%80%81%E6%95%B0%E6%8D%AE%E5%9F%8B%E7%82%B9%E8%AF%B7%E6%B1%82%E7%9A%84%E6%97%B6%E5%80%99%E4%BD%BF%E7%94%A8%E7%9A%84%E6%98%AF-1x1-%E5%83%8F%E7%B4%A0%E7%9A%84%E9%80%8F%E6%98%8E-gif-%E5%9B%BE%E7%89%87)
  - [第 50 题：实现 (5).add(3).minus(2) 功能。](#%E7%AC%AC-50-%E9%A2%98%E5%AE%9E%E7%8E%B0-5add3minus2-%E5%8A%9F%E8%83%BD)
  - [第 51 题：Vue 的响应式原理中 Object.defineProperty 有什么缺陷？](#%E7%AC%AC-51-%E9%A2%98vue-%E7%9A%84%E5%93%8D%E5%BA%94%E5%BC%8F%E5%8E%9F%E7%90%86%E4%B8%AD-objectdefineproperty-%E6%9C%89%E4%BB%80%E4%B9%88%E7%BC%BA%E9%99%B7)
  - [第 52 题：怎么让一个 div 水平垂直居中](#%E7%AC%AC-52-%E9%A2%98%E6%80%8E%E4%B9%88%E8%AE%A9%E4%B8%80%E4%B8%AA-div-%E6%B0%B4%E5%B9%B3%E5%9E%82%E7%9B%B4%E5%B1%85%E4%B8%AD)
  - [第 53 题：输出以下代码的执行结果并解释为什么](#%E7%AC%AC-53-%E9%A2%98%E8%BE%93%E5%87%BA%E4%BB%A5%E4%B8%8B%E4%BB%A3%E7%A0%81%E7%9A%84%E6%89%A7%E8%A1%8C%E7%BB%93%E6%9E%9C%E5%B9%B6%E8%A7%A3%E9%87%8A%E4%B8%BA%E4%BB%80%E4%B9%88)
  - [第 54 题：冒泡排序如何实现，时间复杂度是多少， 还可以如何改进？](#%E7%AC%AC-54-%E9%A2%98%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0%E6%97%B6%E9%97%B4%E5%A4%8D%E6%9D%82%E5%BA%A6%E6%98%AF%E5%A4%9A%E5%B0%91-%E8%BF%98%E5%8F%AF%E4%BB%A5%E5%A6%82%E4%BD%95%E6%94%B9%E8%BF%9B)
  - [第 55 题：某公司 1 到 12 月份的销售额存在一个对象里面](#%E7%AC%AC-55-%E9%A2%98%E6%9F%90%E5%85%AC%E5%8F%B8-1-%E5%88%B0-12-%E6%9C%88%E4%BB%BD%E7%9A%84%E9%94%80%E5%94%AE%E9%A2%9D%E5%AD%98%E5%9C%A8%E4%B8%80%E4%B8%AA%E5%AF%B9%E8%B1%A1%E9%87%8C%E9%9D%A2)
  - [第 56 题：要求设计 LazyMan 类，实现以下功能。](#%E7%AC%AC-56-%E9%A2%98%E8%A6%81%E6%B1%82%E8%AE%BE%E8%AE%A1-lazyman-%E7%B1%BB%E5%AE%9E%E7%8E%B0%E4%BB%A5%E4%B8%8B%E5%8A%9F%E8%83%BD)
  - [第 57 题：分析比较 opacity: 0、visibility: hidden、display: none 优劣和适用场景。](#%E7%AC%AC-57-%E9%A2%98%E5%88%86%E6%9E%90%E6%AF%94%E8%BE%83-opacity-0visibility-hiddendisplay-none-%E4%BC%98%E5%8A%A3%E5%92%8C%E9%80%82%E7%94%A8%E5%9C%BA%E6%99%AF)
  - [第 58 题：箭头函数与普通函数（function）的区别是什么？构造函数（function）可以使用 new 生成实例，那么箭头函数可以吗？为什么？](#%E7%AC%AC-58-%E9%A2%98%E7%AE%AD%E5%A4%B4%E5%87%BD%E6%95%B0%E4%B8%8E%E6%99%AE%E9%80%9A%E5%87%BD%E6%95%B0function%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88%E6%9E%84%E9%80%A0%E5%87%BD%E6%95%B0function%E5%8F%AF%E4%BB%A5%E4%BD%BF%E7%94%A8-new-%E7%94%9F%E6%88%90%E5%AE%9E%E4%BE%8B%E9%82%A3%E4%B9%88%E7%AE%AD%E5%A4%B4%E5%87%BD%E6%95%B0%E5%8F%AF%E4%BB%A5%E5%90%97%E4%B8%BA%E4%BB%80%E4%B9%88)
  - [第 59 题：给定两个数组，写一个方法来计算它们的交集。](#%E7%AC%AC-59-%E9%A2%98%E7%BB%99%E5%AE%9A%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E5%86%99%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E6%9D%A5%E8%AE%A1%E7%AE%97%E5%AE%83%E4%BB%AC%E7%9A%84%E4%BA%A4%E9%9B%86)
  - [第 60 题：已知如下代码，如何修改才能让图片宽度为 300px ？注意下面代码不可修改。](#%E7%AC%AC-60-%E9%A2%98%E5%B7%B2%E7%9F%A5%E5%A6%82%E4%B8%8B%E4%BB%A3%E7%A0%81%E5%A6%82%E4%BD%95%E4%BF%AE%E6%94%B9%E6%89%8D%E8%83%BD%E8%AE%A9%E5%9B%BE%E7%89%87%E5%AE%BD%E5%BA%A6%E4%B8%BA-300px-%E6%B3%A8%E6%84%8F%E4%B8%8B%E9%9D%A2%E4%BB%A3%E7%A0%81%E4%B8%8D%E5%8F%AF%E4%BF%AE%E6%94%B9)
  - [第 61 题：介绍下如何实现 token 加密](#%E7%AC%AC-61-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0-token-%E5%8A%A0%E5%AF%86)
  - [第 62 题：redux 为什么要把 reducer 设计成纯函数](#%E7%AC%AC-62-%E9%A2%98redux-%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E6%8A%8A-reducer-%E8%AE%BE%E8%AE%A1%E6%88%90%E7%BA%AF%E5%87%BD%E6%95%B0)
  - [第 63 题：如何设计实现无缝轮播](#%E7%AC%AC-63-%E9%A2%98%E5%A6%82%E4%BD%95%E8%AE%BE%E8%AE%A1%E5%AE%9E%E7%8E%B0%E6%97%A0%E7%BC%9D%E8%BD%AE%E6%92%AD)
  - [第 64 题：模拟实现一个 Promise.finally](#%E7%AC%AC-64-%E9%A2%98%E6%A8%A1%E6%8B%9F%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-promisefinally)
  - [第 65 题： `a.b.c.d` 和 `a['b']['c']['d']`，哪个性能更高？](#%E7%AC%AC-65-%E9%A2%98-abcd-%E5%92%8C-abcd%E5%93%AA%E4%B8%AA%E6%80%A7%E8%83%BD%E6%9B%B4%E9%AB%98)
  - [第 66 题：ES6 代码转成 ES5 代码的实现思路是什么](#%E7%AC%AC-66-%E9%A2%98es6-%E4%BB%A3%E7%A0%81%E8%BD%AC%E6%88%90-es5-%E4%BB%A3%E7%A0%81%E7%9A%84%E5%AE%9E%E7%8E%B0%E6%80%9D%E8%B7%AF%E6%98%AF%E4%BB%80%E4%B9%88)
  - [第 67 题：数组编程题](#%E7%AC%AC-67-%E9%A2%98%E6%95%B0%E7%BB%84%E7%BC%96%E7%A8%8B%E9%A2%98)
  - [第 68 题： 如何解决移动端 Retina 屏 1px 像素问题](#%E7%AC%AC-68-%E9%A2%98-%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3%E7%A7%BB%E5%8A%A8%E7%AB%AF-retina-%E5%B1%8F-1px-%E5%83%8F%E7%B4%A0%E9%97%AE%E9%A2%98)
  - [第 69 题： 如何把一个字符串的大小写取反（大写变小写小写变大写），例如 ’AbC' 变成 'aBc' 。](#%E7%AC%AC-69-%E9%A2%98-%E5%A6%82%E4%BD%95%E6%8A%8A%E4%B8%80%E4%B8%AA%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%86%99%E5%8F%96%E5%8F%8D%E5%A4%A7%E5%86%99%E5%8F%98%E5%B0%8F%E5%86%99%E5%B0%8F%E5%86%99%E5%8F%98%E5%A4%A7%E5%86%99%E4%BE%8B%E5%A6%82-abc-%E5%8F%98%E6%88%90-abc-)
  - [第 70 题： 介绍下 webpack 热更新原理，是如何做到在不刷新浏览器的前提下更新页面的](#%E7%AC%AC-70-%E9%A2%98-%E4%BB%8B%E7%BB%8D%E4%B8%8B-webpack-%E7%83%AD%E6%9B%B4%E6%96%B0%E5%8E%9F%E7%90%86%E6%98%AF%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E5%9C%A8%E4%B8%8D%E5%88%B7%E6%96%B0%E6%B5%8F%E8%A7%88%E5%99%A8%E7%9A%84%E5%89%8D%E6%8F%90%E4%B8%8B%E6%9B%B4%E6%96%B0%E9%A1%B5%E9%9D%A2%E7%9A%84)
  - [第 71 题： 实现一个字符串匹配算法，从长度为 n 的字符串 S 中，查找是否存在字符串 T，T 的长度是 m，若存在返回所在位置。](#%E7%AC%AC-71-%E9%A2%98-%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%8C%B9%E9%85%8D%E7%AE%97%E6%B3%95%E4%BB%8E%E9%95%BF%E5%BA%A6%E4%B8%BA-n-%E7%9A%84%E5%AD%97%E7%AC%A6%E4%B8%B2-s-%E4%B8%AD%E6%9F%A5%E6%89%BE%E6%98%AF%E5%90%A6%E5%AD%98%E5%9C%A8%E5%AD%97%E7%AC%A6%E4%B8%B2-tt-%E7%9A%84%E9%95%BF%E5%BA%A6%E6%98%AF-m%E8%8B%A5%E5%AD%98%E5%9C%A8%E8%BF%94%E5%9B%9E%E6%89%80%E5%9C%A8%E4%BD%8D%E7%BD%AE)
  - [第 72 题： 为什么普通 `for` 循环的性能远远高于 `forEach` 的性能，请解释其中的原因。](#%E7%AC%AC-72-%E9%A2%98-%E4%B8%BA%E4%BB%80%E4%B9%88%E6%99%AE%E9%80%9A-for-%E5%BE%AA%E7%8E%AF%E7%9A%84%E6%80%A7%E8%83%BD%E8%BF%9C%E8%BF%9C%E9%AB%98%E4%BA%8E-foreach-%E7%9A%84%E6%80%A7%E8%83%BD%E8%AF%B7%E8%A7%A3%E9%87%8A%E5%85%B6%E4%B8%AD%E7%9A%84%E5%8E%9F%E5%9B%A0)
  - [第 73 题： 介绍下 BFC、IFC、GFC 和 FFC](#%E7%AC%AC-73-%E9%A2%98-%E4%BB%8B%E7%BB%8D%E4%B8%8B-bfcifcgfc-%E5%92%8C-ffc)
  - [第 74 题： 使用 JavaScript Proxy 实现简单的数据绑定](#%E7%AC%AC-74-%E9%A2%98-%E4%BD%BF%E7%94%A8-javascript-proxy-%E5%AE%9E%E7%8E%B0%E7%AE%80%E5%8D%95%E7%9A%84%E6%95%B0%E6%8D%AE%E7%BB%91%E5%AE%9A)
  - [第 75 题：数组里面有10万个数据，取第一个元素和第10万个元素的时间相差多少](#%E7%AC%AC-75-%E9%A2%98%E6%95%B0%E7%BB%84%E9%87%8C%E9%9D%A2%E6%9C%8910%E4%B8%87%E4%B8%AA%E6%95%B0%E6%8D%AE%E5%8F%96%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%85%83%E7%B4%A0%E5%92%8C%E7%AC%AC10%E4%B8%87%E4%B8%AA%E5%85%83%E7%B4%A0%E7%9A%84%E6%97%B6%E9%97%B4%E7%9B%B8%E5%B7%AE%E5%A4%9A%E5%B0%91)
  - [第 76 题：输出以下代码运行结果](#%E7%AC%AC-76-%E9%A2%98%E8%BE%93%E5%87%BA%E4%BB%A5%E4%B8%8B%E4%BB%A3%E7%A0%81%E8%BF%90%E8%A1%8C%E7%BB%93%E6%9E%9C)
  - [第 77 题：算法题「旋转数组」](#%E7%AC%AC-77-%E9%A2%98%E7%AE%97%E6%B3%95%E9%A2%98%E6%97%8B%E8%BD%AC%E6%95%B0%E7%BB%84)
  - [第 78 题：Vue 的父组件和子组件生命周期钩子执行顺序是什么](#%E7%AC%AC-78-%E9%A2%98vue-%E7%9A%84%E7%88%B6%E7%BB%84%E4%BB%B6%E5%92%8C%E5%AD%90%E7%BB%84%E4%BB%B6%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%E9%92%A9%E5%AD%90%E6%89%A7%E8%A1%8C%E9%A1%BA%E5%BA%8F%E6%98%AF%E4%BB%80%E4%B9%88)
  - [第 79 题：input 搜索如何防抖，如何处理中文输入](#%E7%AC%AC-79-%E9%A2%98input-%E6%90%9C%E7%B4%A2%E5%A6%82%E4%BD%95%E9%98%B2%E6%8A%96%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86%E4%B8%AD%E6%96%87%E8%BE%93%E5%85%A5)
  - [第 80 题：介绍下 Promise.all 使用、原理实现及错误处理](#%E7%AC%AC-80-%E9%A2%98%E4%BB%8B%E7%BB%8D%E4%B8%8B-promiseall-%E4%BD%BF%E7%94%A8%E5%8E%9F%E7%90%86%E5%AE%9E%E7%8E%B0%E5%8F%8A%E9%94%99%E8%AF%AF%E5%A4%84%E7%90%86)
  - [第 81 题：打印出 1 - 10000 之间的所有对称数](#%E7%AC%AC-81-%E9%A2%98%E6%89%93%E5%8D%B0%E5%87%BA-1---10000-%E4%B9%8B%E9%97%B4%E7%9A%84%E6%89%80%E6%9C%89%E5%AF%B9%E7%A7%B0%E6%95%B0)
  - [第 82 题：周一算法题之「移动零」](#%E7%AC%AC-82-%E9%A2%98%E5%91%A8%E4%B8%80%E7%AE%97%E6%B3%95%E9%A2%98%E4%B9%8B%E7%A7%BB%E5%8A%A8%E9%9B%B6)
  - [第 83 题：var、let 和 const 区别的实现原理是什么](#%E7%AC%AC-83-%E9%A2%98varlet-%E5%92%8C-const-%E5%8C%BA%E5%88%AB%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86%E6%98%AF%E4%BB%80%E4%B9%88)
  - [第 84 题：请实现一个 add 函数，满足以下功能。](#%E7%AC%AC-84-%E9%A2%98%E8%AF%B7%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA-add-%E5%87%BD%E6%95%B0%E6%BB%A1%E8%B6%B3%E4%BB%A5%E4%B8%8B%E5%8A%9F%E8%83%BD)
  - [第 85 题：react-router 里的 `<Link>` 标签和 `<a>` 标签有什么区别](#%E7%AC%AC-85-%E9%A2%98react-router-%E9%87%8C%E7%9A%84-link-%E6%A0%87%E7%AD%BE%E5%92%8C-a-%E6%A0%87%E7%AD%BE%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->





## 前端面试题及答案汇总



### 第 1 题：写 React / Vue 项目时为什么要在列表组件中写 key，其作用是什么？

解析：[第 1 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)

<br/>



### 第 2 题：`['1', '2', '3'].map(parseInt)` what & why ?

解析：[第 2 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/4)

<br/>



### 第 3 题：什么是防抖和节流？有什么区别？如何实现？

解析：[第 3 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/5)

<br/>



### 第 4 题：介绍下 Set、Map、WeakSet 和 WeakMap 的区别？

解析：[第 4 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/6)

<br/>



### 第 5 题：介绍下深度优先遍历和广度优先遍历，如何实现？

解析：[第 5 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/9)

<br/>



### 第 6 题：请分别用深度优先思想和广度优先思想实现一个拷贝函数？

解析：[第 6 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/10)

<br/>



### 第 7 题：ES5/ES6 的继承除了写法以外还有什么区别？

解析：[第 7 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/20)

<br/>



### 第 8 题：setTimeout、Promise、Async/Await 的区别

解析：[第 8 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/33)

<br/>



### 第 9 题：Async/Await 如何通过同步的方式实现异步

欢迎在 Issue 区留下你的答案。

<br/>



### 第 10 题：异步笔试题

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

解析：[第 10 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/7)

<br/>



### 第 11 题：算法手写题

> 已知如下数组：
>
> var arr = [ [1, 2, 2], [3, 4, 5, 5], [6, 7, 8, 9, [11, 12, [12, 13, [14] ] ] ], 10];
>
> 编写一个程序将数组扁平化去并除其中重复部分数据，最终得到一个升序且不重复的数组

解析：[第 11 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/8)

<br/>



### 第 12 题：JS 异步解决方案的发展历程以及优缺点。

解析：[第 12 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/11)

<br/>



### 第 13 题：Promise 构造函数是同步执行还是异步执行，那么 then 方法呢？

解析：[第 13 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/19)

<br/>



### 第 14 题：情人节福利题，如何实现一个 new

解析：[第 14 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/12)

<br/>



### 第 15 题：简单讲解一下http2的多路复用

解析：[第 15 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/14)

<br/>



### 第 16 题：谈谈你对TCP三次握手和四次挥手的理解

解析：[第 16 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/15)

<br/>



### 第 17 题：A、B 机器正常连接后，B 机器突然重启，问 A 此时处于 TCP 什么状态

> 如果A 与 B 建立了正常连接后，从未相互发过数据，这个时候 B 突然机器重启，问 A 此时处于 TCP 什么状态？如何消除服务器程序中的这个状态？（超纲题，了解即可）

解析：[第 17 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/21)

<br/>



### 第 18 题：React 中 setState 什么时候是同步的，什么时候是异步的？

解析：[第 18 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/17)

<br/>



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

解析：[第 19 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/18)

<br/>



### 第 20 题：介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？

解析：[第 20 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/22)

<br/>



### 第 21 题：有以下 3 个判断数组的方法，请分别介绍它们之间的区别和优劣

> Object.prototype.toString.call() 、 instanceof 以及 Array.isArray() 

解析：[第 21 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/23)

<br/>



### 第 22 题：介绍下重绘和回流（Repaint & Reflow），以及如何进行优化

解析：[第 22 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/24)

<br/>



### 第 23 题：介绍下观察者模式和订阅-发布模式的区别，各自适用于什么场景

解析：[第 23 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/25)

<br/>



### 第 24 题：聊聊 Redux 和 Vuex 的设计思想

解析：[第 24 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/45)

<br/>



### 第 25 题：说说浏览器和 Node 事件循环的区别

解析：[第 25 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/26)

<br/> 

### 第 26 题：介绍模块化发展历程

可从IIFE、AMD、CMD、CommonJS、UMD、webpack(require.ensure)、ES Module、`<script type="module">` 这几个角度考虑。

解析：[第 26 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/28)

<br/>



### 第 27 题：全局作用域中，用 const 和 let 声明的变量不在 window 上，那到底在哪里？如何去获取？。

解析：[第 27 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/30)

<br/>



### 第 28 题：cookie 和 token 都存放在 header 中，为什么不会劫持 token？

解析：[第 28 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/31)

<br/>



### 第 29 题：聊聊 Vue 的双向数据绑定，Model 如何改变 View，View 又是如何改变 Model 的

解析：[第 29 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/34)

<br/>



### 第 30 题：两个数组合并成一个数组

请把两个数组 ['A1', 'A2', 'B1', 'B2', 'C1', 'C2', 'D1', 'D2'] 和 ['A', 'B', 'C', 'D']，合并为 ['A1', 'A2', 'A', 'B1', 'B2', 'B', 'C1', 'C2', 'C', 'D1', 'D2', 'D']。

解析： [第 30 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/39)

<br/>



### 第 31 题：改造下面的代码，使之输出0 - 9，写出你能想到的所有解法。

```js
for (var i = 0; i< 10; i++){
	setTimeout(() => {
		console.log(i);
    }, 1000)
}
```

解析：[第 31 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/43)

<br/>



### 第 32 题：Virtual DOM 真的比操作原生 DOM 快吗？谈谈你的想法。

解析：[第 32 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/47)

<br/>



### 第 33 题：下面的代码打印什么内容，为什么？

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

解析：[第 33 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/48)

<br/>



### 第 34 题：简单改造下面的代码，使之分别打印 10 和 20。

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

解析：[第 34 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/51)

<br/>



### 第 35 题：浏览器缓存读取规则

可以分成 Service Worker、Memory Cache、Disk Cache 和 Push Cache，那请求的时候 from memory cache 和 from disk cache 的依据是什么，哪些数据什么时候存放在 Memory Cache 和 Disk Cache中？

解析：[第 35 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/53)

<br/>



### 第 36 题：使用迭代的方式实现 flatten 函数。

解析：[第 36 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/54)

<br/>



### 第 37 题：为什么 Vuex 的 mutation 和 Redux 的 reducer 中不能做异步操作？

解析：[第 37 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/65)

<br/>



### 第 38 题：下面代码中 a 在什么情况下会打印 1？

```js
var a = ?;
if(a == 1 && a == 2 && a == 3){
 	console.log(1);
}
```

解析：[第 38 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/57)

<br/>



### 第 39 题：介绍下 BFC 及其应用。

解析：[第 39 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/59)

<br/>



### 第 40 题：在 Vue 中，子组件为何不可以修改父组件传递的 Prop

如果修改了，Vue 是如何监控到属性的修改并给出警告的。

解析：[第 40 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/60)

<br/>



### 第 41 题：下面代码输出什么

```js
var a = 10;
(function () {
    console.log(a)
    a = 5
    console.log(window.a)
    var a = 20;
    console.log(a)
})()
```

解析：[第 41题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/61)

<br/>



### 第 42 题：实现一个 sleep 函数

比如 sleep(1000) 意味着等待1000毫秒，可从 Promise、Generator、Async/Await 等角度实现

解析：[第 42 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/63)

<br/>



### 第 43 题：使用 sort() 对数组 [3, 15, 8, 29, 102, 22] 进行排序，输出结果

解析：[第 43 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/66)

<br/>



### 第 44 题：介绍 HTTPS 握手过程

解析：[第 44 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/70)

<br/>



### 第 45 题：HTTPS 握手过程中，客户端如何验证证书的合法性

解析：[第 45 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/74)

<br/>



### 第 46 题：输出以下代码执行的结果并解释为什么

```js
var obj = {
    '2': 3,
    '3': 4,
    'length': 2,
    'splice': Array.prototype.splice,
    'push': Array.prototype.push
}
obj.push(1)
obj.push(2)
console.log(obj)
```

解析：[第 46 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/76)

<br/>



### 第 47 题：双向绑定和 vuex 是否冲突

解析：[第 47 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/81)

<br/>



### 第 48 题：call 和 apply 的区别是什么，哪个性能更好一些

解析：[第 48 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/84)

<br/>



### 第 49 题：为什么通常在发送数据埋点请求的时候使用的是 1x1 像素的透明 gif 图片？

解析：[第 49 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/87)

<br/>



### 第 50 题：实现 (5).add(3).minus(2) 功能。

> 例： 5 + 3 - 2，结果为 6

解析：[第 50 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/88)

<br/>



### 第 51 题：Vue 的响应式原理中 Object.defineProperty 有什么缺陷？

为什么在 Vue3.0 采用了 Proxy，抛弃了 Object.defineProperty？

解析：[第 51 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/90)

<br/>



### 第 52 题：怎么让一个 div 水平垂直居中

解析：[第 52 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/92)

<br/>



### 第 53 题：输出以下代码的执行结果并解释为什么

```js
var a = {n: 1};
var b = a;
a.x = a = {n: 2};

console.log(a.x) 	
console.log(b.x)
```

解析：[第 53 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/93)

<br/>



### 第 54 题：冒泡排序如何实现，时间复杂度是多少， 还可以如何改进？

解析：[第 54 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/94)

<br/>



### 第 55 题：某公司 1 到 12 月份的销售额存在一个对象里面

如下：{1:222, 2:123, 5:888}，请把数据处理为如下结构：[222, 123, null, null, 888, null, null, null, null, null, null, null]。

解析：[第 55 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/96)

<br/>



### 第 56 题：要求设计 LazyMan 类，实现以下功能。 

```js
LazyMan('Tony');
// Hi I am Tony

LazyMan('Tony').sleep(10).eat('lunch');
// Hi I am Tony
// 等待了10秒...
// I am eating lunch

LazyMan('Tony').eat('lunch').sleep(10).eat('dinner');
// Hi I am Tony
// I am eating lunch
// 等待了10秒...
// I am eating diner

LazyMan('Tony').eat('lunch').eat('dinner').sleepFirst(5).sleep(10).eat('junk food');
// Hi I am Tony
// 等待了5秒...
// I am eating lunch
// I am eating dinner
// 等待了10秒...
// I am eating junk food
```

解析：[第 56 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/98)

<br/>



### 第 57 题：分析比较 opacity: 0、visibility: hidden、display: none 优劣和适用场景。 

解析：[第 57 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/100)

<br/>



### 第 58 题：箭头函数与普通函数（function）的区别是什么？构造函数（function）可以使用 new 生成实例，那么箭头函数可以吗？为什么？

解析：[第 58 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/101)

<br/>



### 第 59 题：给定两个数组，写一个方法来计算它们的交集。

> 例如：给定 nums1 = [1, 2, 2, 1]，nums2 = [2, 2]，返回 [2, 2]。

解析：[第 59 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/102)

<br/>



### 第 60 题：已知如下代码，如何修改才能让图片宽度为 300px ？注意下面代码不可修改。

> `<img src="1.jpg" style="width:480px!important;”>`

解析：[第 60 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/105)

<br/>



### 第 61 题：介绍下如何实现 token 加密

解析：[第 61 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/106)

<br/>



### 第 62 题：redux 为什么要把 reducer 设计成纯函数

解析：[第 62 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/107)

<br/>



### 第 63 题：如何设计实现无缝轮播

解析：[第 63 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/108)

<br/>



### 第 64 题：模拟实现一个 Promise.finally

解析：[第 64 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/109)

<br/>



### 第 65 题： `a.b.c.d` 和 `a['b']['c']['d']`，哪个性能更高？

解析：[第 65 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/111)

<br/>



### 第 66 题：ES6 代码转成 ES5 代码的实现思路是什么

解析：[第 66 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/112)

<br/>



### 第 67 题：数组编程题

随机生成一个长度为 10 的整数类型的数组，例如 `[2, 10, 3, 4, 5, 11, 10, 11, 20]`，将其排列成一个新数组，要求新数组形式如下，例如 `[[2, 3, 4, 5], [10, 11], [20]]`。

解析：[第 67 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/113)

<br/>



### 第 68 题： 如何解决移动端 Retina 屏 1px 像素问题

解析：[第 68 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/115)

<br/>



### 第 69 题： 如何把一个字符串的大小写取反（大写变小写小写变大写），例如 ’AbC' 变成 'aBc' 。

解析：[第 69 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/116)

<br/>



### 第 70 题： 介绍下 webpack 热更新原理，是如何做到在不刷新浏览器的前提下更新页面的

解析：[第 70 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/118)

<br/>



### 第 71 题： 实现一个字符串匹配算法，从长度为 n 的字符串 S 中，查找是否存在字符串 T，T 的长度是 m，若存在返回所在位置。

解析：[第 71 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/119)

<br/>



### 第 72 题： 为什么普通 `for` 循环的性能远远高于 `forEach` 的性能，请解释其中的原因。

![image-20190512225510941](https://ws2.sinaimg.cn/large/006tNc79gy1g2yxbg4ta8j31gh0u048h.jpg)



解析：[第 72 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/121)

<br/>



### 第 73 题： 介绍下 BFC、IFC、GFC 和 FFC

解析：[第 73 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/122)

<br/>



### 第 74 题： 使用 JavaScript Proxy 实现简单的数据绑定

解析：[第 74 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/123)

<br/>



### 第 75 题：数组里面有10万个数据，取第一个元素和第10万个元素的时间相差多少

解析：[第 75 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/124)

<br/>



### 第 76 题：输出以下代码运行结果

```js
// example 1
var a={}, b='123', c=123;  
a[b]='b';
a[c]='c';  
console.log(a[b]);

---------------------
// example 2
var a={}, b=Symbol('123'), c=Symbol('123');  
a[b]='b';
a[c]='c';  
console.log(a[b]);

---------------------
// example 3
var a={}, b={key:'123'}, c={key:'456'};  
a[b]='b';
a[c]='c';  
console.log(a[b]);
```

解析：[第 76 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/125)

<br/>



### 第 77 题：算法题「旋转数组」

> 给定一个数组，将数组中的元素向右移动 k 个位置，其中 k 是非负数。

示例 1：

```js
输入: [1, 2, 3, 4, 5, 6, 7] 和 k = 3
输出: [5, 6, 7, 1, 2, 3, 4]
解释:
向右旋转 1 步: [7, 1, 2, 3, 4, 5, 6]
向右旋转 2 步: [6, 7, 1, 2, 3, 4, 5]
向右旋转 3 步: [5, 6, 7, 1, 2, 3, 4]
```

示例 2：

```js
输入: [-1, -100, 3, 99] 和 k = 2
输出: [3, 99, -1, -100]
解释: 
向右旋转 1 步: [99, -1, -100, 3]
向右旋转 2 步: [3, 99, -1, -100]
```

解析：[第 77 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/126)

<br/>



### 第 78 题：Vue 的父组件和子组件生命周期钩子执行顺序是什么

解析：[第 78 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/128)

<br/>



### 第 79 题：input 搜索如何防抖，如何处理中文输入

解析：[第 79 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/129)

<br/>



### 第 80 题：介绍下 Promise.all 使用、原理实现及错误处理

解析：[第 80 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/130)

<br/>



### 第 81 题：打印出 1 - 10000 之间的所有对称数

> 例如：121、1331 等

解析：[第 81 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/131)

<br/>



### 第 82 题：周一算法题之「移动零」

> 给定一个数组 nums，编写一个函数将所有 0 移动到数组的末尾，同时保持非零元素的相对顺序。
>
> 示例:
>
> ```
> 输入: [0,1,0,3,12]
> 输出: [1,3,12,0,0]
> ```
>
> 说明:
>
> 1. 必须在原数组上操作，不能拷贝额外的数组。
>
> 1. 尽量减少操作次数。

解析：[第 82 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/132)

<br/>



### 第 83 题：var、let 和 const 区别的实现原理是什么

解析：[第 83 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/133)

<br/>



### 第 84 题：请实现一个 add 函数，满足以下功能。

> ```js
> add(1); 			// 1
> add(1)(2);  	// 3
> add(1)(2)(3)；// 6
> add(1)(2, 3); // 6
> add(1, 2)(3); // 6
> add(1, 2, 3); // 6
> ```

解析：[第 84 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/134)

<br/>



### 第 85 题：react-router 里的 `<Link>` 标签和 `<a>` 标签有什么区别

> 如何禁掉 `<a>` 标签默认事件，禁掉之后如何实现跳转。

解析：[第 85 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/135)

<br/>

