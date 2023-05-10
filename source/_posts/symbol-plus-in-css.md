---
title: css中加号选择器的用法
tag: Web前端基础
categories: 技术分享
---

# 加号 +
加号选择的是当前元素的后面的第一个兄弟元素，两个元素必须有同一个父元素
```code
<div>
    <p>001</p>
    <div class="box">
        <p>002</p>
    </div>
    <p>003</p>
    <p>004</p>
</div>
```


```code
.box + p{
    /** 表示 class 为 box 的 div 后方同层级的第一个 p 元素即内容为 003 的 p 标签/
}
```



参考资料：
[CSS选择器，+ ，＞ 和 ~_css加号选择器_教宗沙立van的博客-CSDN博客](https://blog.csdn.net/a1353206432/article/details/121319775)