# Daily-Interview-Question

加入前端「壹题」学习小组，尽在公众号「高级前端进阶」，进阶共勉之！

工作日每天一道大厂前端面试题，一年后再回头，会感谢曾经努力的自己！

<br/>




## 今日面试题

2019-06-13

> 第 89 题：设计并实现 Promise.race()

解析：[第 89 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/140)

<br/>




## 本周汇总

2019-06-12

> 第 88 题：实现 convert 方法，把原始 list 转换成树形结构，要求尽可能降低时间复杂度

以下数据结构中，id 代表部门编号，name 是部门名称，parentId 是父部门编号，为 0 代表一级部门，现在要求实现一个 convert 方法，把原始 list 转换成树形结构，parentId 为多少就挂载在该 id 的属性 children 数组下，结构如下：

```js
// 原始 list 如下
let list =[
    {id:1,name:'部门A',parentId:0},
    {id:2,name:'部门B',parentId:0},
    {id:3,name:'部门C',parentId:1},
    {id:4,name:'部门D',parentId:1},
    {id:5,name:'部门E',parentId:2},
    {id:6,name:'部门F',parentId:3},
    {id:7,name:'部门G',parentId:2},
    {id:8,name:'部门H',parentId:4}
];
const result = convert(list, ...);

// 转换后的结果如下
let result = [
    {
      id: 1,
      name: '部门A',
      parentId: 0,
      children: [
        {
          id: 3,
          name: '部门C',
          parentId: 1,
          children: [
            {
              id: 6,
              name: '部门F',
              parentId: 3
            }, {
              id: 16,
              name: '部门L',
              parentId: 3
            }
          ]
        },
        {
          id: 4,
          name: '部门D',
          parentId: 1,
          children: [
            {
              id: 8,
              name: '部门H',
              parentId: 4
            }
          ]
        }
      ]
    },
  ···
];
```

解析：[第 88 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/139)

<br/>



2019-06-11

> 第 87 题：在输入框中如何判断输入的是一个正确的网址。

解析：[第 87 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/138)

<br/>



2019-06-03

> 第 86 题：周一算法题之「两数之和」

给定一个整数数组和一个目标值，找出数组中和为目标值的两个数。

你可以假设每个输入只对应一种答案，且同样的元素不能被重复利用。

示例：

```js
给定 nums = [2, 7, 11, 15], target = 9

因为 nums[0] + nums[1] = 2 + 7 = 9
所以返回 [0, 1]
```

解析：[第 86 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/136)

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
