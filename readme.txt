public class solution{
public int[] twosum(int[] nums,int target){
int[] res=new int[2];
if(num==null||nums.length==0){
return res;}
Map<Integer,Integer>map=new HashMap<>();
for(int i=0;i<=nums.length;i++){
int temp=target-num[i];
if(map.containsKey(temp)){
res[1]=i;
res[0]=map.get(temp);
}
map.put(num[i],i);
}
return res;
}
}
按照如下顺序将力扣题目做完，相信会帮助你对**动态规划之子序列问题**有一个深刻的理解。

300.最长递增子序列
674.最长连续递增序列
718.最长重复子数组
1143.最长公共子序列
1035.不相交的线
53.最大子序和
392.判断子序列
115.不同的子序列
583.两个字符串的删除操作
72.编辑距离
为了绝杀编辑距离，我做了三步铺垫，你都知道么？
647.回文子串
516.最长回文子序列
动态规划总结篇






1、反转链表（ LeetCode 206 ）
2、相交链表（ LeetCode 160 ）
3、合并两个有序链表 （ LeetCode 21 ）
4、分隔链表 （ LeetCode 86 ）
5、环形链表 II （ LeetCode 142 ）
6、反转链表 II （ LeetCode 92 ）
7、复制带随机指针的链表（ LeetCode 138 ）
8、栈的基础知识
9、有效的括号（ LeetCode 20 ）
10、基本计算器（ LeetCode 224 ）
11、最小栈（ LeetCode 155 ）
12、验证栈序列（ LeetCode 946 ）
13、每日温度（ LeetCode 739 ）
14、接雨水（ LeetCode 42 ）
15、队列的基础知识
16、用栈实现队列 （ LeetCode 232 ）
17、滑动窗口最大值（ LeetCode 239 ）
18、设计循环双端队列（ LeetCode 641 ）
19、移除链表元素（ LeetCode 203 ）
20、K 个一组翻转链表（ LeetCode 25 ）
21、回文链表（ LeetCode 234 ）
22、奇偶链表（ LeetCode 328 ）
23、从尾到头打印链表（ 剑指Offer 06 ）
24、链表中倒数第 k 个节点（ 剑指Offer 22 ）
25、剑指 Offer 40. 最小的k个数
26、剑指 Offer 41. 数据流中的中位数
27、剑指 Offer 51. 数组中的逆序对
28、合并 K 个升序链表（LeetCode 23）
29、合并两个有序数组( LeetCode 88 )
30、颜色分类(  LeetCode 75  )
31、部分排序 （面试题 16）
32、计算右侧小于当前元素的个数 ( LeetCode 315)
33、有序数组的平方( LeetCode 977 )
34、盛最多水的容器 ( LeetCode 11)
35、两数之和（LeetCode 1）
36、分发饼干（ LeetCode 455 ）
37、柠檬水找零（ LeetCode 860 ）
38、用最少数量的箭引爆气球（ LeetCode 452 ）
39、移掉 K 位数字（ LeetCode 402 ）
40、跳跃游戏（ LeetCode 55 ）
41、摆动序列（ LeetCode 376 ）
42、三数之和（LeetCode 15）
43、最接近三数之和（LeetCode 16）
44、加油站（ LeetCode 134 ）
45、二分查找（ LeetCode 704 ）
46、搜索插入位置（ LeetCode 35 ）
47、在排序数组中查找元素的第一个和最后一个位置（ LeetCode 34 ）
48、搜索旋转排序数组（ LeetCode 33 ）
49、搜索二维矩阵（ LeetCode 74 ）
50、寻找两个正序数组的中位数（ LeetCode 4 ）
51、有效三角形的个数（ LeetCode 611 ）
52、剑指 Offer 53 – II. 0～n-1中缺失的数字
53、剑指 Offer 53 – I. 在排序数组中查找数字 I
54、剑指 Offer 51. 数组中的逆序对
55、寻找峰值（ LeetCode 162 ）
56、第一个错误的版本（ LeetCode 278 ）
57、山脉数组的峰顶索引（ LeetCode 852 ）
58、有效的完全平方数（ LeetCode 367 ）
59、岛屿数量（ LeetCode 200 ）
60、N 皇后（ LeetCode 51 ）
61、火柴拼正方形（ LeetCode 437 ）
62、接雨水 II（ LeetCode 407 ）
63、组合（ LeetCode 77 ）
64、组合总和 II（ LeetCode 216 ）
65、分割回文串（ LeetCode 131 ）
66、全排列（ LeetCode 46 ）
67、二叉树的前序遍历（ LeetCode 144 ）
68、二叉树的中序遍历（ LeetCode 94 ）
69、二叉树的后序遍历（ LeetCode 145 ）
70、从前序与中序遍历序列构造二叉树（ LeetCode 105 ）
71、路径总和 II（ LeetCode 113 ）
72、二叉树的最近公共祖先（ LeetCode 236 ）
73、二叉树的右视图（ LeetCode 199 ）
74、二叉树展开为链表（ LeetCode 114 ）
75、完全二叉树的节点个数（ LeetCode 222 ）
76、二叉树的最大深度（ LeetCode 104 ）
77、二叉树的最小深度（ LeetCode 111 ）
78、爬楼梯（ LeetCode 70 ）
79、斐波那契数（ LeetCode 509 ）
80、最大子序和（ LeetCode 53 ）
81、零钱兑换（ LeetCode 322 ）
82、零钱兑换 II（ LeetCode 518 ）
83、最小路径和（ LeetCode 64 ）
84、编辑距离（ LeetCode 72 ）
85、买卖股票的最佳时机（ LeetCode 121 ）
86、买卖股票的最佳时机II（ LeetCode 122 ）
87、买卖股票的最佳时机III（ LeetCode 123 ）
88、买卖股票的最佳时机IV（ LeetCode 188 ）
89、最佳买卖股票时机含冷冻期(LeetCode 309)
90、买卖股票的最佳时机含手续费(LeetCode 714)
91、完全平方数（ LeetCode 279 ）
92、三角形最小路径和（ LeetCode 120 ）
93、不同路径（ LeetCode 62 ）
94、不同路径II（ LeetCode 63 ）
95、整数拆分（ LeetCode 343 ）
96、地下城游戏（ LeetCode 174 ）
97、打家劫舍（ LeetCode 198 ）
98、打家劫舍II（ LeetCode 213 ）
99、打家劫舍III（ LeetCode 337 ）
100、最长回文子串（ LeetCode 5 ）