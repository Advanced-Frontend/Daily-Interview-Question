# Daily-Interview-Question

加入「前端面试互助群」学习小组，搜索公众号「高级前端进阶」，关注即可加入！

工作日每天一道大厂前端面试题，一年后再回头，会感谢曾经努力的自己！

[线上版本阅读更流畅，点击阅读](https://muyiy.cn/question/)

<br/>



[推荐一个不错的前端算法系列，点击查看](https://github.com/sisterAn/JavaScript-Algorithms)

<br/>



推荐扫码使用微信小程序，除了本项目之外，还囊括了算法题、选择题等多种类型题目和详细解析

记住我们的 Slogan：上下班路上刷一点，半年突击进大厂



<img src="http://resource.muyiy.cn/image/20200106214930.jpg" height="250px">

<br/>




## 今日面试题

第 157 题：浏览器缓存 ETag 里的值是怎么生成的



解析：[第 157 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/383)

<br/>



## 最近汇总

第 156 题：求最终 left、right 的宽度

```js
<div class="container">
    <div class="left"></div>
    <div class="right"></div>
</div>

<style>
  * {
    padding: 0;
    margin: 0;
  }
  .container {
    width: 600px;
    height: 300px;
    display: flex;
  }
  .left {
    flex: 1 2 300px;
    background: red;
  }
  .right {
    flex: 2 1 200px;
    background: blue;
  }
</style>
```

注：此题和 155 题 left、right 样式有些不同



解析：[第 156 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/382)

<br/>



第 155 题：求最终 left、right 的宽度

```js
<div class="container">
    <div class="left"></div>
    <div class="right"></div>
</div>

<style>
  * {
    padding: 0;
    margin: 0;
  }
  .container {
    width: 600px;
    height: 300px;
    display: flex;
  }
  .left {
    flex: 1 2 500px;
    background: red;
  }
  .right {
    flex: 2 1 400px;
    background: blue;
  }
</style>
```



解析：[第 155 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/381)

<br/>



第 154 题：弹性盒子中 flex: 0 1 auto 表示什么意思

解析：[第 154 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/380)

<br/>



第 153 题：实现一个批量请求函数 multiRequest(urls, maxNum)

 要求如下：

1. 要求最大并发数 maxNum

2. 每当有一个请求返回，就留下一个空位，可以增加新的请求
3. 所有请求完成后，结果按照 urls 里面的顺序依次打出



解析：[第 153 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/378)

<br/>



2019-12-31

> 第 152 题：实现一个 normalize 函数，能将输入的特定的字符串转化为特定的结构化数据



解析：[第 152 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/331)

<br/>




2019-11-25

> 第 151 题：用最简洁代码实现 indexOf 方法
>



解析：[第 151 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/321)

<br/>


2019-11-21

> 第 150 题：二分查找如何定位左边界和右边界
>
> 不使用JS数组API，查找有序数列最先出现的位置和最后出现的位置



解析：[第 150 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/320)

<br/>



2019-11-12

> 第 149 题：babel 怎么把字符串解析成 AST，是怎么进行词法/语法分析的？

解析：[第 149 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/315)

<br/>



2019-11-01

> 第 148 题： webpack 中 loader 和 plugin 的区别是什么（平安）



解析：[第 148 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/308)

<br/>



2019-10-31

> 第 147 题：v-if、v-show、v-html 的原理是什么，它是如何封装的？



解析：[第 147 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/307)

<br/>



2019-10-29

> 第 146 题：Vue 中的 computed 和 watch 的区别在哪里（虾皮）



解析：[第 146 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/304)

<br/>



2019-10-24

> 第 145 题：前端项目如何找出性能瓶颈（阿里）



解析：[第 145 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/300)

<br/>



2019-10-22

> 第 144 题：手写二进制转 Base64（阿里）



解析：[第 144 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/299)

<br/>



2019-10-21

> 第 143 题：将 '10000000000' 形式的字符串，以每 3 位进行分隔展示 '10.000.000.000'



解析：[第 143 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/296)

<br/>



2019-10-17

> 第 142 题：（算法题）求多个数组之间的交集（阿里）



解析：[第 142 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/293)

<br/>



2019-10-15

> 第 141 题：Vue 中的 computed 是如何实现的（腾讯、平安）



解析：[第 141 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/291)

<br/>



2019-10-14

> 第 140 题：为什么 HTTP1.1 不能实现多路复用（腾讯）



解析：[第 140 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/290)

<br/>



2019-09-17

> 第 139 题：谈一谈 nextTick 的原理



解析：[第 139 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/281)

<br/>



2019-09-11

> 第 138 题：反转链表，每 k 个节点反转一次，不足 k 就保持原有顺序（哔哩哔哩）



解析：[第 138 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/278)

<br/>



2019-09-04

> 第 137 题：如何在 H5 和小程序项目中计算白屏时间和首屏时间，说说你的思路



解析：[第 137 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/272)

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

![image](http://resource.muyiy.cn/image/20200123162151.png)
