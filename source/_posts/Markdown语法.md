---
title: Markdown语法
date: 2020-02-04 17:31:10
tags: 
    - Markdown
categories:
    - Markdown
---
*****
#MarkDown标题
一级标题
=======
二级标题
---------------
<!-- more -->
井号可表示1到六级标题
#一级
##二级
###三级
######六级
****
#MarkDown段落格式
换行时两个或两个以上的空格加上换行

MARKDOWN支持三种字体，斜体，粗体和粗斜体

斜体用*斜体*
_xieti_

粗体用 __cuti__ **粗体**
斜体体用 ___粗斜体___
分隔线
*****
_________
----
~~s删除线~~
<u>下划线</u>
[^脚注].

[^脚注]:脚注内容
***
#MarkDown列表
* 第一项
* 第二项
1. 第一项
    + 点点点
    + ddd
    + 点点点

  列表嵌套需要在子列表之前加上四个空格

  ***
  #MarkDown区块
> 区块
> ss
> ss
> ss
> ss

区块可以与列表组合使用
****
#MarkDown上的代码
`printf()`函数
代码段可用三个点包围，并且可指定一种语言
``` C
int main（）
{
return 0；
}
```
****
#MarkDown上的链接
[链接名称](链接地址)
[菜鸟教程](www.runoob.com)

高级链接，类似于define

[菜鸟教程][1]

[1]:  www.runoob.com
****
#MarkDown图片
![RUNOOB 标](http://static.runoob.com/images/runoob-logo.png)

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

<img src="http://static.runoob.com/images/runoob-logo.png" width="100%">
****
#MarkDown表格

| 表头       | 表头  |       表头|
| :---   | :----: | ---: |
|单元格单元格   | 单  |  单元格 |
|1   |   |   |
可以用：表示表格的对齐方式
*****
#MarkDown高级应用
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

使用 <b>Ctrl</b>+<br>Alt</br>+<br>Del</br> 重启电脑
使用 <i>Ctrl<i>+<em>Alt</em>+<sub>Del</sub> 重启电脑

用反斜杠表示转义
**文本加粗**
\*\*文本加粗\*\*


$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
