### 编程题

#### 字符串
1. 给一个list of strings， 称为t， 要求实现数据结构，定义函数find(s), s 是一个字符串，返回true or false， true表示s可以由t中不重叠的子串组成，
t中的子串可以重复使用。要求查询时间尽可能短。
  Idea:
  Trie. [空间复杂度可能很高，子节点是所有可能的s， 所以查询时间可以做到O（1）]

2. （745）Prefix and Suffix Search
Given many words, words[i] has weight i.
Design a class WordFilter that supports one function, WordFilter.f(String prefix, String suffix). 
It will return the word with given prefix and suffix with maximum weight. If no word exists, return -1.
   Idea:
   Trie.

3. two_sum ？

4. 最长公共子串

5. 俩字符串s和t，找到s的最短子串，使得t的所有字符都包含在s中

6. 二叉树中没有重复的数字，给一个二叉树的前序后序遍历，求它的中序遍历有多少种情况。

7. 实现一个数据结构，在init（）函数里面给一个 list of string， 有重复的str在里面，在 dis（str1， str2）函数里面输出两个string在数组中最近的index
距离，因为每个人string可能出现多次。
类似 一道string 的题： 821. Shortest Distance to a Character

8. preorder traversal ，recursion and iteration


#### C++
1. const char* 和 char const*的区别

2. 字符串去空格

### 数学、概率
1. 掷骰子，123456都掷出的期望次数
https://www.zhihu.com/question/40320381

2. A、B投硬币，谁先投出正面谁获胜，A先投，求A获胜的概率
【泰勒展开的公式】

3. 小猪喝毒酒
有n瓶水，里面有一瓶毒药，用一堆🐷去喝水（可以喝多瓶），如果水里面有毒药，猪就死掉。猪不能重复用，问，能不能用最少的猪发现哪一瓶是毒药。
https://blog.csdn.net/xywlpo/article/details/6450670

4. 组合数学：m个非负整数的和为N，求解的个数

5. 已知随机函数可以随机生成0，1，2，3，4，那么怎么随机生成0，1，2，3，4，5，6

6. 给个硬币，要求定义一个事件，使得事件发生概率为1/pi



### 机器学习
1. 协同过滤，怎么优化矩阵运算？

2. 牛顿法

3. SVM的推导
