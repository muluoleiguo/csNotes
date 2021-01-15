线性结构

简单地说，线性结构就是表中各个结点具有线性关系。如果从数据结构的语言来描述，线性结构应该包括如下几点：

1、线性结构是非空集。

2、线性结构有且仅有一个开始结点和一个终端结点。

3、线性结构所有结点都最多只有一个直接前趋结点和一个直接后继结点。

 

数组(Array)、栈( Stack)、队列(Queue)、链表( Linked List)等数据的逻辑结构都属于线性表。

 

非线性结构

简单地说，非线性结构就是表中各个结点之间具有多个对应关系。如果从数据结构的语言来描述，非线性结构应该包括如下几点：

1、非线性结构是非空集。

2、非线性结构的一个结点可能有多个直接前趋结点和多个直接后继结点。

 

树( Tree)、图(Graph)、堆(Heap)、散列表(Hash)等数据的逻辑结构都属于非线性结构。



Assume that you have a 9 slots closed hash. If you used the hash function h(k) = k % 9 and pseudo-random probing, here the pseudo-random probing sequence di will be: 5,9,2,1,4,8,6,3,7. 

 

a) Show the final hash table after inserting the number sequence: 3, 27, 15, 72, 60, 12.

 

 b) After filling the above numbers, calculate the probability for each empty slot that it will be the next one filled.

 

c) Determine the ASL（平均关键字比较次数）when searching sequence 3, 27, 15, 72, 60, 12, 54 in the hash table 3

 

假设您有9个封闭的散列。 如果您使用哈希函数h（k）= k％9并使用伪随机探测，则伪随机探测序列di将为：5,9,2,1,4,8,6,3,7。

a）插入数字序列后显示最终的哈希表：3、27、15、72、60、12。

 

 b）填写完上述数字后，计算每个空插槽成为下一个空插槽的概率。

 

c）在哈希表3中搜索序列3、27、15、72、60、12、54时，确定ASL（平均关键字比较次数）