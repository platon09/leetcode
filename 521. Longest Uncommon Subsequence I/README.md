### 题目分析
给定俩个字符串，然后返回最长的不同前缀字符串。

### 解题思路
题目很简单，换一个思路思考后，可以转换规则如下：  
比较两个字符串的长度，若不相等，则返回长度的较大值，若相等则再判断两个字符串是否相同，若相同则返回-1，否则返回长度。