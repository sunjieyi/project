# project
项目文件


几个常用的markdown语法示例

标题

标题1
=====

#标题1

##标题2

###标题3
列表

###无序列表1

* 列表1
* 列表2
* 列表3

###无序列表2

- 列表1
- **列表2**
- 列表3

###有序列表

1. 列表1
2. 列表2
3. 列表3
弹出式注释

把鼠标停留在**HTML**和**W3C**上看会发生什么。

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium
定义列表

Apple
:   Pomaceous fruit of plants of the genus Malus in
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.
代码片段

    ```python
        #!python
        # -*- coding: utf-8 -*-
        from flask import Flask, render_template

        app = Flask(__name__)
        app.debug = APP_DEBUG

        #homepage just for fun
        @app.route('/')
        def home():
            return render_template('index.html')
    ```
角注

Footnotes[^1] have a label[^@#$%] and the footnote's content.

[^1]: This is a footnote content.
[^@#$%]: A footnote on the label: "@#$%".
表格

First Header  | Second Header
--------------|--------------
Content Cell  | Content Cell
Content Cell  | Content Cell
警告

####hint类型的警告
!!! hint "subject of hint"
    Any number of other indented markdown elements.

####note类型的警告
!!! note "subject of note"
    Any number of other indented markdown elements.
警告有多种类型，类型不同生成的html文档样式也不一样，可用的样式有 hint, attention, caution, danger, question, note。

强调

这是**黑体**写法
这是*斜体*的写法
超链接

这是一个[链接](https://github.com/kamidox/blogs)
这是另外一种[链接][1]的形式

[1]: https://pythonhosted.org/Markdown/extensions/index.html
引用

> 引用的文字内容
> 这是另外的引用内容
图片

![图片描述](https://raw.githubusercontent.com/kamidox/blogs/master/kamidox_icon.png)
目录

[TOC]