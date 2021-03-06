---
layout: '[default_layout]'   
title: Python总结           
date: 2018-01-19 17:47:41  
updated: 
permalink: 
render_drafts: true
copyright: true
password: 
comments: true
toc: true                  
tags:                        
- Python

categories:                  
- others

---
# 1、为什么使用 Python 进行数据分析？

Python 作为一门动态编程语言，以简单易用的特性变得越来越流行，同时 Python 具有丰富活跃的生态环境，包含各种任务用途的软件。比如 Web 开发框架 Django、Flask，数据库访问处理 SQLAlchemy，爬虫框架 Scrapy, 数据分析 NumPy, Pandas 等软件包都基于 Python 开发。有了这些高质量软件包的支持，我们就可以完成各种各样的任务需求。
<!--more-->
对于数据分析来说，也同样有各种各样的 Python 软件包，如：

IPython - 易用的 Python 交互式终端；
NumPy - 科学计算软件包，强大的矩阵处理能力；
Pandas - 基于 NumPy, 更加强大方便易用的矩阵运算功能；
Scikit-Learn - 包含了各种机器学习算法；
Keras - 包含了各种神经网络算法，可以满足各种数据分类，聚类需求；
Matplotlib - 强大的绘图软件包，可以绘制各种各样的图表；
除了以上软件包，还有其他大量用于数据分析的 Python 软件包，如果在数据分析过程中遇到一些任务需求，不妨搜索下有没有方便的软件包可以使用。

同时 Python 也是一门胶水语言，可以快速绑定到其他语言实现的数据分析框架上，这样由于 Python 动态语言的特性就可以快速实现相关模型。比如 TensorFlow 核心使用 C++ 开发，但是同时提供了 Python 绑定，这样就可以很方便的使用 Python 代码快速学习 TensorFlow 了。同理，当使用 Python 实现数据分析模型以后，如果发现模型中有些部分需要更高性能的编程语言进行实现时，也可以很方便的绑定替换。


# 2、基础语法

Python 本身非常简单, 主要语法如下：

- 变量可以被赋予任意值；
- 注释以字符 # 开头，赋值通过等号 = 实现；
- 双等号 == 用于相等判断, != 用于不等判断， is 用于判断变量是否为 None 值；
- and 和 or 用于逻辑和，逻辑与运算；
- += 和 -= 用于增加/减少运算，没有自增和自减；
- True 和 False 代表真值和假值；
- 没有强制的语句终止字符，代码块通过缩进表示。缩进表示一个代码块的开始，逆缩进则表示一个代码块的结束；
- 声明以冒号 : 字符结束，并且开启一个缩进级别；
- 可以在一行上使用多个变量；

# 3、数据类型

Python 语言内置了数字，字符串，None 值，元组，列表，字典，集合几种数据类型下面我们一一讲解。

数字可以是整数或者浮点数，注意python没有double类型；
字符串是不可变的；
None 值没有意义，可用于代表某些初始状态；
元组通过 () 圆括号进行创建，不可改变；
列表通过 [] 创建，可以插入或者删除其中的值；
字典通过 {key: value} 形式创建，代表键值对，也就是哈希表，键和值的类型没有要求；
集合通过 {1, 2} 形式创建

# 4、python2.x和python3.x的比较









