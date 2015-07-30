##项目介绍
这是一个应用于机器学习和数据挖掘的算法库
项目涉及Topic Model、矩阵分解、最优化方法(Newton)、时间序列分析等常用挖掘功能。
该项目时间跨度较长，最早的代码始于2013年国庆节前后，前后加起来差不多2年多时间。
 
##项目原则
项目在过去、现在、将来始终遵循也将继续遵循以下两个原则：
1. 贵精不贵多 
2. 简单，可依赖 
不光是实现算法功能，而是每个功能都要从最底层开始优化实现。
从最底层使用的数据结构、查找排序算法、以及内存的分配和使用、矩阵运算优化等。 
此外，项目中尽量避免引入和使用复杂的数据结构，尽量摒弃所谓 **面向对象编程** 的陋习。
同时保证代码的层次清晰、模块分明、抽象合理、扩展方便，这都与**面向对象**没有关系。
该项目接口十分简单，大部分函数调用都是最简单的**一维数组**，不对数据做过多封装。

##项目重构
项目会不定期进行重构，主要我们认为需要就会进行，触发重构的条件有两个：
1. 我觉得需要重构了，是主观因素；
2. 代码量超过了10000行。 
我已经记不清代码有多少次突破10000行，然后又被我们压榨到10000行以内。
最终，第一版发布项目的代码总量定格在10230行。
包括Makefile，以及Cmake使用的CMakeLists.txt文件。

##项目使用
###Makefile
项目可直接使用make命令来进行编译
###cmake
如果你碰巧安装了cmake，
那我也碰巧提供了CMakeLists.txt
可以直接调用sh build.sh 来使用cmake进行编译
