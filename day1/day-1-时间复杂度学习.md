## Day-1 时间复杂度

### 7种时间复杂度

- O(1): 常数复杂度
- O(N)：线性时间复杂度
- O(N^2): 平方
- o(N^3)： 立方
- O(LogN): 对数复杂度
- O(2^n)：指数复杂度
- O(n!)：阶乘

### 主定理
大部分递推关系都可以使用[主定理](https://zh.wikipedia.org/wiki/%E4%B8%BB%E5%AE%9A%E7%90%86)推算时间复杂度

- 常用算法应用
	- 二分查找算法: O(LogN)
	- 二叉树遍历: O(N)
	- 最佳排序矩阵搜索: O(N)
	- 归并排序: O(NLogN)

### 思考题
- 二叉树遍历- 前序中序后序： O(N)
- 图的遍历：O(N) 
- 搜索算法(BFS/DFS):O(N) 

###  leetcode [爬楼梯问题](https://leetcode-cn.com/problems/climbing-stairs/solution/pa-lou-ti-by-leetcode/)
掌握除了斐波那契解法之外的其他思路，特别是可以将空间复杂度降为O(1)的算法

具体算法:
- 暴力破解法， 时间:O(2^N)
- 使用缓存(记忆化递归法)：时间O(N), 空间:O(N)
- 动态规划(斐波那契):时间O(N), 空间:O(N)
- 斐波那契数, 时间O(N), 空间:O(1)
- 斐波那契公式: 时间O(LogN), 空间:O(N)