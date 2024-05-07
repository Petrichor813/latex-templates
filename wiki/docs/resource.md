# LaTeX 资源

??? abstract "参考目录"

    - [写作环境](#写作环境)
      - [TeX 发行套装](#tex-发行套装)
      - [专用编辑器](#专用编辑器)
      - [通用编辑器](#通用编辑器)
      - [在线平台](#在线平台)
      - [在线工具](#在线工具)
    - [LaTeX 相关资源](#latex-相关资源)
      - [社区和问答](#社区和问答)
      - [学习资料](#学习资料)
        - [在线资料](#在线资料)
        - [出版书籍](#出版书籍)
      - [示例和模板](#示例和模板)
    - [其他资料](#其他资料)
      - [中文文献引用](#中文文献引用)
      - [公式渲染](#公式渲染)
      - [许可证](#许可证)
      - [参考资料](#参考资料)

更多参考：

- [:simple-github: egeerardyn/awesome-LaTeX](https://github.com/egeerardyn/awesome-LaTeX)
- [:simple-github: writing-resources/awesome-scientific-writing](https://github.com/writing-resources/awesome-scientific-writing)

## 写作环境

### TeX 发行套装

- [TeXLive](https://tug.org/texlive/): 支持 Windows, Linux
- [MacTeX](https://www.tug.org/mactex/)：支持 macOS，TeXLive 在 mac 系统的发行版
- [MikTeX](https://miktex.org/): 主要支持 Windows

```shell
# macOS 环境配置
brew install mactex-no-gui
brew install tex-live-utility

# 修改镜像【可选】
sudo tlmgr option repository https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/tlnet
# 更新【可选】
sudo tlmgr update --self --all
```

备注：

1. 也可以选择体积更小的`basictex`。
2. `tex-live-utility`即 Tex 的包管理工具`tlmgr`
3. `mactex-no-gui`相比`mactex`去掉了一些 GUI 程序（大部分都不太常用）。

### 专用编辑器

- [WinEdt](https://www.winedt.com/): 收费软件，仅 Window。
- [Texifier（原 TexPad）](https://www.texifier.com): 收费软件，仅 macOS，正在支持 Windows。
- [TeXmaker](https://www.xm1math.net/texmaker/): 开源免费跨平台。
- [TeXStudio](https://www.texstudio.org/): 开源免费跨平台。
- [TeXworks](https://tug.org/texworks/): TexLive 自带，功能简单。
- [TeXShop](https://pages.uoregon.edu/koch/texshop/): MacTeX 自带，功能简单。

### 通用编辑器

- Visual Studio Code，并推荐安装 LaTex Workshop 等插件
- Vim, Emacs 等等

### 在线平台

- [Overleaf](https://www.overleaf.com/) （ShareLaTeX 已经合并到 Overleaf）
- [TeXPage](https://texpage.com/): 国内最近新出的 LaTeX 在线平台（中国版`Overleaf`）。

### 在线工具

- LaTeX 表格生成：<https://www.tablesgenerator.com/>
- LaTeX 数学公式编辑: <https://www.latexlive.com/>
- LaTeX 数学公式可视化编辑和函数图像（在线版本免费，离线版本收费）：<https://www.mathcha.io/>
- LaTex 数学符号查询（仅限英文）：<https://latex.guide/>
- 手写字符（特殊符号）识别： <http://detexify.kirelabs.org/classify.html>
- 速查表（LaTeX cheat sheet）：<https://quickref.me/latex>

---

## LaTeX 相关资源

> 善用搜索引擎和 AI 问答工具。

### 社区和问答

**外文社区**

- [Teh LaTeX Project](https://www.latex-project.org/): LaTeX 官方站
- [CTAN Comprehensive TeX Archive Network](https://www.ctan.org/): 汇集与 TeX 相关的各种（大部分）资源。各地有镜像站。
- [TeX Users Group](https://tug.org/): Tex 用户组，提高了 texlive 下载。
  - [texdoc](https://texdoc.org/index.html)： 在线文档（仅给出文档路径和 PDF 链接），可以作为 CTAN 的查询补充。
- [TeX | StackExchange](https://tex.stackexchange.com/): 高质量问答网站
- [LaTeX forum 社区](https://latex.org/forum/)
- [The TeX Frequently Asked Question List](https://texfaq.org/)

**中文社区**

- [王昭礼 - LaTeX 工作室](https://www.latexstudio.net/)
- [CTEX](https://ctex.org/): 论坛已经关闭，代替品[Github CTeX-org/forum/issues](https://github.com/CTeX-org/forum/issues)

### 学习资料

#### 在线资料

比较经典和简短的入门文档

**外文文档**

- Indian TEX Users Group - [LATEX Tutorials A PRIMER, 2003](https://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf)
- Luong Vo - [Begin LaTeX in minutes](https://luong-komorebi.github.io/Begin-Latex-in-minutes/): 多种语言
- Overleaf - [Learn LaTeX in 30 minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
- Xiong Ying - [A simple guide to LaTeX – Step by Step](https://www.latex-tutorial.com/tutorials/)
- Joseph Wright - [Learn LaTeX](https://www.learnlatex.org/en/)
- Tobias Oetiker - [The Not So Short Introduction to LaTeX2e](https://ctan.org/tex-archive/info/lshort/english/lshort.pdf)
  - [Github 最新版本](https://github.com/oetiker/lshort)
  - [Nightly version 7.0, 2022](https://tobi.oetiker.ch/lshort/lshort.pdf)
  - 中文翻译[一份（不太）简短的 LaTeX2e 介绍](https://ctan.org/tex-archive/info/lshort/chinese/lshort-zh-cn.pdf)
- Joseph Wright - [Beamer - A LaTeX class for producing presentations](https://github.com/josephwright/beamer)

**中文文档**

- Liam Huang - 博客 [一份其实很短的 LaTeX 入门文档](https://liam.page/2014/09/08/latex-introduction/)
- 包太雷（黄新刚） - 《LATEX NOTES 雷太赫排版系统简介》， [Github](https://github.com/huangxg/lnotes/)
- Xinyu Chen（陈新宇） - 《LaTeX 论文写作教程 (中文版)》[Github](https://github.com/xinychen/latex-cookbook)
- 视频：[Bilibili - 刘海洋 · LaTeX 不快速的入门](https://www.bilibili.com/video/BV1s7411U7Pr/)
- [LaTeX 文档中文翻译项目](https://github.com/rockyzhz/latexdoc-chinese-translation)

#### 出版书籍

**外文书籍**

- Stefan Kottwitz - 《LaTeX Beginner's Guide, Second Edition》
  - [Github](https://github.com/PacktPublishing/LaTeX-Beginner-s-Guide-Second-Edition)
  - [latexguide](https://latexguide.org/)
- Nicola L. C. Talbot - 《Dickimaw LaTeX Series》3 卷本
  - Volume: 1, [LaTeX for Complete Novices](https://www.dickimaw-books.com/latex/novices/index.html)
  - Volume: 2, [Using LaTeX to Write a PhD Thesis](https://www.dickimaw-books.com/latex/thesis/index.html)
  - Volume: 3, [LaTeX for Administrative Work](https://www.dickimaw-books.com/latex/admin/index.shtml)
- ……

**中文书籍**

- 刘海洋 - 《LaTeX 入门》，2013 年， [豆瓣](https://book.douban.com/subject/24703731/)
- 吴康隆 - 《简单高效 LaTeX》，2020 年 [豆瓣](https://book.douban.com/subject/35147521/), [Github-《简单粗暴 LaTeX》](https://github.com/wklchris/Note-by-LaTeX)
- 胡伟 - 《LaTeX2e 完全学习手册（第二版）》 [豆瓣](https://book.douban.com/subject/24371496/)

### 示例和模板

- LaTeX 模板：
  - <https://www.latextemplates.com/>
  - <https://www.overleaf.com/latex/templates/>
  - <https://github.com/dustinvtran/latex-templates>
- LaTeX 绘图:
  - TikZ: <https://texample.net/tikz/examples/>
  - Asymptote: <https://asymptote.sourceforge.io/gallery/>
- Beamer 主题：
  - <https://deic.uab.cat/~iblanes/beamer_gallery/>
  - <https://hartwork.org/beamer-theme-matrix/>
  - <https://github.com/martinbjeldbak/ultimate-beamer-theme-list>
  - <https://github.com/XiangyunHuang/awesome-beamers>

---

## 其他资料

### 矢量校徽

- 参考所在学校官方网站。
- 普鲁文, [figma.com - 中国大学矢量校徽合集](https://www.figma.com/community/file/916515339708288305)
- [urongda.com - 中国大学矢量校徽合集](https://www.urongda.com/)

### 中文文献引用

《信息与文献 参考文献著录规则》（GB/T 7714–2015）

- 国家标准，2015 年 5 月 15 日发布，2015 年 12 月 1 日实施，代替《文后参考文献著录规则》（GB/T 7714-2005）
- 相关信息查看[全国标准信息公共服务平台](https://std.samr.gov.cn/gb/search/gbDetailed?id=71F772D8055ED3A7E05397BE0A0AB82A)。版权原因，自行搜索全文。
- LaTeX 相关实现：
  - [hushidong/biblatex-gb7714-2015](https://github.com/hushidong/biblatex-gb7714-2015)
  - [zepinglee/gbt7714-bibtex-style](https://github.com/zepinglee/gbt7714-bibtex-style)
  - [redleafnew/Chinese-STD-GB-T-7714-related-csl](https://github.com/redleafnew/Chinese-STD-GB-T-7714-related-csl)

### 公式渲染

- [MathJax](https://www.mathjax.org/): 浏览器网页显示数学公式的 JavaScript 渲染引擎，支持语言 LaTex、MathML、AsciiMath。
  - StackExchange: [MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)
- [KaTex](https://katex.org/): 数学公式渲染器 ，相比 MathJax 更轻量级。
  - [文档 - Supported Functions](https://katex.org/docs/supported.html)

### 许可证

- [LPPL 协议](https://www.latex-project.org/lppl/): 分发 LaTeX 内核和相关软件包的主要许可证

### 参考资料

- 知乎 - [[LaTeX 指南] 互联网上的 LaTeX 资源](https://zhuanlan.zhihu.com/p/44137623)
- Github·LaTeXStudio - [LaTeXStudio 知识王国](https://github.com/latexstudio/LaTeX-TeXWiki)
- The LaTeX Project - [Useful Links](https://www.latex-project.org/help/links/)
- TeX Users Group - [TeX Resources on the Web](https://www.tug.org/interest.html),
  - [Getting start](https://www.tug.org/begin.html)
