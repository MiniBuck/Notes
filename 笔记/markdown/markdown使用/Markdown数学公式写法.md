# Markdown数学公式写法
​	因为决定要好好记笔记，不然是真的忘，所以此文产生,个人觉得Typora比MarkdownPad 2好用些，毕竟所见即所得嘛。

[TOC]

## 行内公式与行间公式
行内公式指与正文同行，行间公式与当前所在行换行。

​	这是行间公式：
$$
f(x)=\int_{-\infty}^{\infty} t^{z-1}e^{-t}dt
$$
​	这是行间工具：$f(x)=\int_{-infty}^{infty}t^{z-1}e^{-t}dt$

​	行内公式是以`$`起始，以`$`结束；行间公式以`$$`开始和结束，注意直接显示美元符时需要反斜杠转义,这里用的是但行代码块\`\`。

## 上标与下标

​	上标与下标使用`^`与`_`，如`\int_{-\infty}^{\infty}`表示:$\int_{-\infty}^{\infty}$。注意为了消除二义性，需要使用大括号进行分组，如`a^{b^c}`表示$a^{b^c}$。

## 括号

​	小括号中括号正常使用，大括号需要转义，否则与表示分组的大括号冲突，即`\{\}`表示$\{\}$。

​	使用`\left`与`\right`修饰括号可以使括号大小与公式相适应，如`\left(\frac{x}{y}\right)`: 

$\left(\frac{x}{y}\right)$。大括号可以也可由`\lbrace`和`\rbrace`来表示。

## 尖括号

​	不同于大于小于号，使用`langle`与`rangle`，例如`\langle x lrangle`表示$\langle x \rangle$。

## 取整

​	上取整：`\lceil x \rceil`,如$\lceil x \rceil$。

​	下取整:`\floor x \rfloor`,如$\lfloor x \rfloor$。

## 求和

​	求和符号`\sum`，下标表示下限，上标表示上限。例如：

​	$\sum_{i = 1}^n x_i$ 的写法：`\sum_{i = 1}^n x_i`；

## 积分

​	积分(integral)符号`\int`,上下标分别表示上下限，多重积分仍使用`\int`符号，i的个数等于积分会重数。

​	$\int_{y=i}^{k} \int_{x=i}^{j}xydxdy$ 写法：`\int_{y=i}^{k} \int_{x=i}^{j}xydxdy`。

​	$\iiint$的写法`\iiint`。

## 连乘

​	连乘(product)符号`\prod`,上下标表示连乘开始与结束。

​	$\prod_{i=1}^{K}x_i$ ：`\prod_{i=1}^{K}x_i`

## 未完待续

先暂时记这么多，之后随用随记......

[参考链接]:https://www.jianshu.com/p/068172920337	"Typera Markdown语法详解"
[参考链接]: https://www.jianshu.com/p/25f0139637b7	"markdown中公式编辑教程"

