---
title: Using_Markdown_writing
date: 2023-05-21 16:54:43
tags: Markdown
mathjax: true
---

# 这是一级标题
下面开始说明如何使用markdown进行写作

## 这是二级标题

这是正文  
换一行？ （在上一行后面按两次空格，再回车就是换一行）

换一段（按两次换行就是换一段）  

### 1 强调  
**加粗了: 前后各加两个*号**  
*斜体：前后各加一个星号*

### 2 列表  
1. 自动编号：数字 + 点 + 空格即可
2. 来一个二级标题
   1. 按一下回车，再tab就行
3. 再来一个三级标题
   1. 按回车，再按tab
      1. 继续回车，再tab
   
### 3 插入图片：图床上传图片
把图片先上传到[自己的图床](https://imgse.com/cathyimage_)，然后复制生成的图片链接。  
格式为：!+[图片名字]+(http:\\……png) 
![p9Ip0b9](https://s1.ax1x.com/2023/05/21/p9Ip0b9.png)
*图片注释*  

或者：
[![p9Ipb28.png](https://s1.ax1x.com/2023/05/21/p9Ipb28.png)](https://imgse.com/i/p9Ipb28)

### 4 数学公式  
$$
\lim_{x \to \infin}\frac{sin(x)}{x}=1
$$

在一段文字中插入公式: $\lim_{x \to \infin}f(x)$, command + m 快捷键连按两次就可以生成4个美元符号然后输入公式



### 5 表格
| EMD    |   HHT    |   HHSA |
| :----- | :------: | -----: |
| 1      |    2     |      3 |
| 左对其 | 居中对齐 | 右对齐 |

调整编辑部分表格格式快捷键：  
先选中表格内容，然后：Alt（fn+option） + shift + f


### 6 插入链接
复制网址，然后选中要给超链接的文字，直接：command + v 就行  
这是一个laTex的[链接](https://www.latexlive.com/home)

### 7 code
英文的三个小点：1左边的那个键

``` javascript
import numpy as np
from PyEMD import EMD
import matplotlib.pyplot as plt 

```

### 8 导航
[![p9IpOKg.png](https://s1.ax1x.com/2023/05/21/p9IpOKg.png)](https://imgse.com/i/p9IpOKg)

### 9 将md文件导出为pdf
1. 首先下载这个插件：Markdown Preview Enhanced 
2. 然后 command + shift + v 打开 Preview **.md 界面
3. 最后在 Preview **.md 界面，右键，然后选中：Chrome(Puppeteer) --> PDF  即可

### 10 这是该md文件的下载链接！
