# HTML入门笔记1

## 2021.1.25

## HTML是谁发明的

Tim Berners-Lee，李爵士。

## HTML起手式

在vscode中，使用`! + tab`可以快速生成html文档框架。

## 常用的表示章节标签

+ h1 - h6:文章标题标签，通常`h1`只有一个。
+ section: 表示一个独立的章节块。
+ article：表示文章的内容部分。
+ main：表示html文档中最重要的内容。
+ aside：表示分支内容，比如侧边栏的信息。
+ div：包裹内容的容器。
  
## html标签的全局属性

> 属性是控制html标签实际效果的开关。

+ class:给标签添加类名。
+ contenteditable:添加该属性可使标签包裹的内容被用户编辑。
+ hidden：隐藏标签内容。
+ id:标签的唯一标识，除非确定唯一，否则不推荐使用。
+ style:可以设置标签的css属性，修改标签内容的样式
+ tabindex:设置该属性可使用tab键在已设置的标签内容间跳转，按照正数的从小到大顺序跳转。设置为0时最后跳转，为-1时不可跳转。
+ title:给标签设置一个标题，当鼠标悬停到内容上时显示所设置的值。

## 常用内容标签

+ a:超链接，使用该标签的内容可点击，将跳转到设置的链接
+ strong：使用该标签将使包裹部分字体加粗。
+ em：使用该标签将使包裹部分字体变为斜体。
+ code：可使被包裹的内容呈现代码的字样。
+ pre:html默认多个缩进、空格只保留一个空格，该标签包裹内容会保留所有缩进、空格、换行。