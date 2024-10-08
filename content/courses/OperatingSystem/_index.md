---
# Page title
title: 《计算机操作系统》课程

# Title for the menu link if you wish to use a shorter link title, otherwise remove this option.
linktitle: 课程介绍

# Page summary for search engines.
summary: 操作系统是计算机系统的指挥中心，它既是系统中各种资源的管理者，又是服务的提供者。操作系统在计算机系统中所处的地位和作用决定本课程在计算机学科课程中特殊重要的核心位置。

# Date page published
date: 2018-09-09

authors: ["admin"]
author_notes: ["contributor"]

# Book page type (do not modify).
type: book

# Position of this page in the menu. Remove this option to sort alphabetically.
weight: 1
---

## 一、课程介绍 

《操作系统》课程是计算机考研408指定课程。操作系统是计算机系统的指挥中心，它既是系统中各种资源的管理者，又是服务的提供者。操作系统在计算机系统中所处的地位和作用决定本课程在计算机学科课程中特殊重要的核心位置。本课程主要讲授操作系统的基本概念、基本原理、设计方法和实现技术，包括：操作系统概述、进程线程与作业、中断与处理机调度、互斥同步、死锁、存储管理、输入输出系统、文件系统等内容。

## 二、课程资源

- updating：[2024年操作系统课件PPT](https://pan.baidu.com/s/1NQcS8-zCk3bhDMN4lgdDiw?pwd=p21f)，[配套练习题库](https://www.doc88.com/p-73247196945596.html)
- 教材：计算机操作系统（慕课版），汤小丹 王红玲 姜华 汤子瀛编著，人民邮电出版社
- 本书官方视频资源：[1.官方全书慕课视频(新书的封底有刮刮卡激活码)](https://www.rymooc.com/Course/show/714)，[2.B站官方教学视频王红玲主讲](https://www.bilibili.com/video/BV17h411B7yW/)
- MIT神级OS课程，强烈推荐学习：[operating systems 6.828](https://pdos.csail.mit.edu/6.828/2023/index.html) 
- 上海交通大学陈海波老师，华为操作系统首席科学家，专注操作系统研究，[IPADS实验室](https://ipads.se.sjtu.edu.cn/start)，教材与实验：[操作系统原理与实现](https://ipads.se.sjtu.edu.cn/ospi/)，建议自学完成实验部分
- [Linux命令大全](http://www.runoob.com/linux/linux-command-manual.html)，著名的操作系统专家[Andrew S. Tanenbaum的个人网站](http://www.cs.vu.nl/~ast/)

## 三、课程考核方式

- 课堂表现和作业：20%

- 期中测试：20%

- 期末考试：60%

## 四、教学计划
- 上课信息：
  - 1-17周，周三3-4节，10:20-11:50，文济楼208
  - 1-16周双周，周四3-4节，10:20-11:50，文济楼109

[2023年秋授课信息]({{< relref "./history/2024OS" >}})，[2023年秋课件PPT](https://pan.baidu.com/s/1qzxmW44K8OcAsm8T1Fjbrg?pwd=cvix)

[2024年秋课件PPT](https://pan.baidu.com/s/1NQcS8-zCk3bhDMN4lgdDiw?pwd=p21f), 授课形式：翻转课堂，2024年秋授课信息如下：

| Lesson Number |                             章节                             |                             内容                             |            备注             |
| :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------------------------: |
|    1    | 第1章 操作系统引论1.1-1.7节 <br />[第1章思维导图](/courses/OperatingSystem/mindmap/chapter1.png) | 操作系统的目标和作用、操作系统的发展过程、操作系统的基本特性、操作系统的主要功能、操作系统的结构设计 |        第1章作业，课后1，2，25                     |
|    2    | 第2章 进程描述与控制 2.1-2.3，2.4-2.6（2次课）<br />[第2章思维导图](/courses/OperatingSystem/mindmap/chapter2.png) |      前趋图、进程的描述、控制、通信、线程、讲解作业 <br /> <font color="blue">提前预习内容：</font>程序并发执行P5-7、进程控制P24-28、线程的实现P45-51               |   第2章作业，1，2，21   |
|    3    | 第3章 处理机调度与死锁3.1-3.2<br />[第3章思维导图](/courses/OperatingSystem/mindmap/chapter3.png) |          处理机调度概述，调度算法<br /> <font color="blue">提前预习内容：</font>评价指标P11、优先级调度算法P21-24， 高响应比优先调度P25         |       |
|    4    | 第3章 处理机调度与死锁3.3-3.6，3.7-3.8（2次课）<br />[第3章思维导图](/courses/OperatingSystem/mindmap/chapter3.png) |          实时调度、死锁、预防死锁、避免死锁、死锁的检测与解除 <br /> <font color="blue">提前预习内容：</font>抢占式EDF例子P41、最低松弛度优先LLF算法P42-44， 产生死锁的必要条件及处理方法P55-57、死锁预防方法P59-60；银行家算法P66-69、银行家算法例子P70-72、例子续P73-74、死锁检测算法P86-87       |  第3章作业，课后1，2，20，22     |
|    5    | gap |                 |      |
|    6    | 第4章 进程同步4.1-4.4；4.5-4.7（2次课） |  进程同步的基本概念，软件同步机制，硬件同步机制，信号量机制；管程机制、经典进程的同步问题、Linux进程同步机制               |  <br /> <font color="blue">提前预习内容：</font>机器语言P9-10，整型信号量P22，记录型信号量P23-24，利用信号量实现前趋关系P30；生产者消费者解决方法P49-50，哲学家进餐记录型信号量P56，读者写着问题P63-64，信号量操作讨论P71    |

