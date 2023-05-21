---
author: OS
public: yes
tags: 
---
# 表格（Table）书写

要添加表，请使用三个或多个连字符（`---`）创建每列的标题，并使用管道（`|`）分隔每列。您可以选择在表的任一端添加管道。


```
| 行/列 | 列名2 | 列明3 |
| ----- | ----- | ----- |
| 行名1 |       |       |
| 行名2 |       |       |
| 行名3 |       |       |
```

呈现的输出如下所示：

| 行/列 | 列名2 | 列明3 |
| ----- | ----- | ----- |
| 行名1 |       |       |
| 行名2 |       |       |
| 行名3 |       |       |

单元格宽度可以变化，如下所示。呈现的输出将看起来相同。

```
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |
```


## 对齐

您可以通过在标题行中的连字符的左侧，右侧或两侧添加冒号（`:`），将列中的文本对齐到左侧，右侧或中心。

```
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

呈现的输出如下所示：

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## 格式化表格中的文字

您可以在表格中设置文本格式。例如，您可以添加链接，代码（仅反引号（`` ` ``）中的单词或短语，而不是代码块）和强调。

您不能添加标题，块引用，列表，水平规则，图像或HTML标签。

## 在表中转义管道字符

您可以使用表格的HTML字符代码（`&#124;`）在表中显示竖线（`|`）字符。

## OB 中支持的嵌套/混用

| 行/列 | 我是列名2 | 我是列名3 | 我是列名4 |
| ----- | ----- | ----- |----|
| 我是行名1 |  #我默认支持Tag哦     |       |
| 我是行名2 |   我也支持链接其他页面[[欢迎]]    |       |
| 我是行名3 | 我支持纯文本哦  |       |

## 表格相关的插件

### table extended（表格增强）


### table enhancer
功能：支持在 编辑模式 和 阅读模式下，像你熟悉的其他软件一样，所见即所得处理单元格和表格的行列操作（增删改查）

### table generator

功能：支持图形化创建1x1-5x8 的表格
配合：Editing tool bar 效果更佳


## 表格相关的转化工具

在线转化工具：https://tableconvert.com/zh-CN/

支持多种表格格式的相互转化

<iframe src="https://tableconvert.com/zh-CN/markdown-to-excel" allow="fullscreen" allowfullscreen="" style="height:1200px;width:100%;"></iframe>