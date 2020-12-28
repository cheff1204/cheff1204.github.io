---
layout: page
title:  "javaScript基础&语法"
subtitle: "菜鸟上路"
date:   2020-012-28 21:21:21 +0530
categories: ["语言语法与常用模块"]
---

#JavaScript 基础

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