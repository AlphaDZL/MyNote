## Markdown



[TOC]

### 一级标题：
本行开头使用一个 （ # ） 加上一个（或多个）空格然后加上标题内容。

```
# 一级标题
```

### 二级标题：
本行开头使用两个（ ## ） 加上一个（或多个）空格然后加上标题内容。
```
## 二级标题
```
（总共六级标题，一级标题最大，级数越高，标题越小）

### 段落分隔：
只需用一行或多行空白行将段落之间分开即可。
```
First paragraph

Second paragraph
```
### 段落内换行：
一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行
```
First line.  
Second line.
```
### 有序列表：
每个列表项前，添加数字并紧跟一个（ . ） 号然后加上空格，数字不必按数学顺序排列，但是列表应当以数字 1 起始。
```
1. First item
2. Second item
3. Third item
4. Fourth item
```
1. First item
2. Second item
3. Third item
4. Fourth item
### 无序列表：
每个列表项前面添加破折号（ - ）、星号  （ * ） 或加号 （ + ） 然后加上空格 。缩进一个或多个列表项可创建嵌套列表。
```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
### 分隔线：
单独一行上使用三个或多个星号 ( *** )、破折号 ( --- ) 或下划线 ( ___ ) ，并且不能包含其他内容。
```
---
***
___
```
### 粗体：
使用两个 （ * ）号或者（  _  ）号，把想要加粗的内容括起来。
```
**加粗的内容__**
__加粗的内容__
```
### 斜体：
使用一个 （ * ）号或者（  _  ）号，把想要加粗的内容括起来。
```
*_斜体内容_*
_斜体内容_
```
### 代码块：
使用三个反引号（ \`\`\` ） 括起来（可以用四个反引号把三个反应号括起来，以此来让三个反引号显示出正常样子，如以下演示的例子）
````
```

```
````

### 链接：
链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。
```
[超链接显示名](超链接地址 "超链接title")
这是一个链接 [Markdown语法](https://markdown.com.cn "Markdown语法")。
```
这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")。

尖括号可以把URL或者email地址变成可点击的链接。
```
<https://markdown.com.cn>
<fake@example.com>
```
<https://markdown.com.cn>
<fake@example.com>

### 图片：
使用感叹号 ( ! ), 紧跟方括号( [ ] ) ，方括号内写替代文本，方括号后紧跟圆括号( ( ) ) 图片链接放在圆括号里，在原括号里，链接后可以增加一个可选的图片标题文本。
```
![一张图片](image.png "图片1")
```
### 图片链接：
链接语法括住图片语法即可。
```
[![一张图片](image.png "图片1")](https://markdown.com.cn)
```

### 目录树：
只需要在文档中增加 [TOC] ，就会自动根据文档中的h1~h6标题生成目录树。

### 页内跳转:

Markdown会自动给每一个h1~h6标题生成一个锚，其id就是标题内容。

```
[Markdown](#Markdown)
```
[跳转到顶部](#Markdown)

### 自定义锚：

假设我们想跳转到文档中的一个不是标题的位置，则需要在该位置自定义一个锚。可使用HTML语法来定义一个锚。可选的HTML标签很多，比如`<span>、<a>`等等。
锚点：
```
<span id="loc"></span>
```
<span id="loc"></span>
跳转点：

```
[点击跳转](#loc)
```
[点击跳转](#loc)


### 转义字符：
大多数在字符前面添加反斜杠字符( \ )。（例外 ：  <  使用`&lt;`转义，&  使用 `&amp;`转义）

### 表著作权的符号：
```
&copy;AlphaDZL
```
&copy;AlphaDZL

### 内嵌 HTML 标签:

行级內联标签可直接使用，块级标签必须在前后加上空行。另外在 HTML 块级标签内不能使用 Markdown 语法。

### 引用语法：
在段落前添加一个（  >  ）符号。
```
> First line.
>
>> Second line.
```
> First line.
>
>> Second line.

