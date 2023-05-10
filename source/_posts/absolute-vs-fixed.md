---
title: css中定位设为absolute和设为fixed的区别
tag: Web前端基础
---

区别很简单：
1、有滚动条的情况下，设为fiex定位元素不会随着窗口移动而移动，设为absolute定位则元素会随着窗口移动而移动
2、absolute相对于 static 定位以外的第一个父元素进行定位，fixed相对于浏览器窗口进行定位

参考文章：
[absolute和fixed的区别_absolute fixed_友人C君~的博客-CSDN博客](https://blog.csdn.net/CWH0908/article/details/86570568)
[前端面试题：relative、absolute、fixed分别相对于谁定义？_fixed定位是相对于谁的_前端程序员路易的博客-CSDN博客](https://blog.csdn.net/qq_46582421/article/details/123193937)