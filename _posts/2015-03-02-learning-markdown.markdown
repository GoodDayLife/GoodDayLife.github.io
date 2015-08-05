---
layout: post
title:  "Markdown基础学习!"
date:   2015-03-20 14:49:15
categories: Markdown
---

这几天折腾博客，就发现了Jekyll和Markdown。
用了几天的感觉是markdown+vim+jekyll+github那真是一个字“爽”啊！
下面是我从http://www.google.com下载的一个文档。虽然原作者没有整理很好，但是写得相当简洁。就上传了，顺便试一下上传的功能和下载的速度。
先试一下这个[下载链接]({{ site.url }}/assets/markdown.pdf)能不能用。

下面言归正传：开始学习markdown语法。
markdown大概分成以下几类：
# 标题
标题由1－6个\#表示，一级标题最大，其余亦如是。
# 强调
强调由两种方法表示;（一个符号表示斜体，两个符号表示粗体）：

1. 粗体	如： \*\* **这是粗体** \*\*或\_\___这是粗体__\_\_

2. 斜体 如： \**这是斜体*\* \__这是斜体_\_

# 引用
就像github上显示后的截图：
>这就是区块引用：
>这一行也是

# 列表
列表是由符号加一个空格组成，如：

1. red
2. green
3. blue

+ red
+ green 
+ blue

- red
- green 
- blue

# 链接
行内链接[链接](www.google.com)
就是一个方括号加一个不括号组成。小括号中可以是变量哦！
或者用\<\> 表示自动链接。
# 图片
![试一下](/assets/aaa.jpg)
	这是直接插入图片。

![试一下][try]
这是定义插入方式。

[try]:/assets/aaa.jpg "Optional title attribute"
# 代码
行内代码用两组\`\`符号，单独代码用一对\`符号。
# 分割线
有四种表示方法，用一划线时要与上文隔一行：

***

* * * 

*****

---

# 其他
单独表示符号时用反斜线来转意。



[我的仓库链接]: https://github.com/ICEleemoo
