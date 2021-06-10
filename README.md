# Algorithm
梳理常用算法，leetcode刷题

## 回溯法
> 回溯法

优选搜算法，又称试探法。利用试探性的方法，在包含问题所有解的解空间树中，将可能的结果搜索一边，从而获得满足条件的解。搜索过程采用深度 遍历策略，并随时判定结点是否满足条件要求，满足要求就继续向下搜索，若不满足要求则回溯到上一层，这种解决问题的方法称为回溯法。

**回溯法求解问题步骤**

1. 针对给定问题，定义问题的解空间树；
2. 确定易于搜索的解空间结构；
3. 以深度优先方式搜索解空间，并且在搜索过程中用剪枝函数避免无效搜索；
4. 用回溯法求解问题，重点是设计问题的解空间树，其解题过程是深度遍历解空间树的过程。

> 解空间树
依据待求解问题的特性，用树结构表示问题的解结构、用叶子表示问题所有可能的解的一棵树。
