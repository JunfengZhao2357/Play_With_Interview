## Problem1:
- 有一个字符串数组。将数组中的每一个字符串按照字母序排序：之后再将整个字符串数组按照字典序排序。那么时间复杂度为？
- 假设最长的字符串长度为s；数组中有n个字符串
- 对每个字符串排序：O(slogs)
- 将数组中的每一个字符串按照字母序排序：O(n*slogs)
- 将整个字符串数组按照字母序排序：O(s*nlogn)   其实在排序算法中O(nlogn)指的是比较的次数，对于int来说，那字符串会有s个字母，所以乘上s
- 时间复杂度：O(n*slogs)+O(s*nlogn)
---