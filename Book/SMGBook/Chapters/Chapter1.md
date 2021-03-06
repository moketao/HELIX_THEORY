
# 第一部分   

> #### he4o如何实现强人工智能
>
> 1. 通过he4o的设计原则和理念来介绍本系统的实现原理方式。
> 2. 通过对he4o架构的多种角度解析来加深讲解为什么这样实现。

<br><br><br><br><br>

# 第一章 设计理念

<br><br>

## 第一节 NoData

---

> 所有的被先天定义的数据或规则，都将作为"灵活性"的杀手存在。
>
> 
>
> 只有在不断的与现实世界、与自我的交互中，获取到的数据才是真实的，可能适应所有环境变化的数据与知识。
>
> 
>
> 所以NoData这个理念也本系统最早提出的理念之一，这个理念也形成了本系统最大的缺点：“即必须有一个成长期”。
>
> 
>
> <font color="green">注：如果将一个18岁的AI复杂生产10000台，就会有10000台成年AI。但这损失的是多样性，而这种多样性对于大多数情况下是非常重要的。</font>



## 第二节 浅思考和深思考

---

本系统将：

1. 未获取"注意力"的思考行为称为：浅思考。

2. 将获取注意力"的思考行为称为：深思考。

   ​

>  浅思考和深思考是：无意识、潜意识和有意识的代码表现的一部分。另一部分是思维任务的多线程。



## 第三节 LOP分层编程思想

---



**节前阅读：**

* [读本节内容前请点击阅读链接内容](../../手写笔记/Note4.md#n4p13loplayer-oriented-programming170803)



**本系统主要使用LOP分层思想开发   `而非常用的OOP。`**

1. 逻辑语言时代的函数和算法通过 CodeLayer 层来实现。
2. 面向对象的大多数编程理念通过 DataLayer (神经网络和知识表示)来实现。
3. 而逻辑全部使用 AwarenessLayer 意识和数据思考来实现，而意识又是多线程的。（无意识、潜意识与有意识）

**总结：**

* LOP的方式下输入端是现实世界，输出也是现实世界。并将“现实数据”的算法处理、自动抽象、IO、思考、意识、情感等融为一体。



**注：**

> 1. LOP的分层是说整个软件架构编程方式上的分层。
> 2. LOP是本系统将 “计算机软件” 与 “AI设计” 结合的一种方式。
> 3. LOP的分层编程思想，是使 “软件形式的AI系统” 有意识有通用智能的关键。
> 4. 意识操作的是主线程，但无意识操作在另一个线程运行。（LOP的方式让数据有了逻辑，让数据有了线程，而不是代码层实现）





## 第四节 三维思维抽象架构

---



**节前阅读：**

* [读本节内容前请点击阅读链接内容_3维抽象概述](../../框架/3维抽象概述.md#3维抽象概述)
* [读本节内容前请点击阅读链接内容_知识表示](../../框架/知识表示.md#第1维抽象的知识表示)

**概述：**

* “三维架构”是描述AI的长期认知体系的。
* 其描述了“AI”在成长过程中的行为、习惯、经验、性格、原则、更包括审美观、人格、思想、价值观的形成。





## 第五节 树形知识表示

---



**节前阅读：**

- [(N3P7)数据树理论](../../手写笔记/Note3.md#n3p7数据树理论)     
- [(N3P8)](../../手写笔记/Note3.md#n3p8)   

**概述：**

- “树形知识表示”是描述AI的长期“认知体系”与“神经网络”形成的结构的。  
- 其描述了“AI”在成长过程生成的各种数据，及抽象的各种数据。这些数据“形成的结构”。

**主要组成：**

1. 知识表示
2. 神经网络



## 第六节 类比、归纳与统计

---



**节前阅读：**

- [N5P2智能神经网络](../../手写笔记/Note5.md#n5p2智能神经网络)     

##### 前言：

* 在本系统中，类比、归纳与统计的使用非常广泛，几乎遍布于整个系统。

1. **类比:**

   * 概念：
     * 在本系统中，基于类比的“推理”、“抽象”等被广泛使用。
     * 类比被认为是AI算法的最小单元。
   * 用途：
     * 在“唯一性判断”中的应用。
     * 在知识的抽象时的应用。
     * “横向点亮”依赖类比的方式。
     * 在解决问题或者使用经验时的应用。
     * 对 “神经网络” 的类比。
     * 等等...
   * 其它：
     * 准确率
     * 相似性

2. **归纳：**

   * 概念：
     * 用于归类等归纳性功能。
   * 用途：
     * 在知识表示中的“抽象”功能，是以“归纳”为基础的。　

3. **统计：**

   * 概念：
     * 用于统计并记录一些数据或功能的使用率。


   * 用途：
     * 在神经网络中，一个非常重要的功能“强度”，就是基于统计的实现。





## 第七节 抽象与结构

---



1. **抽象**

   >  在he4o系统中，所有非直接表示实体的数据都是抽象数据（即意识流之上层），而抽象表现在“简单归纳”或“细分归纳”等神经网络中的高维节点。所以抽象是以“数据节点”或“神经网络”的方式体现的。

   * 归纳
   * 常识
     * 规律
     * 逻辑
     * Value(函数值)
   * 经验
   * MindValue
   * Mind权重

2. **结构**



## 第八节 智能多维神经网络

------

**概念：**

* 介绍：
  * 在he4o系统中，神经网络具有数据中枢和神经调用两大功能，具体将在后面第四章神经网络中详细介绍。

**前言：**

* 标题有些吹牛逼,其实就是树形的神经网络,
* 神经网络部分占到本系统近25%的内容。并且神经相关的包括：
  * 知识表示部分与网络部分，想像力，意识真实感，感觉，感受mindValue，创造力，智力，思考，常识，经验，习惯，性格，原则，思想，算法神经，函数。


**正文：**


1. **智能神经网络**
   * 神经网络的强大，神经网络解决`知识表示`难题（`从有限到无限`，`迁移学习能力`，`抽象能力`）
2. **多维神经网络**
   * 神经网络具有无限维度，互相嵌套与关联，神经网络中的关联是没有明确规定的，只要想到的都可以进行关联。




## 第九节 内外感觉

**概念：**

* [n4p18 内感觉](../../手写笔记/Note4.md#n4p18内感觉)
* [n5p14 外感觉](../../手写笔记/Note5.md#n5p14-外感觉)