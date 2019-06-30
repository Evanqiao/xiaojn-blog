﻿title: C++练习题目（一）
date: 2017-5-09 12:57:36
categories: 我学编程
tags: 
 - C++
toc: false
comments: true
---

说明：
这几个题目要用到的知识点都在培训班老师的讲义上有，可以去查阅相关资料来完成这些题目，写出来的代码要求是自己理解了的，提前编译和调试，确保提交的代码没有语法错误问题。
提交格式： 题号_姓名的拼音.cpp （1_zhangsan.cpp）
以附件形式发到我的邮箱： `yihqiao@126.com` 
<!--more-->

## 题目一
编写一个程序，要求用户以整数方式输入秒数（使用long或long long变量存储），然后以天、小时、分钟和秒的方式显示这段时间。使用符号常量来表示每天有多少个小时、每小时有多少分钟以及每分钟有多少秒。输出样例：
```
Enter the number of seconds: 31600000
31600000 seconds = 365 days, 17 hours, 46 minutes, 40 seconds
Enter the number of seconds: 31
31 seconds = 0 days, 0 hours, 0 minutes, 31 seconds
```
提示：
使用常量定义变量的方法：
```
const int HOURS_PER_DAY = 24
```
或
```
#define HOURS_PER_DAY 24
```

## 题目二
编写一个程序，要求用户输入n (n >= 2)个互不相同的正整数，然后输出这n个整数中的最大的偶数和最小的奇数，如果对应的奇数或偶数不存在则输出-1. 输入有两行，第一行是n，代表输入整数的个数，第二行为n个正整数，输出为两个数。样例：
样例1：
输入：
7
2 7 3 8 4 18 9
输出：
18 3
样例2：
输入：
4
4 8 2 10
输出：
10 -1

## 题目三
定义一个类来表示银行账户，数据成员包括储户姓名、账号（使用字符串表示）和存款。成员函数执行如下操作：
- 创建一个对象并将其初始化；
- 显示储户姓名、账号和存款；
- 存入参数指定的存款；
- 取出参数指定的款项。

请提供类的声明和方法的实现，并编写一个小程序来演示所有的特性。

## 题目四
建立一个长度为n的链表，链表的节点存放的是整数值，删除链表的第m个节点，然后输出链表中每个节点的值。输入有3行，第一行为n，表示要建立的链表的长度，第二行为n个整数，依次表示链表中节点的值，第三行为要删除的节点的编号（链表节点的编号从1开始）。输出为删除一个节点后的链表。样例：
输入：
8
3 12 -2 -10 12 49 7 9
3
输出：
3 12 -10 12 49 7 9


