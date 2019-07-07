# Daily-Interview-Question

加入前端「壹题」学习小组，尽在公众号「高级前端进阶」，进阶共勉之！

工作日每天一道大厂前端面试题，一年后再回头，会感谢曾经努力的自己！

<br/>




## 今日面试题

2019-07-08

> 第 100 题：请写出如下代码的打印结果
>
> ```js
> function Foo() {
>     Foo.a = function() {
>         console.log(1)
>     }
>     this.a = function() {
>         console.log(2)
>     }
> }
> Foo.prototype.a = function() {
>     console.log(3)
> }
> Foo.a = function() {
>     console.log(4)
> }
> Foo.a();
> let obj = new Foo();
> obj.a();
> Foo.a();
> ```



公司：京东

解析：[第 100 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/155)

<br/>




## 本周汇总

2019-07-05

> 第 99 题：编程算法题
>
> 用 JavaScript 写一个函数，输入 int 型，返回整数逆序后的字符串。如：输入整型 1234，返回字符串“4321”。要求必须使用递归函数调用，不能用全局变量，输入函数必须只有一个参数传入，必须返回字符串。



公司：bilibili

解析：[第 99 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/153)

<br/>



2019-07-04

> 第 98 题：写出如下代码的打印结果

```js
function changeObjProperty(o) {
  o.siteUrl = "http://www.baidu.com"
  o = new Object()
  o.siteUrl = "http://www.google.com"
} 
let webSite = new Object();
changeObjProperty(webSite);
console.log(webSite.siteUrl);
```

公司：京东

解析：[第 98 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/152)

<br/>



2019-07-02

> 第 97 题：React 和 Vue 的 diff 时间复杂度从 O(n^3) 优化到 O(n) ，那么 O(n^3) 和 O(n) 是如何计算出来的？



解析：[第 97 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/151)

<br/>



2019-07-01

> 第 96 题：介绍下前端加密的常见场景和方法

解析：[第 96 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/150)

<br/>



## 历史汇总

-   [前端面试题及答案汇总](https://github.com/Advanced-Frontend/Daily-Interview-Question/blob/master/datum/summary.md)

<br/>



## 半月刊

- [【半月刊 1】前端高频面试题及答案汇总](https://juejin.im/post/5c6977e46fb9a049fd1063dc)
- [【半月刊 2】前端高频面试题及答案汇总](https://juejin.im/post/5c7bd72ef265da2de80f7f17)
- [【半月刊 3】前端高频面试题及答案汇总](https://juejin.im/post/5c9ac3f66fb9a070e056718f)
- [【半月刊 4】前端高频面试题及答案汇总](https://juejin.im/post/5cb3376bf265da039c0543da)

<br/>



## 交流

进阶系列文章汇总如下，觉得不错点个 star，欢迎 **加群** 互相学习。

> [https://github.com/yygmind/blog](https://github.com/yygmind/blog)

我是木易杨，公众号「高级前端进阶」作者，跟着我**每周重点攻克一个前端面试重难点**。接下来让我带你走进高级前端的世界，在进阶的路上，共勉！

![image](https://github.com/yygmind/blog/raw/master/images/weixin_re.png)
