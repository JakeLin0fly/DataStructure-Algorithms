# Data-Structure-Algorithms


* ## 线性表

  *零个或多个数据元素的**有限序列***

  * ### [顺序表](https://github.com/JakeLin0fly/DataStructure-Algorithms/tree/master/SqList)

    *线性表的<font color=red>顺序存储结构</font> ，指的是用一段**地址连续的存储单元**依次存储线性表的数据元素*

  * ### 链表

    线性表的<font color=red>***链式存储结构*** </font>

    * #### [单链表](https://github.com/JakeLin0fly/DataStructure-Algorithms/tree/master/LinkList)

    * #### [静态链表](https://github.com/JakeLin0fly/DataStructure-Algorithms/tree/master/StaticLinkList)

        *用 <font color=red>数组</font>描述的**链表**叫做静态链表*
        
    * #### 循环链表

        *将单链表中终端结点的指针由空指针改为指向头结点，使得单链表形成一个环，这种头尾相连的单链表称为单循环链表，简称循环链表（circular linked list）*

    * #### 双向链表

        *双向链表是在单链表的每个结点中，再设置一个指向其前驱结点的指针域*

  * ### [栈](https://github.com/JakeLin0fly/DataStructure-Algorithms/tree/master/Stack)

    栈是限定仅在表尾进行插入和删除的线性表。又称为后进先出（**Last In First Out**，***LIFO***）的线性表。

  * ### [队列](https://github.com/JakeLin0fly/DataStructure-Algorithms/tree/master/Queue)

    队列是只允许在一端进行插入操作，而在另一端进行删除操作的线性表。是一种先进先出（***First In First Out***，***FIFO***）的线性表。

* ## 串
	
	串（string）是由零个或多个字符组成的有限序列，又称字符串。
	
	### 子串定位
	
	 * 朴素的模式匹配
	
	   主串S的每个字符，都与子串T的开头作比较，直到匹配成功或最终失败。（即***简单的双层循环***）
	
	   时间复杂度：***O(m+n)***
	
	 * **[KMP模式匹配算法](https://github.com/JakeLin0fly/DataStructure-Algorithms/tree/master/KMP)**
	
	   克努特-莫里斯-普拉特算法，KMP算法。
	
* ## 散列表


* ## 树
  
* ## 图



---

*源码参考：程杰《大话数据结构》*