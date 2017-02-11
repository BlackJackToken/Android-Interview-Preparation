# Android-Interview-Preparation
---

感觉时间过得很快，转眼就大三了。为了找到一份好实习，我需要制定一份全面的学习计划并且严格执行。这个repository就是我的学习计划，欢迎star和fork，欢迎补充。每个知识点准备好后一般都会发在我的笔记本上：[https://github.com/bboylin/MyNotebook](https://github.com/bboylin/MyNotebook)

* datastructure & algorithm
    * [排序](https://github.com/bboylin/MyNotebook/blob/master/part4/sort.md)
    * 基本数据结构：
        * 栈和队列
        * 堆和优先队列
        * 链表
        * 散列表
        * 斐波那契堆
    * 树
        * [红黑树](http://blog.csdn.net/qq_29407877/article/details/49556143)
        * [伸展树](https://github.com/bboylin/MyNotebook/blob/master/part4/splay.md)
        * [AVL](https://github.com/bboylin/MyNotebook/blob/master/part4/avl.md)
        * B树
    * 图
        * 基本的图算法
            * 深度/广度优先搜索
            * 拓扑排序
            * 强连通分量等概念
        * 最小生成树
            * Kruskal和Prim算法
        * 单源最短路径
            * Bellman-Ford算法
            * 有向无环图中的单源最短路径问题
            * Dijkstra
            * 差分约束和最短路径
        * 所有结对点的最短路径问题
            * 最短路径和矩阵乘法
            * Floyd-Warshall算法
            * 用于稀疏图的Johnson算法
    * 最大流问题
    * [动态规划](https://github.com/bboylin/MyNotebook/blob/master/part4/dp.md)
    * 贪心算法
        * 哈夫曼编码
        * 调度/装箱问题
    * 摊还分析
    * 随机化算法
    * 回溯
    * 分治
    * 多线程算法
    * 矩阵运算
    * 线性规划
    * 多项式与快速傅里叶变换
    * 数论算法
    * 字符串匹配

* android
    * android基础总结
    * 四大组件和AIDL
    * Http网络请求
        * 原理
        * 设计与实现
    * 内存泄漏分析
    * sqlite
    * 性能优化
    * 代码规范
    * 单元测试
    * 重构
    * IPC机制
    * Activity和fragment
    * 多线程
        * 消息机制（handler，looper，messageQueue）
        * 多线程和线程池
        * 同步集合
        * 同步锁
        * AsyncTask源码分析
    * view和动画
        * 自定义控件
        * [recyclerview和listview比较](https://github.com/bboylin/MyNotebook/blob/master/part1/RecyclerView%E5%92%8Clistview%E7%9A%84%E5%8C%BA%E5%88%AB.md)
        * scroller
        * 动画
    * surfaceView
    * bitmap
    * 热修复
    * [初探event bus和RxBus](https://github.com/bboylin/MyNotebook/blob/master/part1/%E5%88%9D%E6%8E%A2event%20bus%E5%92%8CRxBus.md)
    * orm
    * RxJava & RxAndroid
    * [Picasso源码分析](https://github.com/bboylin/MyNotebook/blob/master/part1/picasso%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90.md)
    * MVP/MVVM架构开发app
    * kotlin

* java

    * JavaSE(Java基础)
        * Java基础知识
        * [反射](https://github.com/bboylin/MyNotebook/blob/master/part3/java/reflection.md)
        * Java中的内存泄漏
        * String源码分析
        * Java集合框架
        * ArrayList源码剖析
        * LinkedList源码剖析
        * Vector源码剖析
        * HashMap源码剖析
        * HashTable源码剖析
        * LinkedHashMap源码剖析

    * JVM(Java虚拟机)
        * JVM基础知识
        * JVM类加载机制
        * Java内存区域与内存溢出
        * [垃圾回收算法](https://github.com/bboylin/MyNotebook/blob/master/part3/gc/java%E4%B8%AD%E7%9A%84%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6.md)

    * JavaConcurrent(Java并发)
        * Java并发基础知识
        * 生产者和消费者问题
        * Thread和Runnable实现多线程的区别
        * 线程中断
        * 守护线程与阻塞线程
        * synchronized
        * 多线程环境中安全使用集合API
        * 实现内存可见的两种方法比较：加锁和volatile变量
        * 死锁
        * 可重入内置锁
        * 使用wait/notify/notifyAll实现线程间通信
        * NIO
        * 实现java线程池


* 设计模式

  * [设计模式六大原则](https://github.com/bboylin/MyNotebook/blob/master/part2/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E5%85%AD%E5%A4%A7%E5%8E%9F%E5%88%99.md)
  * [单例模式](https://github.com/bboylin/MyNotebook/blob/master/part2/%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F.md)
  * Builder模式
  * 原型模式
  * 简单工厂
  * [工厂方法模式](https://github.com/bboylin/MyNotebook/blob/master/part2/%E5%B7%A5%E5%8E%82%E6%96%B9%E6%B3%95%E6%A8%A1%E5%BC%8F.md)
  * [抽象工厂模式](https://github.com/bboylin/MyNotebook/blob/master/part2/%E6%8A%BD%E8%B1%A1%E5%B7%A5%E5%8E%82%E6%A8%A1%E5%BC%8F.md)
  * [策略模式](https://github.com/bboylin/MyNotebook/blob/master/part2/%E7%AD%96%E7%95%A5%E6%A8%A1%E5%BC%8F.md)
  * 状态模式
  * 责任链模式
  * 解释器模式
  * 命令模式
  * 观察者模式
  * 备忘录模式
  * 迭代器模式
  * 模板方法模式
  * 访问者模式
  * 中介者模式
  * 代理模式
  * 组合模式
  * 适配器模式
  * 装饰模式
  * 享元模式
  * 外观模式
  * 桥接模式

* android项目实战
    * [西交Link](http://xjtu.link/)
    * Gank客户端
    * bilibili客户端

* 面试/笔试

* 读书笔记
    * thinking in java
        * [chapter1-13](https://github.com/bboylin/MyNotebook/blob/master/part7/thinking%20in%20java%E7%AC%94%E8%AE%B0%E4%B8%8A.md)
        * [chapter14-15](https://github.com/bboylin/MyNotebook/blob/master/part7/thinking%20in%20java%E7%AC%94%E8%AE%B0%E4%B8%AD.md)
        * [chapter16-21](https://github.com/bboylin/MyNotebook/blob/master/part7/thinking%20in%20java%E7%AC%94%E8%AE%B0%E4%B8%8B.md)
    * effective java
        * [chapter 2](https://github.com/bboylin/MyNotebook/blob/master/part7/effective%20java%E7%AC%AC%E4%BA%8C%E7%AB%A0%E7%AC%94%E8%AE%B0.md)
        * [chapter 3](https://github.com/bboylin/MyNotebook/blob/master/part7/effective%20java%E7%AC%AC%E4%B8%89%E7%AB%A0%E7%AC%94%E8%AE%B0.md)
    * android开发进阶：从小工到专家
    * android开发艺术探索
        * [第一章：activity的生命周期和启动模式](https://github.com/bboylin/MyNotebook/blob/master/part7/Android%E5%BC%80%E5%8F%91%E8%89%BA%E6%9C%AF%E6%8E%A2%E7%B4%A2%E7%AC%AC%E4%B8%80%E7%AB%A0%E7%AC%94%E8%AE%B0.md)
        * [第二章：IPC机制](https://github.com/bboylin/MyNotebook/blob/master/part7/Android%E5%BC%80%E5%8F%91%E8%89%BA%E6%9C%AF%E6%8E%A2%E7%B4%A2%E7%AC%AC%E4%BA%8C%E7%AB%A0%E7%AC%94%E8%AE%B0.md)
    * 设计模式之禅
    * android源码设计模式解析与实战
    * [CSAPP](https://github.com/bboylin/MyNotebook/blob/master/part6/csapp.md)
    * 算法导论
    * 深入理解java虚拟机
    * [程序员的自我修养：链接，装载和库](https://github.com/bboylin/MyNotebook/blob/master/part6/xiuyang.md)

* 操作系统
    * [进程管理](http://bboylin.xyz/2016/12/18/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E5%A4%8D%E4%B9%A0%E4%B9%8B%E8%BF%9B%E7%A8%8B%E7%AE%A1%E7%90%86/)
