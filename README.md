# Makoto's LeetCode List

![mkt_lc](https://github.com/yuchengZhang009/MKTLCList/blob/main/mkt_lc.png)

## 前言

### 算法题、LeetCode和本题单

也许大家听过这样的比喻：对数据结构和算法的理解，是CS相关工程和科研的内功。或者说，就算日常的工作任务是CRUD，也得知其然并知其所以然。所以算法岗、开发岗招聘时，总会考几道算法题，有时机考OJ，有时是面试白板手撕。听说谷歌内部招聘，升L7级岗，都要考这个。

简而言之，找算法岗开发岗，要准备算法题。

LeetCode汇集了许多不同难度的算法题，并提供在线练习、题解讨论 ~~，事算法题平台中的豪杰（确信）~~

但LeetCode上的题目总数接近3000（2022.08），其中只有小部分是高频题、精华题、母题、重点题 ~~（做题家狂喜）~~

这个题单，就是对一些前人工作的综合和总结，包括了*：

- 剑指offer第二版
- labuladong的算法小抄 **
- 代码随想录——跟着Carl学算法
- 🔥 LeetCode 热题 HOT 100
- 🐧 腾讯精选练习 50 题
- 👨‍💻 LeetCode 精选 TOP 面试题

相当于求出多份题单的并集，给出了重点题的题库。~~私以为常见面试题都在里面了~~

\* ： 前三项为专讲算法题，备战面试的书籍，很值得推荐。后三项为LeetCode网站上的题单。

\** ：关于此书和此作者存在一定争议。参见[此处](https://www.zhihu.com/question/437514195)。



### 开刷前的准备

在开始刷题前，需要准备的是：

熟悉的1-2门编程语言，如C/C++、Python、JAVA。最好对它们的标准库中的常见工具也了解一些，不过也可以边刷边学。

了解最基本的数据结构的定义，如栈、队列、哈希集合、哈希表、二叉树；了解最基本的排序算法、搜索算法（如DFS、BFS）、递归思想等。会分析基本的算法时间、空间复杂度。

**最重要的还是时刻记住，什么不会，谷歌一下总能搞会。** 从概念（什么是递归？什么是动态规划？）到编程语言特性和工具（我作为Python小白第一次读collections和functools之类模块的文档时还是挺震撼的），这些都可以谷歌学会，还不会就再谷歌一下。

## 1、链表

|     题目                                                         |    备注  |
| ------------------------------------------------------------ | ---- |
| [19. 删除链表的倒数第   N 个结点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list) |      |
| [23. 合并K个升序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists) |      |
| [160. 相交链表](https://leetcode-cn.com/problems/intersection-of-two-linked-lists) |      |
| [剑指   Offer 18. 删除链表的节点](https://leetcode-cn.com/problems/shan-chu-lian-biao-de-jie-dian-lcof) |      |
| [剑指   Offer 22. 链表中倒数第k个节点](https://leetcode-cn.com/problems/lian-biao-zhong-dao-shu-di-kge-jie-dian-lcof) |      |
| [61. 旋转链表](https://leetcode-cn.com/problems/rotate-list) |      |
| [237. 删除链表中的节点](https://leetcode-cn.com/problems/delete-node-in-a-linked-list) |      |
| [328. 奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list) |      |
| [148. 排序链表](https://leetcode-cn.com/problems/sort-list)  |      |
| [2. 两数相加](https://leetcode-cn.com/problems/add-two-numbers) |      |
| [138. 复制带随机指针的链表](https://leetcode-cn.com/problems/copy-list-with-random-pointer) |      |
| [141. 环形链表](https://leetcode-cn.com/problems/linked-list-cycle) |      |
| [142. 环形链表   II](https://leetcode-cn.com/problems/linked-list-cycle-ii) |      |
| [206. 反转链表](https://leetcode-cn.com/problems/reverse-linked-list) |      |
| [21. 合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists) |      |
| [234. 回文链表](https://leetcode-cn.com/problems/palindrome-linked-list) |      |
| [剑指   Offer 06. 从尾到头打印链表](https://leetcode-cn.com/problems/cong-wei-dao-tou-da-yin-lian-biao-lcof) |      |
| [25. K 个一组翻转链表](https://leetcode.cn/problems/reverse-nodes-in-k-group) |      |
| [203. 移除链表元素](https://leetcode.cn/problems/remove-linked-list-elements) |      |
| [83. 删除排序链表中的重复元素](https://leetcode.cn/problems/remove-duplicates-from-sorted-list) |      |
| [92. 反转链表 II](https://leetcode.cn/problems/reverse-linked-list-ii) |      |

## 2、二叉树

## 3、哈希表

## 4、栈

## 附录

### 进阶

正如数学学科存在从省级到国际级的数学奥林匹克竞赛，这些算法题对应着各级信息学竞赛。对于各级信息学竞赛的参与者（通称OIers），力扣的难度顶多算是入门级。在信息学竞赛中，选手将学习更多、更复杂的数据结构和算法。他们来刷力扣基本属于降维打击。

如果想成为竞赛级算法强者，[点此](https://oi-wiki.org/)打开新世界的大门。

### 展望

有了题单，下一步我希望把每道题容易理解、说人话的题解加上去。另外，对力扣的简单题，用Python语言实现时常常能写出一行代码即可AC的效果。我愿称之为一行超人。就我所知，Github上也有一些repo记载了这些一行搞定简单题的代码。我希望未来有空，能收集一些有趣的“一行超人”代码 ~~（有生之年）~~
