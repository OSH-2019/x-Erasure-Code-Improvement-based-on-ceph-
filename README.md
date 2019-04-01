#OSH小组大作业

- [OSH小组大作业](#osh小组大作业)
    - [项目简介](#项目简介)
    - [小组成员介绍](#小组成员介绍)
    - [现有的成果](#现有的成果)
        - [小组讨论](#小组讨论)
        - [调研报告](#调研报告)


##项目简介
- 我们小组在咨询老师之后决定把分布式存储作为我们主要研究的目标，现阶段的想法可能还不是很成熟，项目简介也会持续不断更新。
- 现有想法

现有的数据库一般没有直接使用对象存储，至于底层采用块和文件的数据库均有实现，而数据库本身需要实现快速修改，快速访问的特性，底层使用哪种方式的性能并不能说一定前者与后者有明显区别。而Ceph本身是一个以对象存储为底层的架构，我们打算在这个已有的非常成熟的分布式系统上建立一个对数据库的实现，对其性能进行探究，并对此优化。
##小组成员介绍

张灏文

陈云开

毕超

刘硕

张铭哲
##现有的成果
###[小组讨论](https://github.com/OSH-2019/x-Distributed-System-based-on-ceph/tree/master/discussions)
###[调研报告](https://github.com/OSH-2019/x-Distributed-System-based-on-ceph/blob/master/docs/research.md)