Scroll down for the English version of README.

`THUquarto`是`Tsinghua University`和`Quarto`的缩写，它是一个基于 LaTeX 和 Quarto开发的清华大学学位论文Quarto模板，包括本科综合论文训练、硕士论文、博士论文以及博士后出站报告。它旨在让用户能够使用语法简单的类markdown文档（Quarto）来实现调用 LaTeX 进行复杂的文件编译。`THUquarto`亦被封装在[`drhutools`](https://sammo3182.github.io/software/drhutools/)软件包中，用户可借助`drhutools::THUquarto()`进行下载使用。

**需要特别强调的是**，本软件包是基于[ThuThesis](https://github.com/tuna/thuthesis)开发的Quarto版本，因此其亦可被视作其拓展包。
`THUquarto`的**主要** LaTeX 代码来自于**ThuThesis**宏包开发者的贡献，`THUquarto`在[LaTeX项目公共许可证 v1.3c](https://www.latex-project.org/lppl/lppl-1-3c/)的授权使用范围内使用**ThuThesis**宏包的内容。

请在[LaTeX项目公共许可证 v1.3c](https://www.latex-project.org/lppl/lppl-1-3c/)的使用许可范围内使用`THUquarto`。

# 下载

`THUquarto`是一个基于 LaTeX 和 Quarto开发的清华大学学位论文Quarto模板，因此其使用需要下载`THUquarto`核心软件包，亦需要恰当安装 LaTeX 、Quarto和ThuThesis等支持项目

## 核心软件包

本节提供了**开发版**和**发布版**下载路径。

- 开发版

  - [GitHub Releases](https://github.com/syfyufei)

- 发布版

  - [CRAN]()

  - [`drhutools`](https://sammo3182.github.io/software/drhutools/)

## 支持项目

### LaTeX 发行版

本文提供两种不同的 LaTeX 发行版选项，用户可以根据自身需求选择安装

- **`TinyTeX`**。TinyTeX是一个瘦身版的TeX Live，用户可以参考其主页的[支持文档](https://yihui.org/tinytex/)自行安装。需要强调的是，因为`THUquarto`和ThuThesis中包含大量宏包的调用，因此安装`TinyTeX`的用户在享受其便捷的同时，亦需要在安装第三方宏包上伤脑筋，尤其是无法通过`tlmgr`安装的宏包。对于这些包，请参见[此issue](https://github.com/rstudio/tinytex/issues/126#issuecomment-503020154)
                                                                                                                    - **`TexLive`**。用户亦可通过[Texlive主页](https://tug.org/texlive/)安装完整版的`TexLive`。

### Quarto

Quarto是一套开源的科技出版系统。
它使得用户能够使用Jupyter、Python、R、Julia和Observable创作HTML、PDF、MS Word、ePub等格式的可复制、高质量的文章、演示文稿、网站、博客和书籍。
Quarto是`THUquarto`必须项，请参考[Quarto支持页面](https://quarto.org/docs/get-started/)进行安装。

### ThuThesis

[ThuThesis](https://github.com/tuna/thuthesis)一个简单易用的清华大学学位论文 LaTeX 模板，`THUquarto`的主体 LaTeX 代码来自ThuThesis。请参考[ThuThesis的Github项目主页](https://github.com/tuna/thuthesis#readme)进行安装。

***

`THUquarto` is an abbreviation for `Tsinghua University` and `markdown`. It is a Quarto template for Tsinghua University academic theses developed using LaTeX and Quarto, covering undergraduate comprehensive training papers, master's theses, doctoral dissertations, and postdoctoral station reports. The package aims to allow users to utilize the simple syntax of Quarto-like markdown documents to harness the power of LaTeX for sophisticated document compilation. `THUquarto` is also encapsulated in the [`drhutools`](https://sammo3182.github.io/software/drhutools/) package, which users can utilize via `drhutools::THUquarto()` for downloading and use.

**It's imperative to note** that this package is a Quarto version developed based on [ThuThesis](https://github.com/tuna/thuthesis), and thus it can also be regarded as an extension of it. The **primary** LaTeX code for `THUquarto` originates from the contributions of the **ThuThesis** package developers. `THUquarto` utilizes the content of the **ThuThesis** package within the scope of authorization provided by the [LaTeX Project Public License v1.3c](https://www.latex-project.org/lppl/lppl-1-3c/).

Kindly use `THUquarto` in compliance with the terms set by the [LaTeX Project Public License v1.3c](https://www.latex-project.org/lppl/lppl-1-3c/).

# Download

As `THUquarto` is a Quarto template for Tsinghua University academic theses developed with LaTeX and Quarto, it requires downloading the core `THUquarto` package and properly installing supporting projects like LaTeX, Quarto, and ThuThesis.

## Core Package

This section provides the download paths for both **development** and **release** versions.

* Development Version:
    
    * [GitHub Releases](https://github.com/syfyufei)
* Release Version:

    * CRAN
    * [`drhutools`](https://sammo3182.github.io/software/drhutools/)

## Supporting Projects

### LaTeX Distributions

Two distinct LaTeX distributions are provided for users to choose from based on their requirements:

* **`TinyTeX`**: A lightweight version of TeX Live. Users can refer to its official [documentation](https://yihui.org/tinytex/) for installation. It's crucial to highlight that due to the extensive macro package usage in `THUquarto` and ThuThesis, while `TinyTeX` offers convenience, users might face challenges installing third-party macro packages, especially those not installable via `tlmgr`. For such packages, refer to [this issue](https://github.com/rstudio/tinytex/issues/126#issuecomment-503020154).
    
* **`TexLive`**: Users can also opt for a full version of `TexLive` available on the [Texlive homepage](https://tug.org/texlive/).
    

### Quarto

Quarto is an open-source scientific publishing system. It empowers users to craft reproducible, high-quality documents, presentations, websites, blogs, and books in formats like HTML, PDF, MS Word, ePub, etc., using Jupyter, Python, R, Julia, and Observable. Quarto is essential for `THUquarto`. For installation, refer to the [Quarto support page](https://quarto.org/docs/get-started/).

### ThuThesis

[ThuThesis](https://github.com/tuna/thuthesis) is an intuitive LaTeX template for academic theses at Tsinghua University. Since the main LaTeX code for `THUquarto` originates from ThuThesis, it is crucial. Kindly consult [ThuThesis's Github project homepage](https://github.com/tuna/thuthesis#readme) for installation details.
                                                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                                                    
