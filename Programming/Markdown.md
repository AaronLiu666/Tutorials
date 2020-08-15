
## Github flavored Markdown

Github markdown 官方教程：
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)


### 数学公式
GitHub Flavored Markdown 曾经是支持 LaTeX 的，但是现在不支持了……因此若想在 README 或者评论中插入数学公式，就得使用另外的方式。

CodeCogs 提供了一个[在线 LaTeX 编辑器](https://www.codecogs.com/latex/eqneditor.php)，可以将输入的数学公式转换为图片，并自动生成 HTML 代码（也支持其他格式）。

其它可以安装 Mathjax

公式居中： 
```
$$ xxx $$
```

### VScode中的图床插件：PicGo

[PicGo](https://marketplace.visualstudio.com/items?itemName=Spades.vs-picgo)，用vscode编辑markdown时，可以安装这个插件，从而很方便地上传并插入图像。

操作|快捷键
---|---
Uploading an image from clipboard | Ctrl + Alt + U 
Uploading images from explorer | Ctrl + Alt + E
Uploading an image from input box | Ctrl + Alt + O


## 表格

一个快速编辑markdown和latex表格的网站：[Tables Generator](http://www.tablesgenerator.com/latex_tables)

## 常用命令

### 字体
加粗：
```
** 内容 **
```

斜体：
```
* 内容 *
```

### 图片
设置居中和宽度：
```
<div align=center><img src="https://img2018.cnblogs.com/blog/1921421/202002/1921421-20200214185756593-677332335.png" width = "60%" /></div>
```

```
<p align="center">
  <img width="60%" src="https://raw.githubusercontent.com/Mingrui-Yu/Seq-CALC/master/docs/sequence.png">
</p>
```