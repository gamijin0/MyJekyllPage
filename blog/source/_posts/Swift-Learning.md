---
title: Swift-Learning
date: 2016-09-27 00:28:17
tags:
---

参加了2016年的MDCC，发现IOS专场几乎都在讲 __Swift__ ，看到Swift融合了许多语言的特点，优雅但灵活，简洁而功能强大，有由一门IOS开发专用的语言向通用高级语言转变的趋势，神往不已，决定开始逐步学习

这篇文章就用于记录我学习Swift过程中的收获，方便以后回顾与查阅



_ _ _


#基础部分 - The Basics

- 你可以在定义元组的时候给单个元素命名:
`let http200Status = (statusCode: 200, description: "OK")`
给元组中的元素命名后,你可以通过名字来获取这些元素的值:
`print("The status code is \(http200Status.statusCode)")
// 输出 "The status code is 200"`

- 可选绑定好奇怪，先跳过


