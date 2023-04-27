# OJ系统的要点

![img](https://pic1.zhimg.com/80/v2-05b09b7884edb0f9917d5465d0bbc728_720w.webp)

[知乎日报：一小时从零建立你自己的 Online Judge - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/105300813)

### 如何处理题与答案的关系？

算法题方便。操作系统实验？计组的汇编实验？

涉及到oj核心的原理

### 怎么处理数据？

提交历史是否保存？

怎么利用这些数据

### 效率问题

多核调度

### 架构问题

后端和评测机如何动态扩缩容来应对不同场景

### 交付和部署

rkt/kata

![Docker 与 Linux 容器的区别一览](https://www.redhat.com/rhdc/managed-files/traditional-linux-containers-vs-docker_0.png)

![img](https://pic2.zhimg.com/80/v2-132b25f1a4cd3640139a7689541d83a9_720w.webp)![img](https://pic1.zhimg.com/80/v2-a72c9882137220c0436db5d707d3e8f0_720w.webp)

### 安全性

1)权限控制：要用低权限运行程序、有可能的话使用沙箱限制更多的权限；2)网站安全：要学会基本的防sql注入等；3)系统安全：管理好服务器，不过这个对学生来说可能难点，但是边学边做也还好；4)编译器修改：去掉不安全的.h和obj，这是个艰难的工程；5)源代码分析：定义一些危险关键字，找几个ACMer去实现词法分析&关键词过滤。

