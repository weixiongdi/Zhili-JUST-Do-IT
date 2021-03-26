# Here it is

=====================================

- megabits and megabiytes;传输用mbps，存储用MB

Anyway, here we stand today, with the delineation clear: Bandwidth is measured in bits, storage capacity in bytes

====================

## three-sigma rule

```
mu  = mean of the data
std = standard deviation of the data
IF abs(x-mu) > 3*std  THEN  x is outlier
```

======================

- general availability (GA)

In the software release life cycle, general availability (GA) refers to the marketing phase when all commercialization activities pertaining to the software product have been completed and it is available for purchase.

===========================

## CS-抽取转化装载(Extract， Transform and Load)；数据抽取

**ETL是将业务系统的数据经过抽取、清洗转换之后加载到数据仓库的过程，目的是将企业中的分散、零乱、标准不统一的数据整合到一起，为企业的决策提供分析依据。** ETL是BI项目重要的一个环节。 通常情况下，在BI项目中ETL会花掉整个项目至少1/3的时间,ETL设计的好坏直接关接到BI项目的成败。    

　　ETL的设计分三部分：数据抽取、数据的清洗转换、数据的加载。在设计ETL的时候我们也是从这三部分出发。数据的抽取是从各个不同的数据源抽取到ODS(Operational Data Store，操作型数据存储)中——这个过程也可以做一些数据的清洗和转换)，在抽取的过程中需要挑选不同的抽取方法，尽可能的提高ETL的运行效率。ETL三个部分中，花费时间最长的是“T”(Transform，清洗、转换)的部分，一般情况下这部分工作量是整个ETL的2/3。数据的加载一般在数据清洗完了之后直接写入DW(Data Warehousing，数据仓库)中去

================================

- what is a PBI in software dev?

  a PBI (Product Backlog Item).

============================

## 云原生应用的三大特征：容器化封装、动态管理、面向微服务

==========================

conda command

root environment



additional environment /env

\--------------------------------------



conda env list



~~source activate myenv~~

conda activate myenv



conda list



conda install seaborn=版本号



conda update matplotlib



conda update

===========================

3-23-2021

my_wellname=cursor.execute("SELECT DISTINCT \"Well Name\" FROM WELL_PRODUCTION ")

转义，带有space的column name

=======================

work question

![png](work_q1.png)

=========

## [How to open and convert sqlite database to pandas dataframe]

```
import sqlite3
import pandas as pd
# Create your connection.
cnx = sqlite3.connect('file.db')

df = pd.read_sql_query("SELECT * FROM table_name", cnx)
```

===========================================

## 要做网站，你需要学一种web编程语言

要做网站，你需要学一种web编程语言，显然C/C++没用，再说你的学校里面学的那点皮毛更是连掌握C/C++也算不上。
你可以学习Jsp、asp.net、PHP、Ruby On Rails、Node.JS、Python等语言中的任何一种。
如果你用asp.net，你需要的开发工具是Visual Studio。如果是Jsp，包括Struts等框架，你需要MyEclipse。如果你开发PHP程序，可以用 ZendStudio。
除了服务器编程语言，你还需要一种数据库，比如MySQL、Oracle、SQL Server等。
另外既然是网站，就需要和html css js等前端技术打交道，你要有些美工的技巧，懂得css布局，jquery和ajax等，最好学一种简单的前端框架，比如angular.js或者easy ui。
也许说了这么多，你已经有些迷惑了。其实以上这些你完全不会都没事，最重要的技能是：
你要善于使用Google，无论是你打算学习任何东西，或者胡乱抄袭一个现成的，或者雇佣一个程序员，它都可以帮助你。

=======

## 【高并发】学好并发编程，关键是要理解这三个核心问题

[click here](../[高并发]学好并发编程，关键是要理解这三个核心问题.html)

====================

## 浅谈几种常用负载均衡架构

软件负载解决的两个核心问题是：选谁、转发，其中***的是 LVS(Linux Virtual Server)。

 然而，我们的网站对外提供的访问入口都是一个的，比如www.taobao.com。那么当用户在浏览器输入 www.taobao.com 的时候如何将用户的请求分发到集群中不同的机器上呢，这就是负载均衡在做的事情。

[detail](https://developer.51cto.com/art/201904/595761.htm)

-============================================

## Cache 是什么

今天，来给大家介绍一个计算机系统里的常见概念——cache。**学院派喜欢译作高速缓冲存储器，民间通常简称缓存。**在介绍 cache 之前有必要首先明确一下它的英文读音：它的正确念法和 cash 完全相同，不是“擦车”...…

**到底什么叫做 cache 呢？**说白了，就是用一块又小又快的存储设备来作为更大更慢的存储设备的缓冲区，从而提高数据访问速度。**Memory hierarchy** 的核心思想就是金字塔的每一层都是下一层的缓存。什么意思呢？咱们从下往上举例。

[detail](https://zhuanlan.zhihu.com/p/71956210)

======================

## what is hook

一个定义不明的术语而已
Hook：在已经可以正常运作的程序中额外添加流程控制
可以实现，但不限于获取所hook流程中特定时刻的各种数据，修改数据，修改程序流程
比如，在一家公司，所有采购事宜只需财务和专员协调沟通即可完成。现在公司决定下个hook, 采购事宜需总经理签字批准才可继续执行。至于总经理怎么hook操作：是随便签字，还是搞潜规则，或者有自己的想法和安排来进行新的采购事项，这就属于hook的具体实现
实际上不理解hook，也无所谓。毕竟不一定用得到，用到的时候自然有自己的理解

作者：Saterblues
[链接](https://www.zhihu.com/question/20610442/answer/128149486)
来源：知乎

=====================================

## 【Spark你妈喊你回家吃饭-01】 Spark是什么鬼？

基于对MR的理解，回忆一下分布式计算碰到的几个典型问题

（1）分布式情况下，资源如何分配，谁负责分配资源，资源都在哪里 ？

（2）分布式情况下，任务如何分配，任务哪里来，谁分配任务，分给谁？

（3）分布式情况下，任务执行的时候，如何跟踪任务进度，谁统一汇总任务执行情况，下面的人如何回报任务？

（4）分布式情况下，任务执行的时候，如何跟踪资源动态使用情况，谁负责统计所有资源情况，各个节点怎么回报资源给统计的人？

其实分布式计算框架，就这点破事，折腾不出什么新鲜花样

[click](https://blog.csdn.net/sjh752422969/article/details/54999497)

## .  表示用户所处的当前目录

　 .  表示用户所处的当前目录
  .. 表示上级目录
　~ 表示当前用户自己的home目录
　~USER 表示用户名为USER的家目录，这里的USER是在/etc/passwd中存在的用户名

  使用“../”来表示上一级目录，“../../”表示上上级的目录，以此类推。