## Plans and notes

> Study hard, work hard, enjoy it!

## Python

1. [完全卸载 python](https://github.com/Gaotianhe/Learninglist/issues/25)
2. [python pip 工具无法使用的问题](https://github.com/Gaotianhe/Learninglist/issues/24)
3. [Python 和 pip 镜像 + 安装dlib遇到的坑 + 学习bs4](https://github.com/Gaotianhe/Learninglist/issues/13)
4. [Python - virtualenv deploy](https://github.com/Gaotianhe/Learninglist/issues/38)
5. [Python for beginners](https://github.com/Gaotianhe/Learninglist/issues/41)

## [数据结构和算法](https://github.com/Gaotianhe/Learninglist/labels/Datastructure-and-Algorithm)

1. [算法 - 如何高效地做题](https://github.com/Gaotianhe/Learninglist/issues/18)
2. [读《算法笔记》 - 基本数据类型](https://github.com/Gaotianhe/Learninglist/issues/49)

时间、空间复杂度分析是数据结构和算法中的重中之重！！！掌握：时间、空间复杂度的概念，大O表示法的由来，各种复杂度分析技巧，以及最好、最坏、平均、均摊复杂度分析方法。

数据结构和算法的概念：从广义上讲，数据结构就是指一组数据的存储结构。算法就是操作数据的一组方法。图书馆储藏书可以进行对比，所有的书“数据”，都要按照某种规则“结构”分门别类地存储起来，这是为了方便以后的借阅。从狭义上讲，就是专指一些数据结构和算法：队列、栈、堆、二分查找、动态规划等。

数据结构和算法是相辅相成的。数据结构是为算法服务的，算法要作用在特定的数据结构之上。

王争（曾经在google工作）总结的20个最常用的、最基础的数据结构和算法知识点。10个数据结构：**数组、链表、栈、队列、散列表、二叉树、堆、跳表、图、Trie树**；10个算法：**递归、排序、二分查找、搜索、哈希算法、贪心算法、分治算法、回溯算法、动态规划、字符串匹配算法**。要学习数据结构和算法的：“来历”、“自身的特点”、“适合解决的问题”、“实际的应用场景”

学习技巧：1）边学边练，适度刷题；2）多思考、多交流、多问；3）设定一个踮起脚尖就能碰到的目标，完成后奖励自己，再次设定目标；4）知识的积累沉淀需要时间，不要着急。

[数据结构和算法动态可视化](https://visualgo.net/en)

### 第一阶段
- 复杂度分析
- 数组、栈、队列
- 链表
- 递归
- 排序、二分查找

### 第二阶段
- 散列表
- 二叉树
- 堆和堆排序
- BF/RK字符串匹配算法
- Trie 树
- 图的表示
- 深度广度优先搜索

### 第三阶段
- 四种算法思想
- 跳表
- 拓扑排序、Dijkstra 算法、A<sup>*</sup> 算法
- B+ 树
- 位图

### 第四阶段
- BM、KMP、AC 自动机
- 红黑树
- 哈希算法

### 数据结构与算法-框架
```text
数据结构和算法
.
└── 复杂度分析
        ├── 空间复杂度
        └── 时间复杂度
                ├── 最好
                ├── 最坏
                ├── 平均
                └── 均摊


└── 基本算法思想
        ├── 贪心算法
        ├── 分治算法
        ├── 动态规划
        ├── 回溯算法
        └── 枚举算法


└── 排序
      ├── O(n^2)
            ├── 冒泡排序
            ├── 插入排序
            ├── 选择排序
            └── 希尔排序
      ├── O(nlogn)
            ├── 归并排序
            ├── 快速排序
            └── 堆排序
      └── O(n)
            ├── 计数排序
            ├── 基数排序
            └── 桶排序


└── 线性表
      ├── 数组
      ├── 链表
            ├── 单链表
            ├── 双向链表
            ├── 循环链表
            ├── 双向循环链表
            └── 静态链表
      ├── 栈
            ├── 顺序栈
            └── 链式栈
      └── 队列
            ├── 普通队列
            ├── 双端队列
            ├── 阻塞队列
            ├── 并发队列
            └── 阻塞并发队列


└── 散列表
      ├── 散列函数
      ├── 冲突解决
            ├── 链表法
            ├── 开放寻址
            └── 其他
      ├── 动态扩容
      └── 位图


└── 树
      ├── 二叉树
            ├── 平衡二叉树
            ├── 二叉查找树
            ├── 平衡二叉查找树
                    ├── AVL 树
                    └── 红黑树
            ├── 完全二叉树
            └── 满二叉树
      ├── 多路查找树
            ├── B 树
            ├── B+ 树
            ├── 2-3 树
            └── 2-3-4 树
      ├── 堆
            ├── 小顶堆
            ├── 大顶堆
            ├── 优先级队列
            ├── 斐波那契堆
            └── 二项堆
      └── 其他
            ├── 树状数组
            └── 线段树


└── 图
      ├── 图的存储
            ├── 邻接矩阵
            └── 邻接表
      ├── 拓扑排序
      ├── 最短路径
      ├── 关键路径
      ├── 最小生成树
      ├── 二分图
      └── 最大流


└── 搜索
      ├── 深度优先搜索
      ├── 广度优先搜索
      └── A<sup>*</sup> 启发式搜索


└── 查找
      ├── 线性表查找
      ├── 树结构查找
      └── 散列表查找


└── 字符串匹配
      ├── 朴素
      ├── KMP
      ├── Robin-Karp
      ├── Boyer-Moore
      ├── AC 自动机
      ├── Trie
      └── 后缀数组


└── 其他
      ├── 数论
      ├── 计算几何
      ├── 概率分析
      ├── 并查集
      ├── 拓扑网络
      ├── 矩阵运算
      └── 线性规划
```

## 操作系统

1. [Win10 - CPU使用率和环境变量格式修改](https://github.com/Gaotianhe/Learninglist/issues/14)
2. [Linux - Linux下tar命令解压到指定目录](https://github.com/Gaotianhe/Learninglist/issues/7)
3. [Linux - CentOS源码编译安装Nginix（等待补充）](https://github.com/Gaotianhe/Learninglist/issues/6)
4. [Linux - 在Ubuntu18.04（阿里轻量应用服务器）上装nginx](https://github.com/Gaotianhe/Learninglist/issues/5)
5. [Linux - 在Linux安装Reslio Sync文件传递软件](https://github.com/Gaotianhe/Learninglist/issues/4)
6. [Linux - apt-get: command not found](https://github.com/Gaotianhe/Learninglist/issues/32)
7. [Docker - 使用docker部署IPFS节点](https://github.com/Gaotianhe/Learninglist/issues/33)
8. [Docker - docker安装Ubuntu](https://github.com/Gaotianhe/Learninglist/issues/36)
9. [Vbox - 动态分配空间压缩空间大小](https://github.com/Gaotianhe/Learninglist/issues/57)