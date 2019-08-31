# 正则表达式 

* 正则表达式(Regular Expression)是一种文本模式，包括**普通字符**（例如，`a 到 z `之间的字母）和**特殊字符**（称为`元字符`）。
* 正则表达式使用单个字符串来描述、匹配一系列匹配某个句法规则的字符串。
* 正则表达式是繁琐的，`但它是强大的`，学会之后的应用会让你除了提高效率外，会给你带来绝对的成就感。只要认真阅读本教程，加上应用的时候进行一定的参考，掌握正则表达式不是问题。

先体会一下他都能做什么？
```js
var str = "abc123def";
var patt1 = /[0-9]+/;
document.write(str.match(patt1)); // 123
```

显而易见正则表达式可以帮助我们匹配到我们想要的绝大部分格式的数据（文本）

这里我们会用大量的例子来解释每一个方法、符号、字符的含义和使用场景

数字1、2、3和各种符号大家都认识，可一旦出现微积分、极限、导数大家就会头疼，正则也一样，所以我们共勉～


### 内容列表

1. 正则表达式 - 简介
2. 正则表达式 - 语法
3. 正则表达式 - 元字符
4. 正则表达式 - 运算符优先级
5. 正则表达式 - 匹配规则
6. 正则表达式 - 示例
7. 正则表达式 - 在线工具