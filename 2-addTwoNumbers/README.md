## 题意分析

给出两个链表表示两个整数，表头代表低位。返回一个两个整数相加之后的链表表示。

## 题解思路

直接从低位到高位用链表模拟即可，有几点注意事项：

+ 注意设置进位标记；
+ 注意两个整数长短不一时，在余出的长度部分相当于加0；
+ 不要忘记余出长度部分的进位标记，比如1+999，进位标记需要一直传递；
+ 注意0+0的特殊情况。

