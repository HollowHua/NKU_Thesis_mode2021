# 南开大学本科生毕业论文(毕业设计)LaTeX模板（物理学院）
* 本模板除了标准字体外还用到了“方正粗楷简体”，个人授权免费，需自行下载安装。
* Windows下测试编译通过。
* **本人在此论文模板基础上，根据2021年物理学院论文格式要求做了一些修改，大体上符合新的格式要求。**
* 欢迎以后使用者继续完善此模板。
## 已知问题
* 英文题目无法自动换行（已经解决）
## 模板来源
[南开大学研究生（博士生）毕业论文LaTeX模板](https://github.com/NewFuture/NKThesis)

thanks to @darfux， @NewFuture


## 说明

### 文件夹及文件说明
* [main.tex](main.tex)模板入口
* [nkthesis.bib](nkthesis.bib) 参考文献bib文件，可使用Google学术或百度学术直接导出bibtex格式
* [tex/文件夹](tex/) 每一章单独一个文件,主要写作部分
* [tex/image](tex/) 默认的图片路径文件夹，论文中所使用的图片可以放在此文件夹中
* [NKThesis.cfg](NKThesis.cfg) 格式设置文件，主要设置封面、声明、摘要的格式和字体，可以使用ctrl+F查找需要修改的设置
* [NKThesis.sty](NKThesis.sty) 格式设置文件，其中有正文绝大多数的格式和字体设置

### 其他说明

* 支持绘图
* 支持语法高亮(`python`和`c++`特别优化)


## 编写

### 编译方式
`xelatex`(Tex编译)+`biber`(参考文献编译)

#### 编译脚本
* windows 双击 `build.cmd`即可
* linux 在此目录下运行 `./build.cmd`即可

#### 手动编译:
```
xelatex main
biber main
xelatex main
xelatex main
```

### 推荐编辑器和工具

基本要求: 自动补全，语法高亮，错误提示,实时预览,光标同步

* [sublime](https://www.sublimetext.com/) + [LatexTools插件](https://github.com/SublimeText/LaTeXTools) +[Sumatra pdf](https://www.sumatrapdfreader.org/download-free-pdf-viewer.html)
* [VS code](https://code.visualstudio.com/) + [LaTeX-Workshop插件](https://github.com/James-Yu/LaTeX-Workshop)

* **个人比较推荐VSCode + TexLive的编辑器和编译器，安装和配置过程参考知乎文章：[使用VSCode编写LaTeX](https://zhuanlan.zhihu.com/p/38178015)**
* **其中settings.json中的latex配置，嫌麻烦的可以使用我自己的一套配置(需要修改文件路径)，配置见文件[settings.txt](settings.txt)。**

# 预祝大家论文通过，顺利毕业！
