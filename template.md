<p>
    <center><font size=8 face="楷体">PaperMarkdown</font></center><br>
	<center><font size=5 face="楷体">一个简单的Markdown模板</font></center>
	<center><font face="楷体">Author：BobLi Swigger</font></center>
	<center><font face="楷体">日期：2020年11月09日</font></center>
</p>

<h1>目录</h1>

[TOC]

# 关于本模板

PaperMarkdown是一个简单易用的Markdown模板，你可以用这个模板记课堂笔记、写实验报告，甚至可以用它来写一些要求不太严格的论文！

# 为什么用Markdown

虽然Latex功能比Markdown强大，格式严谨，但是，Latex需要编译（我只想写一个实验报告，为什么要学习一门新的语法，甚至还要调试？），Latex的代码渲染非常奇怪（你会发现复制PDF中的代码格式乱的让你头痛）。因此，PaperMarkdown横空出世。

* 基于Markdown简单的写作方式
* 最小的文件体积（word和latex哪一个能比我占空间小？）
* 比word更优秀的数学公式渲染
* 比word和Latex更优秀的代码渲染（word有语法高亮？Latex的PDF代码复制有多乱？）
* 基于HTML：Markdown还不够？你可以直接在Markdown文件里面嵌入HTML代码来控制显示。

# 插入任何你想插入的东西

## 图片

如果你想要插入图片，如[图2-1](#Fig:NFA_1)，可以复制这一段代码，来插入你的图片，并添加引用。当然图片下方的标题你可以起任何你喜欢的名字。

<div id="Fig:NFA_1"><center>
<img src="https://tse4-mm.cn.bing.net/th/id/OIP.1hBTATaIYbqz9CqJbzrhWgHaE8?pid=Api&rs=1" style="zoom: 80%;" />
<br>图2-1
</center></div>
## 插入表格

如[表3-2](#Table:distinguish)，你可以复制这一段代码插入表格，并随时更改你的表格，你也可以为你的表格添加标题，交叉引用。

<div id="Table:distinguish"></div>

| Pi                 | Pi_new         | Explan                      |
| ------------------ | -------------- | --------------------------- |
| $A \rightarrow PE$ |                |                             |
| {A,B,C,D}{E}       | {A,B,C}{D}{E}  | 用b对{A,B,C,D}分割           |
| {A,B,C}{D}{E}      | {A,C}{B}{D}{E} | 用b对{A,B,C}分割             |
| {A,C}{B}{D}{E}     | {A,C}{B}{D}{E} | $\pi = 3.1415926$         |

<center>表3-2</center>

## 插入...

你甚至可以插入任何你想插入的东西，当然不是在本文件中集成，而是将它们上传到互联网上，并在Markdown内提供超链接引用任何东西。

<h3><center>参考文献</center></h3>

[1]  [百度](https://www.baidu.com/)