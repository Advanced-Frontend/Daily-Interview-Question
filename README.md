# Daily-Interview-Question

加入前端「壹题」学习小组，尽在公众号「高级前端进阶」，进阶共勉之！

工作日每天一道大厂前端面试题，一年后再回头，会感谢曾经努力的自己！

[线上版本阅读更流畅，点击阅读](https://muyiy.cn/question/)

<br/>




## 今日面试题
2019-09-02

> 第 135 题：算法题（盛大）
>
> 在一个字符串数组中有红、黄、蓝三种颜色的球，且个数不相等、顺序不一致，请为该数组排序。使得排序后数组中球的顺序为:黄、红、蓝。
>
> 例如：红蓝蓝黄红黄蓝红红黄红，排序后为：黄黄黄红红红红红蓝蓝蓝。



解析：[第 135 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/266)

<br/>




## 本周汇总
2019-08-30

> 第 134 题：求两个日期中间的有效日期
>
> 如 2015-2-8 到 2015-3-3，返回【2015-2-8 2015-2-9...】



解析：[第 134 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/264)

<br/>



2019-08-29

> 第 133 题：用 setTimeout 实现 setInterval，阐述实现的效果与 setInterval 的差异



解析：[第 133 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/259)

<br/>



2019-08-27

> 第 132 题：实现一个 Dialog 类，Dialog可以创建 dialog 对话框，对话框支持可拖拽（腾讯）



解析：[第 132 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/257)

<br/>



2019-08-26

> 第 131 题：接口如何防刷



解析：[第 131 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/254)

<br/>



2019-08-23

> 第 130 题：输出以下代码执行结果，大致时间就好（不同于上题）
>
> ```js
> function wait() {
>   return new Promise(resolve =>
>     setTimeout(resolve, 10 * 1000)
>   )
> }
> 
> async function main() {
>   console.time();
>   await wait();
>   await wait();
>   await wait();
>   console.timeEnd();
> }
> main();
> ```



解析：[第 130 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/253)

<br/>



2019-08-22

> 第 129 题：输出以下代码执行结果
>
> ```js
> function wait() {
>   return new Promise(resolve =>
>     setTimeout(resolve, 10 * 1000)
>   )
> }
> 
> async function main() {
>   console.time();
>   const x = wait();
>   const y = wait();
>   const z = wait();
>   await x;
>   await y;
>   await z;
>   console.timeEnd();
> }
> main();
> ```



解析：[第 129 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/251)

<br/>



2019-08-20

> 第 128 题：Http 状态码 301 和 302 的应用场景分别是什么



解析：[第 128 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/249)

<br/>



2019-08-19

> 第 127 题：如何用 css 或 js 实现多行文本溢出省略效果，考虑兼容性



解析：[第 127 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/246)



2019-08-15

> 第 126 题：扑克牌问题
>
> 有一堆扑克牌，将牌堆第一张放到桌子上，再将接下来的牌堆的第一张放到牌底，如此往复；
>
> 最后桌子上的牌顺序为： (牌底) 1,2,3,4,5,6,7,8,9,10,11,12,13 (牌顶)；
>
> 问：原来那堆牌的顺序，用函数实现。



解析：[第 126 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/245)

<br/>



2019-08-13

> 第 125 题：如何将`[{id: 1}, {id: 2, pId: 1}, ...]` 的重复数组（有重复数据）转成树形结构的数组 `[{id: 1, child: [{id: 2, pId: 1}]}, ...]` （需要去重）



解析：[第 125 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/243)

<br/>



2019-08-12

> 第 124 题：永久性重定向（301）和临时性重定向（302）对 SEO 有什么影响



解析：[第 124 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/241)

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
