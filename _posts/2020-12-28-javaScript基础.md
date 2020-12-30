---
layout: page
title:  "javaScript基础&语法"
subtitle: "菜鸟上路"
date:   2020-012-28 21:21:21 +0530
categories: ["语言语法与常用模块"]
---

# JavaScript 基础

> js是什么？

- 解释型或即时编译型的编程语言(代码不进行预编译)
	- 解释型语言：
		- 机器运行时逐行运行，每运行一次执行一次。
		- 如Java、JavaScript、VBScript、Perl、Python、Ruby、MATLAB。
	- 编译型语言：
		- 编译型语言写的程序执行之前，需要一个专门的编译过程，把程序编译成为机器语言的文件。
		- 如C++，JAVA
- 脚本语言

> js组成
> 语境不一样使用不一样，浏览器中称为js脚本，控制页面。后端成为node.js

## ECMAScript 

- JavaScript的核心
	- 含义：定义了JavaScript的语法规范。
	- JavaScript的核心，描述了语言的基本语法和数据类型，ECMAScript是一套标准，定义了一种语言的标准与具体实现无关。

## BOM 浏览器对象模型

- 含义：

## DOM 文档对象模型

- 含义：window中的对象，来描述文档对象的模型；DOM可以把HTML看做是文档树，通过DOM提供的API可以对树上的节点进行操作

- 操作DOM
	- 对DOM节点的增删改查。
		- DOM节点
			- 1属性节点 html中的标签的属性
			- 2元素节点 HTML中的标签
			- 3文本节点 html文本


### js基础语法

- 写在行内

```html
<input type="button" value="按钮" onclick="alert('Hello World')" />
```

- 写在标签里

```html
<head><script>alert('Hello World!');</script></head>

```

- 外部文件引入

```html
<script src="main.js"></script>

```

#### js中的数组

- JavaScript中没有多维数组概念
	-JavaScript 变量可以是对象。数组是特殊类型的对象。可以在相同数组中存放不同类型的变量。
	- 可以在数组保存对象。您可以在数组中保存函数。你甚至可以在数组中保存数组：
		- myArray[0] = Date.now;
		- myArray[1] = myFunction;
		- myArray[2] = myCars;

### JS逻辑

- 使用Boolean()函数来确定表达式或变量是否为真；
- 所有不具有"真实"值的即为False
	- 如：0，-0，""(空值)，undefined，null，Nan
	- 比较两个 JavaScript 对象将始终返回 false。

```js
var x = 0; //-0，undefined，null，Nan
Blllean(x);
```

> 注意：不要创建布尔对象，会拖慢执行速度，（但是可以使用new定义对象。


### AJAx

> 无刷新更新页面

- Ajax 工作原理
	- 网页中发生一个事件（页面加载、按钮点击）
    - 由 JavaScript 创建 XMLHttpRequest 对象
    - XMLHttpRequest 对象向 web 服务器发送请求
    - 服务器处理该请求
    - 服务器将响应发送回网页
    - 由 JavaScript 读取响应
    - 由 JavaScript 执行正确的动作（比如更新页面）
