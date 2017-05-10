# Java Concurrency Recipes

# Authors

| Name | Weibo Id | Blog | Mail |
|:-----------|:-------------|:-------------|:-----------|
| 李豪 |[@计算所的小鼠标](http://weibo.com/icttinymouse) | [CarpenterLee](http://www.cnblogs.com/CarpenterLee/) | hooleeucas@163.com |

# Introduction

“能够驾驭多核程序的，都是稀缺人才。” ——孔子

摩尔定律失效促使人们寻找多核/众核的解决方案，当下手机平板都已四核八核，更不用说动则多块CPU数十个核的服务器了。多核使得并发/并行程序大行其道，但是如何编写正确、有效的并行程序并非易事。跟单核程序不同，多核程序牵涉到合理的任务划分，以及线程之间的同步、竞争等问题。糟糕的多核程序效率可能还不如单核程序，更可怕的是还可能出现死锁、状态错误等严重问题。

为简化并发编程，Java语言为我们提供很多工具类。本系列文章对Java并发相关的常见工具类给出介绍，让读者快速对Java并发编程建立一个简洁而深入的认识。为了不把读者吓走，本系列文章从将从现实中常遇到的问题出发，尽可能的围绕实际问题进行介绍。如果想全面了解Java并发编程，建议阅读相关书籍。

# Contents

具体内容安排如下：

1. [Atomics](./markdown/1-Atomics.md)，介绍常见原子变量
2. [Concurrent Collections(I)](/markdown/2-Concurrent%20Collections(I).md)，介绍并发容器
线程池
显示锁
...



