# Leetcode-Python8
## 28. Find the Index of the First Occurrence in a String, 459. Repeated Substring Pattern, String summary, Two pointers summary

May 23, 2023  4h

On the eighth day, we will learn more about Strings. 
The challenges today are about KMP algorithms, which will be finished later. Then I wrote a summary of the string questions.

## 28. Find the Index of the First Occurrence in a String
[leetcode](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/)\
[Reading link](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0028.%E5%AE%9E%E7%8E%B0strStr.md)\
[video](https://www.bilibili.com/video/BV1PD4y1o7nd/?spm_id_from=pageDriver&vd_source=63f26efad0d35bcbb0de794512ac21f3)\
Will be finished later.

## 459. Repeated Substring Pattern
[leetcode](https://leetcode.com/problems/repeated-substring-pattern/)\
[Reading link](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0459.%E9%87%8D%E5%A4%8D%E7%9A%84%E5%AD%90%E5%AD%97%E7%AC%A6%E4%B8%B2.md)\
[video](https://www.bilibili.com/video/BV1cg41127fw/?spm_id_from=333.788&vd_source=63f26efad0d35bcbb0de794512ac21f3)\
Will be finished later.

## String summary
Two pointers are commonly used in arrays, linked lists, and string.\
Starting from the end to start when process a string is a useful way, like in [reading](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/%E5%89%91%E6%8C%87Offer05.%E6%9B%BF%E6%8D%A2%E7%A9%BA%E6%A0%BC.md). It's more efficient.\
Firstly do a partial reverse, then do a total reverse. This also is a new way to solve questions.

## Two pointers summary
**数组**上的元素，不能真正的删除，只能覆盖。\
反转**字符串**, 定义两个指针（也可以说是索引下标），一个从字符串前面，一个从字符串后面，两个指针同时向中间移动，并交换元素。\
在替换空格 中, 思路就是首先扩充数组到每个空格替换成"%20"之后的大小。然后双指针从后向前替换空格。\
删除冗余空格的过程中, ~~????~~
使用双指针法来翻转**链表**, 只需要改变链表的next指针的指向，直接将链表反转。\
在链表中求环，通过双指针判断是否有环，而且还要找到环的入口。使用快慢指针（双指针法），分别定义 fast 和 slow指针，从头结点出发，fast指针每次移动两个节点，slow指针每次移动一个节点，如果 fast 和 slow指针在途中相遇 ，说明这个链表有环。\
**哈希表**, n数之和使用双指针也可以解决。

