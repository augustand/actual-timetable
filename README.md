
# Reboot实战班课程表

## 学员可完成项目

###实战项目之一（精简版CMDB）

* html+css+js多种前端技术结合
* ajax异步请求操作
* 常见数据库设计原则、CMDB表结构实战、mysql实操
* 独立完成此项目，会对整体的web(LAMP)架构有很好的了解


###实战项目之二（Nginx日志统计分析与多维可视化）
* 用Python处理Nginx日志文件，进行多维度数据统计分析
* 根据ip、访问地址和访问状态等数据统计，统计结果保存数据库
* Highcharts等流行前端技术多维度将分析结果可视化展示



###实战项目之三（[快速构建实用监控系统](http://blog.51reboot.com/python36-falcon-mon-video/)）
* Python读取机器的实时使用数据，通过http请求将数据入库
* 设计数据入库的api，可以收集不同机器的数据
* 前端将内存数据读出，可视化展示折线图
* 独立完成此项目，对Python常用的time等模块有很好的掌握


----

##（一）Python基础
+ Python的特点
+ 第一个Python程序
+ 数字、字符串
+ 字符串格式化
+ 变量及变量赋值
+ 注释
+ Python的四则运算、运算符（in、not in、is、and、or）
+ 获取用户输入（input、raw_input）
+ 字符串格式化
+ 流程控制（if..else、for、while True、break、continue、pass）
+ 作业1：让用户输入数字，累加
+ 作业2：存10000块钱，年利率是3.25，多少年之后，存款能翻倍
+ 作业3：求一个序列中，最大的两个数



##（二）Python列表
              
* 列表（分片、步长、方法）
* 常用内置函数（max、min、range）
* list内置方法
* 冒泡排序的实现
* 数组去重的实现
* 练习1: 实现简单的队列和栈
* 作业1：两个数组求交集
* 作业2：插入排序算法的实现



##（三）Python字典 字符串

                
 * 字符串方法（find、join、split、strip、format、replace、
index、count）

 * 字典常用方法、字典格式化字符串
 * del语句
 * 常用内置函数
 * 练习1:list排序
 * 练习2:dict按照key排序
 * 基础复习

##（四）Python文本操作
   
* 文件读写操作（open、read、readline、readlines、write、close）
* 异常处理（try..except、else、raise）
* 项目1：统计一篇文章中有多少个单词及每个单子出现次数
* 实现目标（可以简单清晰的统计出各个单词的信息）
* 项目目的（对字符串、字典语法练习和文件的操作练习）
* 作业：编写Nginx日志分析程序
* 实现目标（对Nginx日志请求类型、返回值、url、ip各个维度统
计）
* 项目目的（日常工作中遇到日志分析应该怎么样全方位的统计）


##（五）Python函数编程

* 列表推导式、嵌套的列表推导式
* 函数详解def，return（默认参数值、函数调用、函数返回值、全局变量、局部变量）
* 深入函数定义（可变参数列表、参数列表的分拆、Lambda 形式）
* 作用域
* Lambda匿名函数
* Sorted排序函数
* 练习1：实现一个函数，求传入所有参数之和
* 作业：写一个计算器可以实现加减乘除

##（六）Web Flask框架


* Python的模块
* 简单的html（table、表单）学习
* 简单web框架Flask介绍
* 前端jquery简介
* 作业1：写一个用户注册的html表单（数据存在文件里，支持增删查）
* 作业2：第五天计算器的题，支持优先级 

##（七）数据库基础

* 简单的sql语句学习（增添改查）、数据库建表
* Python执行sql，控制数据库
* 项目1：用Flask实现数据库的增添改查
* 实现目标（可以简单的实现web增添改查功能）
* 项目目的（对Flask、MySQLdb的学习）  
* 将第六天的作业，存储改为mysql

##（八）前端基础


* 前端基础
    - css
    - javascript基础
* 前端学习之jquery
* Ajax调用Python接口
* Bootstrap框架学习
* 作业：对第7天的Flask增删改查提供前端页面，通过web页面对数据库增删改查
* 要求：异步加载数据，不刷新页面

##（九）实战项目之cmdb

* Flask用户登入
* 项目CMDB系统
* CMDB系统基础信息分析
* CMDB系统资产表设计
* CMDB系统数据展现
* CMDB系统数据更新
* jquery插件的使用
    - 常用插件
    - 网上的插件如何使用
* 目的：完整的前端+后端+数据库的项目
* 项目扩展介绍


##（十）Python抽象

+ 类的基本概念与详解
+ 变量与方法
+ 作用域与命名空间
+ 继承
+ 类的抽象、封装、方法与实例化实践


##（十一）Python常用模块

* 常用内置模块（sys、os、commands）
* 脚本参数处理（sys.argv）
* 时间的控制(time)
* 定时获取机器的内存占用等信息，存储数据库
* 单机上线流程介绍




## （十二）实战项目之二（[Python写一个简单的监控系统](http://blog.51reboot.com/python36-falcon-mon-video/)）

* Python读取机器的实时使用数据，通过http请求将数据入库
* 设计数据入库的api，可以收集不同机器的数据
* 前端将内存数据读出，可视化展示折线图
* 独立完成此项目，对Python常用的time等模块有很好的掌握




##（十三）实战项目之三（Nginx访问日志入库可视化）

* 将Nginx日志处理结果入库
* Flask模板系统，多页面继承
* 前端可视化库的使用
* 常见可视化图形
    - 饼图
    - 折线图等等
* 存储的内存数据可视化
* 项目扩展介绍
 
## （赠送）Flask扩展
* Flask大型应用的代码组织结构
    * 用包来组织代码介绍。 适用场景分析demo实现，
    * 用蓝图来组织代码介绍。分区结构 VS 功能结构，适用场景分析。demo实现

* Flask-script扩展。应用场景分析， demo实现
* Flask-SQLAlchemy扩展（ORM）应用场景分析，简单demo实现
* Flask-Migrate扩展,应用场景分析，简单demo实现
* restful api分析及Flask-restful扩展介绍，应用场景分析 ，简单demo实现
