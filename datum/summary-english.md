## Front-end interview questions and answers summary


### Question 1: Why do you write a key in a list of a component when writing a React / Vue project? What is the purpose?

Company: Drip, hungry?

Analysis: [Question 1](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/1)

<br/>



### Question 2：`['1', '2', '3'].map(parseInt)` what & why ?

Analysis: [Question 2](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/4)

<br/>



### Question 3：What is anti-shake and throttling? What's the difference? How to achieve?

Company: Digging for money

Analysis: [Question 3](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/5)

<br/>



### Question 4：Introduce the difference between Set, Map, WeakSet and WeakMap?

Analysis: [Question 4](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/6)

<br/>



### Question 5： Introducing depth-first traversal and breadth-first traversal, how to achieve it?
Analysis: [Question 5](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/9)

<br/>



### Question 6：Do you implement a copy function with depth-first thinking and breadth-first thinking?

Analysis: [Question 6](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/10)

<br/>



### Question 7：What is the difference between ES5/ES6 inheritance and writing?

Analysis: [Question 7](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/20)

<br/>



### Question 8：The difference between setTimeout, Promise, Async/Await

Analysis: [Question 8](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/33)

<br/>



### Question 9：How does Async/Await implement asynchronously by means of synchronization?

Company: headline, micro doctor

Analysis: [Question 9](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/156)

<br/>



### Question 10：Asynchronous pen test questions
>Please write the result of the following code

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

Analysis: [Question 10](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/7)

Company: Headline

<br/>



### Question 11：Algorithm handwritten questions

>The following array is known:
>
> var arr = [ [1, 2, 2], [3, 4, 5, 5], [6, 7, 8, 9, [11, 12, [12, 13, [14] ] ] ], 10];
>
> Write a program to flatten the array and repeat some of the data, and finally get an ascending and non-repeating array

Company: Ctrip

Analysis: [Question 11](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/8)

<br/>



### Question 12：The evolution and advantages and disadvantages of the JS asynchronous solution.

Company: Drip, Dig, Micro, Haikang

Analysis: [Question 12](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/11)

<br/>



### Question 13：Is the Promise constructor executed synchronously or asynchronously, then what about the then method?

Company: Micromedical

Analysis: [Question 13](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/19)

<br/>



### Question 14：Valentine's Day Welfare, how to implement a new

Company: Redeem

Analysis: [Question 14](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/12)

<br/>



### Question 15：Briefly explain the multiplexing of http2

Company: Netease

Analysis: [Question 15](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/14)

<br/>



### Question 16：Talk about your understanding of TCP three-way handshake and four wavers

Analysis: [Question 16](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/15)

<br/>



### Question 17：After the A and B machines are connected normally, the B machine suddenly restarts and asks A what state is in TCP at this time.

>If A and B establish a normal connection, they never send data to each other. At this time, B suddenly restarts the machine and asks A what state is TCP at this time? How to eliminate this state in the server program? (Super-level questions, understand)


Analysis: [Question 17](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/21)

<br/>



### Question 18：When is setState in React synchronous and when is it asynchronous?

Company: Micromedical

Analysis: [Question 18](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/17)

<br/>



### Question 19： React setState pen test, what does the following code output?

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
    console.log(this.state.val);    // first log

    this.setState({val: this.state.val + 1});
    console.log(this.state.val);    //  2nd log

    setTimeout(() => {
      this.setState({val: this.state.val + 1});
      console.log(this.state.val);  // 3rd log

      this.setState({val: this.state.val + 1});
      console.log(this.state.val);  // 4th log
    }, 0);
  }

  render() {
    return null;
  }
};
```

Analysis: [Question 19](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/18)

<br/>



### Question 20： Introduce the npm module installation mechanism. Why can I automatically install the corresponding module by entering npm install?

Analysis: [Question 20](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/22)

<br/>



### Question 21：There are three methods for judging arrays. Please introduce the differences and advantages between them.
> Object.prototype.toString.call() , instanceof , and Array.isArray()

Analysis: [Question 21](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/23)

<br/>



### Question 22： Introducing Repaint & Reflow and how to optimize it

Analysis: [Question 22](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/24)

<br/>



### Question 23： Introduce the difference between the observer mode and the subscription-release mode, and what scenarios are applicable to each

Analysis: [Question 23](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/25)

<br/>



### Question 24：Talk about the design ideas of Redux and Vuex

Analysis: [Question 24](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/45)

<br/>



### Question 25：Tell the difference between the browser and the Node event loop

Analysis: [Question 25](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/26)

<br/>

### Question 26：Introducing the development of modularity

It can be considered from the perspectives of IIFE, AMD, CMD, CommonJS, UMD, webpack (require.ensure), ES Module, <script type="module">.


Analysis: [Question 26](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/28)

<br/>



### Question 27：In the global scope, the variables declared with const and let are not on the window. So where exactly? How to get it?

Analysis: [Question 27](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/30)

<br/>



### Question 28：Both the cookie and the token are stored in the header. Why not hijack the token?

Analysis: [Question 28](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/31)

<br/>



### Question 29： Talk about Vue's two-way data binding, how the Model changes the View, and how the View changes the Model.

Analysis: [Question 29](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/34)

<br/>



### Question 30：Combining two arrays into one array

Please put two arrays ['A1', 'A2', 'B1', 'B2', 'C1', 'C2', 'D1', 'D2'] and ['A', 'B', 'C ', 'D'], merged into ['A1', 'A2', 'A', 'B1', 'B2', 'B', 'C1', 'C2', 'C', 'D1', 'D2', 'D'].

Analysis:  [Question 30](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/39)

<br/>



### Question 31：ransform the code below to output 0 - 9, and write out all the solutions you can think of.

```js
for (var i = 0; i< 10; i++){
	setTimeout(() => {
		console.log(i);
    }, 1000)
}
```

Analysis: [Question 31](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/43)

<br/>



### Question 32：Is Virtual DOM really faster than operating a native DOM? Talk about your thoughts.

Analysis: [Question 32](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/47)

<br/>



### Question 33：What does the following code print, and why?

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

Analysis: [Question 33](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/48)

<br/>



### Question 34：Simply modify the code below to print 10 and 20 respectively.

```js
var b = 10;
(function b(){
    b = 20;
    console.log(b); 
})();
```

Analysis: [Question 34](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/51)

<br/>



### Question 35：Browser Cache Read Rules

Can be divided into Service Worker, Memory Cache, Disk Cache and Push Cache, what is the basis of the request from memory cache and from disk cache, and when is the data stored in Memory Cache and Disk Cache?


Analysis: [Question 35](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/53)

<br/>



### Question 36：Implement the flatten function in an iterative manner.

Analysis: [Question 36](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/54)

<br/>



### Question 37：Why can't Vuex's mutation and Redux's reducer do asynchronous operations?

Analysis: [Question 37](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/65)

<br/>



### Question 38：In the following code a Under what circumstances will I print 1?

```js
var a = ?;
if(a == 1 && a == 2 && a == 3){
 	console.log(1);
}
```

Analysis: [Question 38](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/57)

公司：京东

<br/>



### Question 39：Introduce the BFC and its applications.

Analysis: [Question 39](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/59)

<br/>



### Question 40：In Vue, why subcomponents cannot modify the Prop passed by the parent component

If modified, how Vue monitors the modification of the property and gives a warning.

Analysis: [Question 40](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/60)

<br/>



### Question 41：What does the following code output?

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

Analysis: [Question 41题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/61)

<br/>



### Question 42：Implementing a sleep function

For example, sleep(1000) means waiting for 1000 milliseconds, which can be achieved from the perspectives of Promise, Generator, Async/Await, etc.

Analysis: [Question 42](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/63)

<br/>



### Question 43：Sorting arrays [3, 15, 8, 29, 102, 22] using sort(), outputting the result

Analysis: [Question 43](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/66)

<br/>



### Question 44：Introducing the HTTPS handshake process

Analysis: [Question 44](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/70)

<br/>



### Question 45：How does the client verify the validity of the certificate during the HTTPS handshake?

Analysis: [Question 45](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/74)

<br/>



### Question 46：Output the results of the following code execution and explain why

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

Analysis: [Question 46](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/76)

<br/>



### Question 47：Two-way binding and vuex conflict

Analysis: [Question 47](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/81)

<br/>



### Question 48：What is the difference between call and apply, which is better?

Analysis: [Question 48](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/84)

<br/>



### Question 49：Why is it usually a 1x1 pixel transparent gif image when sending a data burying request?

Analysis: [Question 49](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/87)

<br/>



### Question 50： Implementation (5).add(3).minus(2) Function.

> Example: 5 + 3 - 2, the result is 6

Analysis: [Question 50](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/88)

Company: Baidu

<br/>



### Question 51： What is the flaw in Object.defineProperty in Vue's responsive principle?

Why did you use Proxy in Vue 3.0 and discard Object.defineProperty?

Analysis: [Question 51](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/90)

<br/>



### Question 52：How to make a div horizontally centered vertically

Analysis: [Question 52](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/92)

<br/>



### Question 53：Output the execution results of the following code and explain why

```js
var a = {n: 1};
var b = a;
a.x = a = {n: 2};

console.log(a.x) 	
console.log(b.x)
```

Analysis: [Question 53](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/93)

<br/>



### Question 54：How is the bubble sorting achieved, what is the time complexity, and how can it be improved?

Analysis: [Question 54](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/94)

<br/>



### Question 55：A company's sales from January to December exist in an object

As follows: {1:222, 2:123, 5:888}, please process the data as follows: [222, 123, null, null, 888, null, null, null, null, null, null, null].

Analysis: [Question 55](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/96)

<br/>



### Question 56：Requires the design of the LazyMan class to implement the following features.

```js
LazyMan('Tony');
// Hi I am Tony

LazyMan('Tony').sleep(10).eat('lunch');
// Hi I am Tony
// Waited for 10 seconds...
// I am eating lunch

LazyMan('Tony').eat('lunch').sleep(10).eat('dinner');
// Hi I am Tony
// I am eating lunch
// Waited for 10 seconds...
// I am eating diner

LazyMan('Tony').eat('lunch').eat('dinner').sleepFirst(5).sleep(10).eat('junk food');
// Hi I am Tony
// Waited for 5 seconds...
// I am eating lunch
// I am eating dinner
// Waited for 10 seconds...
// I am eating junk food
```

Analysis: [Question 56](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/98)

<br/>



### Question 57：Analysis and comparison opacity: 0, visibility: hidden, display: none Advantages and disadvantages and applicable scenarios.

Analysis: [Question 57](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/100)

<br/>



### Question 58：What is the difference between an arrow function and a normal function? The constructor can generate instances using new , so can the arrow function work? why?

Analysis: [Question 58](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/101)

<br/>



### Question 59：: Given two arrays, write a method to calculate their intersection.

> For example: Given nums1 = [1, 2, 2, 1], nums2 = [2, 2], return [2, 2].

Analysis: [Question 59](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/102)

<br/>



### Question 60：The following code is known. How can I modify the image width to 300px? Note that the code below cannot be modified.

> <img src="1.jpg" style="width:480px!important;">


Analysis: [Question 60](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/105)

<br/>



### Question 61：Introducing how to implement token encryption

Analysis: [Question 61](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/106)

<br/>



### Question 62：Why does redux design reducer as a pure function?

Analysis: [Question 62](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/107)

<br/>



### Question 63：How to design a seamless carousel

Analysis: [Question 63](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/108)

<br/>



### Question 64：Simulating a Promise.finally

Analysis: [Question 64](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/109)

<br/>



### Question 65： `a.b.c.d` and `a['b']['c']['d']`， which one is higher?

Analysis: [Question 65](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/111)

<br/>



### Question 66：What is the implementation of ES6 code conversion to ES5 code?

Analysis: [Question 66](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/112)

<br/>



### Question 67：Array Programming Questions

Randomly generate an array of integer types of length 10, such as `[2, 10, 3, 4, 5, 11, 10, 11, 20]`, arrange them into a new array, requiring the new array form as follows, for example `[[ 2, 3, 4, 5], [10, 11], [20]]`.

Analysis: [Question 67](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/113)

<br/>



### Question 68： How to solve the mobile Retina screen 1px pixel problem

Analysis: [Question 68](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/115)

<br/>



### Question 69： How to reverse the case of a string (uppercase to lowercase and uppercase), for example, 'AbC' becomes 'aBc'.

Analysis: [Question 69](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/116)

<br/>



### Question 70：  Introduce the principle of webpack hot update, how to update the page without refreshing the browser

Analysis: [Question 70](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/118)

<br/>



### Question 71： Implement a string matching algorithm. From the string S of length n, find whether there is a string T. The length of T is m, if there is a return position.

Analysis: [Question 71](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/119)

<br/>



### Question 72： Why the performance of a normal `for` loop is much higher than the performance of `forEach`, please explain why.

![image-20190512225510941](https://ws2.sinaimg.cn/large/006tNc79gy1g2yxbg4ta8j31gh0u048h.jpg)



Analysis: [Question 72](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/121)

<br/>



### Question 73： Introduction to BFC, IFC, GFC and FFC

Analysis: [Question 73](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/122)

<br/>



### Question 74： Simple data binding with JavaScript Proxy

Analysis: [Question 74](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/123)

<br/>



### Question 75：There are 100,000 data in the array. How much difference is the time between the first element and the 100,000th element?

Analysis: [Question 75](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/124)

<br/>



### Question 76：Output the following code to run the result

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

Analysis: [Question 76](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/125)

<br/>



### Question 77：Algorithm title "Rotating array"

> Given an array, move the elements in the array to the right by k positions, where k is a non-negative number.

Example 1：

```js
Enter: [1, 2, 3, 4, 5, 6, 7] 和 k = 3
Output: [5, 6, 7, 1, 2, 3, 4]
Explanation:
Rotate right 1 steps: [7, 1, 2, 3, 4, 5, 6]
Rotate right 2 steps:: [6, 7, 1, 2, 3, 4, 5]
Rotate right 3 steps: [5, 6, 7, 1, 2, 3, 4]
```

Example 2：

```js
Enter: [-1, -100, 3, 99] 和 k = 2
Output: [3, 99, -1, -100]
Explanation:
Rotate right 1 steps: [99, -1, -100, 3]
Rotate right 2 steps: [3, 99, -1, -100]
```

Analysis: [Question 77](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/126)

<br/>



### Question 78： What is the order of execution of Vue's parent and child component lifecycle hooks?

Analysis: [Question 78](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/128)

<br/>



### Question 79：Input Search How to Anti-Shake, How to Handle Chinese Input

Analysis: [Question 79](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/129)

<br/>



### Question 80：Introducing Promise.all usage, principle implementation, and error handling

Analysis: [Question 80](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/130)

<br/>



### Question 81：Print out all symmetrical numbers between 1 and 10000

> For example: 121, 1331, etc.

Analysis: [Question 81](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/131)

<br/>



### Question 82："Mobile Zero" on Monday's algorithm

> Given an array of nums, write a function that moves all 0s to the end of the array while maintaining the relative order of non-zero elements.
>
> Example:
>
> ```
> Input: [0,1,0,3,12]
> Output: [1,3,12,0,0]
> ```
>
> Description:
>
> 1. Must be manipulated on the original array, no extra arrays can be copied.

>
> 1. Minimize the number of operations.

Analysis: [Question 82](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/132)

<br/>



### Question 83：What is the implementation principle of the difference between var, let, and const?

Analysis: [Question 83](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/133)

<br/>



### Question 84：Implement an add function that satisfies the following features.

> ```js
> add(1); 			// 1
> add(1)(2);  	// 3
> add(1)(2)(3)；// 6
> add(1)(2, 3); // 6
> add(1, 2)(3); // 6
> add(1, 2, 3); // 6
> ```

Analysis: [Question 84](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/134)

<br/>



### Question 85：What is the difference between the <Link> tag and the <a> tag in the react-router?

> How to disable the `<a>` tag default event, how to implement the jump after the ban.

Analysis: [Question 85](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/135)

<br/>



### Question 86：: "The sum of two numbers" on Monday's algorithm

Given an array of integers and a target value, find the two numbers in the array that are the target values.

You can assume that each input corresponds to only one answer, and the same elements cannot be reused.

Example:

```js
Given nums = [2, 7, 11, 15], target = 9

Because nums[0] + nums[1] = 2 + 7 = 9
So return [0, 1]
```

Analysis: [Question 86](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/136)

公司：京东、快手

<br/>



### Question 87：How to judge the input is a correct URL in the input box.

Analysis: [Question 87](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/138)

<br/>



### Question 88：实现 convert 方法，把原始 list 转换成树形结构，要求尽可能降低时间复杂度

Implementing the convert method, converting the original list into a tree structure requires as much time complexity as possible
In the following data structure, id represents the department number, name is the department name, parentId is the parent department number, and 0 is the first-level department. Now it is required to implement a convert method, convert the original list into a tree structure, and mount the originalId as the number. Under the attribute children array of the id, the structure is as follows:

```js
// The original list is as follows
let list =[
    {id:1,name:'Department A',parentId:0},
    {id:2,name:'Department B',parentId:0},
    {id:3,name:'Department C',parentId:1},
    {id:4,name:'Department D',parentId:1},
    {id:5,name:'Department E',parentId:2},
    {id:6,name:'Department F',parentId:3},
    {id:7,name:'Department G',parentId:2},
    {id:8,name:'Department H',parentId:4}
];
const result = convert(list, ...);

// The result after conversion is as follows
let result = [
    {
      id: 1,
      name: 'Department A',
      parentId: 0,
      children: [
        {
          id: 3,
          name: 'Department C',
          parentId: 1,
          children: [
            {
              id: 6,
              name: 'Department F',
              parentId: 3
            }, {
              id: 16,
              name: 'Department L',
              parentId: 3
            }
          ]
        },
        {
          id: 4,
          name: 'Department D',
          parentId: 1,
          children: [
            {
              id: 8,
              name: 'Department H',
              parentId: 4
            }
          ]
        }
      ]
    },
  ···
];
```

Analysis: [Question 88](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/139)

<br/>



### Question 89：Designing and implementing Promise.race()

Analysis: [Question 89](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/140)

<br/>



### Question 90：Keyword highlighting for fuzzy search results

<img src="https://ws3.sinaimg.cn/large/006tNc79ly1g43dykaccuj30u01hc49s.jpg" height="800"/>

Analysis: [Question 90](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/141)

<br/>



### Question 91：Introducing HTTPS man-in-the-middle attacks

Analysis: [Question 91](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/142)

<br/>



### Question 92：Known data formats, implement a function fn Find all parent ids in the chain

> ```js
> const value = '112'
> const fn = (value) => {
> ...
> }
> fn(value) // output [1， 11， 112]
> ```



<img src="https://ws1.sinaimg.cn/large/006tNc79gy1g45a04ntttj30k20wen01.jpg" height="800"/>



Analysis: [Question 92](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/143)

<br/>



### Question 93：Given two ordered arrays of size nums1 and nums2 of size m and n. Find the median of these two ordered arrays. The time complexity of the algorithm is required to be O(log(m+n)).

Example 1：

```js
nums1 = [1, 3]
nums2 = [2]
```

The median is 2.0

Example 2:

```js
nums1 = [1, 2]
nums2 = [3, 4]
```

The median is s(2 + 3) / 2 = 2.5

Analysis: [Question 93](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/144)

<br/>



### Question 94：Does vue need to use an event proxy to bind events to each element in v-for? why?

Analysis: [Question 94](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/145)

<br/>



### Question 95：Simulating a deep copy and considering the mutual reference of objects and the copy of Symbol

Analysis: [Question 95](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/148)

<br/>



### Question 96：Introducing common scenarios and methods for front-end encryption

Analysis: [Question 96](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/150)

<br/>



### Question 97： How does the diff time complexity of React and Vue be optimized from O(n^3) to O(n), then how are O(n^3) and O(n) calculated?

Analysis: [Question 97](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/151)

<br/>



### Question 98：Write the print result of the following code

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

Company: Jingdong

Analysis: [Question 98](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/152)

<br/>



### Question 99：Programming Algorithm Questions

> Write a function in JavaScript, type int, and return the string after the integer is reversed. For example, enter integer 1234 and return the string "4321". Requires that you must use a recursive function call. You cannot use a global variable. The input function must have only one argument passed in, and must return a string.

Company: bilibili

Analysis: [Question 99](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/153)

<br/>
