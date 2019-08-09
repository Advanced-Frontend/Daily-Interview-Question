# Daily-Interview-Question

加入前端「壹题」学习小组，尽在公众号「高级前端进阶」，进阶共勉之！

工作日每天一道大厂前端面试题，一年后再回头，会感谢曾经努力的自己！

[线上版本阅读更流畅，点击阅读](https://muyiy.vip/question/)

<br/>




## 今日面试题
2019-08-09

> 第 123 题：vue 是如何对数组方法进行变异的？例如 push、pop、splice 等方法
>



解析：[第 123 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/239)

<br/>




## 本周汇总
2019-08-08

> 第 122 题：webpack 打包 vue 速度太慢怎么办？



解析：[第 122 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/238)

<br/>



2019-08-07

> 第 121 题：统计 1 ~ n 整数中出现 1 的次数。
>
> 例如统计 1 ~ 400W 出现 1 的次数。



解析：[第 121 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/237)

<br/>



2019-08-05

> 第 120 题：为什么 for 循环嵌套顺序会影响性能？

```js
var t1 = new Date().getTime()
for (let i = 0; i < 100; i++) {
  for (let j = 0; j < 1000; j++) {
    for (let k = 0; k < 10000; k++) {
    }
  }
}
var t2 = new Date().getTime()
console.log('first time', t2 - t1)

for (let i = 0; i < 10000; i++) {
  for (let j = 0; j < 1000; j++) {
    for (let k = 0; k < 100; k++) {

    }
  }
}
var t3 = new Date().getTime()
console.log('two time', t3 - t2)
```



解析：[第 120 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/235)

<br/>



## 所有面试题汇总

-   [壹题所有题目及答案汇总](https://github.com/Advanced-Frontend/Daily-Interview-Question/blob/master/datum/summary.md)

<br/>



## 半月刊

- [前端 100 问：能搞懂 80% 的请把简历给我](https://github.com/yygmind/blog/issues/43)
- [【半月刊 1】前端高频面试题及答案汇总](https://juejin.im/post/5c6977e46fb9a049fd1063dc)
- [【半月刊 2】前端高频面试题及答案汇总](https://juejin.im/post/5c7bd72ef265da2de80f7f17)
- [【半月刊 3】前端高频面试题及答案汇总](https://juejin.im/post/5c9ac3f66fb9a070e056718f)
- [【半月刊 4】前端高频面试题及答案汇总](https://juejin.im/post/5cb3376bf265da039c0543da)

<br/>



## 联系我

进阶系列文章汇总如下，觉得不错点个 star，欢迎 **加群** 互相学习。

> [https://github.com/yygmind/blog](https://github.com/yygmind/blog)

我是木易杨，公众号「高级前端进阶」作者，跟着我**每周重点攻克一个前端面试重难点**。接下来让我带你走进高级前端的世界，在进阶的路上，共勉！

![image](https://github.com/yygmind/blog/raw/master/images/weixin_re.png)
