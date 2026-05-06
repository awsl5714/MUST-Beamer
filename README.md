<div align="center">

<br>

# 🎓 MUST Beamer Template

### 澳门科技大学 LaTeX Beamer 演示文稿模板  
### Macau University of Science and Technology Beamer Template

<br>

![LaTeX](https://img.shields.io/badge/LaTeX-Beamer-008080?style=for-the-badge&logo=latex&logoColor=white)
![XeLaTeX](https://img.shields.io/badge/Compile-XeLaTeX-blue?style=for-the-badge)
![MUST](https://img.shields.io/badge/University-MUST-001E62?style=for-the-badge)
![Beginner Friendly](https://img.shields.io/badge/Beginner-Friendly-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/Usage-Academic-orange?style=for-the-badge)

<br>

一个适用于 **课程汇报 / 论文展示 / 学术报告 / 组会汇报 / 毕业答辩预演** 的澳门科技大学风格 Beamer 模板。

</div>

---

## 📌 项目简介

本项目提供了一套 **澳门科技大学风格的 LaTeX Beamer 幻灯片模板**，适合用于：

- 🎤 课程 Presentation
- 📚 论文精读汇报
- 🧪 科研组会展示
- 📝 学术论文复现汇报
- 🎓 毕业设计 / 毕业论文预答辩
- 🧑‍🏫 Seminar / Workshop 分享

模板采用 **深蓝 + 红色强调线 + 校徽元素** 的视觉风格，整体简洁、正式、适合学术场景。

---

## ✨ 模板特色

| 功能 | 说明 |
|---|---|
| 🎨 MUST 风格配色 | 使用澳门科技大学常见的深蓝主色，辅以红色强调线 |
| 🏫 校徽封面 | 支持封面页、章节页、感谢页展示校徽 |
| 🧩 模块化结构 | `main.tex` 作为主文件，各章节放在 `sections/` 中 |
| 📖 中文友好 | 使用 `ctex` 与 `fontspec`，支持中文排版 |
| 📊 学术展示常用组件 | 内置表格、公式、block、列表、参考文献示例 |
| ✅ 新手友好 | 只需要修改标题、作者、章节内容即可快速使用 |
| 📄 PDF 预览 | GitHub 上已经提供编译好的 PDF，下载即可查看效果 |

---

## 👀 在线预览 PDF

如果你只是想先看看模板长什么样，不需要安装 LaTeX。

### 方法一：直接在 GitHub 上预览

在仓库中点击 PDF 文件，例如：

```text
MUST-Beamer-Template.pdf
```

GitHub 通常会自动打开 PDF 预览页面。

### 方法二：下载 PDF 到本地查看

如果 GitHub 预览加载较慢，可以：

1. 点击仓库里的 `MUST-Beamer-Template.pdf`
2. 点击右上角的 **Download**
3. 用浏览器、Adobe Acrobat、Edge、Preview 等 PDF 阅读器打开

> 如果你的 PDF 文件名不是 `MUST-Beamer-Template.pdf`，请点击你仓库中实际上传的 PDF 文件。

---

## 🖼️ 模板效果预览

模板包含以下典型页面：

| 页面类型 | 内容 |
|---|---|
| 🏠 封面页 | 标题、副标题、作者、课程 / 学院、日期、校徽 |
| 📑 目录页 | 自动展示章节结构 |
| 🧭 章节页 | 大面积深蓝切割风格章节过渡 |
| 📄 内容页 | 论文卡片、问题背景、核心思想、模型架构 |
| 🧮 公式页 | 适合展示方法中的核心数学公式 |
| 📊 表格页 | 适合展示实验结果和对比 |
| 🧪 消融实验页 | 展示组件贡献和实验分析 |
| 🖼️ 可视化页 | 放置模型结构图、结果图、热力图等 |
| 🙏 感谢页 | Thank you & Questions |
| 📚 参考文献页 | BibTeX 参考文献展示 |

---

## 📦 下载与解压教程

本模板通常有两种获取方式：

### 方式一：下载 GitHub 仓库

1. 打开本项目 GitHub 页面
2. 点击绿色按钮 **Code**
3. 选择 **Download ZIP**
4. 下载完成后得到一个压缩包，例如：

```text
must-beamer-template-main.zip
```

5. 解压后进入文件夹即可使用

---

### 方式二：下载我上传的模板压缩包

如果仓库中已经提供了 LaTeX Beamer 模板压缩包，例如：

```text
must-beamer-template.zip
```

请按照下面方式解压。

---

## 🧰 如何解压 ZIP 文件？

### 🪟 Windows 用户

#### 方法一：鼠标右键解压

1. 找到下载好的文件：

```text
must-beamer-template.zip
```

2. 鼠标右键点击它
3. 选择：

```text
全部解压 / Extract All
```

4. 选择一个你容易找到的位置，例如桌面
5. 点击 **Extract / 解压**

解压后你应该能看到类似文件夹：

```text
must-beamer-template/
```

---

#### 方法二：PowerShell 命令解压

如果你喜欢命令行，可以在 PowerShell 中运行：

```powershell
Expand-Archive -Path must-beamer-template.zip -DestinationPath .
```

然后进入文件夹：

```powershell
cd must-beamer-template
```

---

### 🍎 macOS 用户

#### 方法一：双击解压

1. 找到下载好的：

```text
must-beamer-template.zip
```

2. 双击它
3. 系统会自动解压出文件夹：

```text
must-beamer-template/
```

---

#### 方法二：终端命令解压

打开 Terminal，进入下载目录，例如：

```bash
cd ~/Downloads
```

解压：

```bash
unzip must-beamer-template.zip
```

进入模板目录：

```bash
cd must-beamer-template
```

---

### 🐧 Linux 用户

打开终端，运行：

```bash
unzip must-beamer-template.zip
```

如果没有安装 `unzip`，可以先安装：

#### Ubuntu / Debian

```bash
sudo apt update
sudo apt install unzip
```

#### Fedora

```bash
sudo dnf install unzip
```

然后进入项目目录：

```bash
cd must-beamer-template
```

---

## 📁 文件结构说明

解压后，你会看到如下结构：

```text
must-beamer-template/
├── main.tex                  ← 主文件，负责组织整份 slides
├── beamerthemeMUST.sty       ← 样式文件：配色、封面、章节页、block 样式等
├── references.bib            ← BibTeX 参考文献数据库
├── README.md                 ← 使用说明文档
├── sections/
│   ├── introduction.tex      ← 引言与背景
│   ├── method.tex            ← 方法部分
│   └── experiment.tex        ← 实验部分
└── figures/
    └── school_logo.png       ← MUST 校徽图片
```

---

## 🚀 新手快速开始

如果你是第一次使用 LaTeX Beamer，可以按下面步骤来。

---

### 第一步：安装 LaTeX 环境

本模板需要使用 **XeLaTeX** 编译。

根据你的系统选择安装：

| 系统 | 推荐安装 |
|---|---|
| 🪟 Windows | [TeX Live](https://www.tug.org/texlive/) 或 [MiKTeX](https://miktex.org/) |
| 🍎 macOS | [MacTeX](https://www.tug.org/mactex/) |
| 🐧 Linux | TeX Live |
| ☁️ 不想安装 | 使用 [Overleaf](https://www.overleaf.com/) |

> 新手如果不想折腾本地环境，推荐直接使用 Overleaf。

---

### 第二步：打开主文件

整个项目最重要的文件是：

```text
main.tex
```

你可以用下面任意编辑器打开：

- VS Code
- TeXstudio
- TeXworks
- Overleaf
- Sublime Text
- Texmaker

---

### 第三步：修改基本信息

打开 `main.tex`，找到类似下面的内容：

```latex
\title{你的论文标题}
\subtitle{副标题（可选）}
\author{作者 A \quad 作者 B}
\institute{课程名称 / 学院名称}
\date{\today}
```

把它改成你的信息，例如：

```latex
\title{基于深度学习的医学图像分类研究}
\subtitle{论文阅读与方法复现汇报}
\author{张三 \quad 李四}
\institute{澳门科技大学 / 计算机科学与工程学院}
\date{2026 年 5 月 6 日}
```

---

### 第四步：修改各章节内容

章节内容放在 `sections/` 文件夹中：

```text
sections/
├── introduction.tex
├── method.tex
└── experiment.tex
```

你可以分别修改：

| 文件 | 用途 |
|---|---|
| `sections/introduction.tex` | 写研究背景、论文动机、问题定义 |
| `sections/method.tex` | 写方法、模型架构、核心公式 |
| `sections/experiment.tex` | 写实验设置、主要结果、消融实验、可视化 |

---

### 第五步：编译 PDF

在项目根目录下运行：

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

编译完成后会生成：

```text
main.pdf
```

这就是你的最终演示文稿。

---

## 🧑‍💻 不同工具的编译方法

### 使用 VS Code

推荐安装插件：

```text
LaTeX Workshop
```

然后：

1. 打开项目文件夹
2. 打开 `main.tex`
3. 使用 `Recipe: xelatex -> bibtex -> xelatex -> xelatex`
4. 编译生成 PDF

如果没有对应 recipe，可以在 VS Code 设置中添加 XeLaTeX 编译链。

---

### 使用 TeXstudio

1. 打开 `main.tex`
2. 点击菜单：

```text
Options / 选项 → Configure TeXstudio / 配置 TeXstudio
```

3. 将默认编译器改为：

```text
XeLaTeX
```

4. 点击绿色运行按钮编译

如果使用参考文献，请按顺序运行：

```text
XeLaTeX → BibTeX → XeLaTeX → XeLaTeX
```

---

### 使用 Overleaf

如果你不想安装任何软件，可以使用 Overleaf。

#### 操作步骤

1. 打开 [Overleaf](https://www.overleaf.com/)
2. 新建项目
3. 选择：

```text
Upload Project
```

4. 上传 `must-beamer-template.zip`
5. 打开项目设置
6. 将 Compiler 改成：

```text
XeLaTeX
```

7. 点击 Recompile

---

## 🧩 常用命令说明

模板提供了一些自定义命令，让你快速创建具有 MUST 风格的页面。

| 命令 | 说明 | 示例 |
|---|---|---|
| `\musttitlepage` | 生成封面页 | `\musttitlepage` |
| `\mustsection{标题}{副标题}` | 生成章节分隔页 | `\mustsection{1. 引言与背景}{Introduction & Motivation}` |
| `\mustthankspage{文字}` | 生成感谢页 | `\mustthankspage{Thank you! \& Questions?}` |
| `\cmark` | 绿色对勾 | `\cmark 做什么` |
| `\xmark` | 红色叉号 | `\xmark 不做什么` |
| `\warn` | 金色警告符号 | `\warn 注意事项` |

---

## 📝 如何新增一页 Slide？

在对应章节文件中，例如 `sections/method.tex`，加入：

```latex
\begin{frame}{模型架构}
    \begin{itemize}
        \item 模块 A：负责特征提取
        \item 模块 B：负责信息融合
        \item 模块 C：负责最终预测
    \end{itemize}
\end{frame}
```

然后重新编译即可。

---

## 📚 如何新增一个章节？

假设你想新增一个“相关工作”章节。

### 第一步：新建文件

在 `sections/` 中新建：

```text
related_work.tex
```

---

### 第二步：写入章节内容

在 `sections/related_work.tex` 中写：

```latex
\mustsection{相关工作}{Related Work}

\begin{frame}{相关工作概览}
    \begin{itemize}
        \item 方向一：传统方法
        \item 方向二：深度学习方法
        \item 方向三：最新大模型方法
    \end{itemize}
\end{frame}
```

---

### 第三步：在 `main.tex` 中引入

找到类似下面的位置：

```latex
\input{sections/introduction}
\input{sections/method}
\input{sections/experiment}
```

加入：

```latex
\input{sections/related_work}
```

例如：

```latex
\input{sections/introduction}
\input{sections/related_work}
\input{sections/method}
\input{sections/experiment}
```

---

## 🖼️ 如何插入图片？

把图片放入 `figures/` 文件夹，例如：

```text
figures/architecture.png
```

然后在 slide 中写：

```latex
\begin{frame}{模型架构}
    \centering
    \includegraphics[width=0.8\linewidth]{figures/architecture.png}
\end{frame}
```

常见图片格式：

- `.png`
- `.jpg`
- `.jpeg`
- `.pdf`

推荐使用高清 `.png` 或矢量 `.pdf`。

---

## 📊 如何插入表格？

示例：

```latex
\begin{frame}{主要结果}
    \centering
    \begin{tabular}{lccc}
        \toprule
        Model & 指标 A & 指标 B & 指标 C \\
        \midrule
        Baseline 1 & 80.1 & 75.3 & 78.2 \\
        Baseline 2 & 82.4 & 77.5 & 80.0 \\
        Ours       & 86.7 & 81.2 & 84.9 \\
        \bottomrule
    \end{tabular}
\end{frame}
```

> 如果使用 `\toprule`、`\midrule`、`\bottomrule`，需要确保导言区已经加载 `booktabs` 包。

---

## 🧮 如何插入公式？

示例：

```latex
\begin{frame}{核心公式}
    \[
        \mathcal{L}
        =
        \sum_{i=1}^{N}
        \ell(f(x_i; \theta), y_i)
        +
        \lambda \|\theta\|^2
    \]

    \begin{itemize}
        \item 第一项：数据拟合损失
        \item 第二项：正则化项
    \end{itemize}
\end{frame}
```

---

## 📚 如何添加参考文献？

参考文献信息写在：

```text
references.bib
```

例如：

```bibtex
@article{vaswani2017attention,
  title={Attention Is All You Need},
  author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki},
  journal={Advances in Neural Information Processing Systems},
  year={2017}
}
```

在正文中引用：

```latex
\cite{vaswani2017attention}
```

然后按照下面顺序编译：

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

---

## 🎨 配色说明

模板中定义了以下颜色：

| 颜色名 | 色值 | 用途 |
|---|---|---|
| `mustblue` | `#001E62` | 主色，深蓝 |
| `mustred` | `#D50032` | 强调色，红色 |
| `mustteal` | `#1E83A0` | 青色辅助色 |
| `mustgold` | `#F2A900` | 金色，用于提示或强调 |
| `mustgray` | `#53565A` | 灰色文字 |

如果想修改颜色，请打开：

```text
beamerthemeMUST.sty
```

找到类似内容：

```latex
\definecolor{mustblue}{HTML}{001E62}
\definecolor{mustred}{HTML}{D50032}
\definecolor{mustteal}{HTML}{1E83A0}
\definecolor{mustgold}{HTML}{F2A900}
\definecolor{mustgray}{HTML}{53565A}
```

修改对应的 HTML 色值即可。

---

## 🏫 如何更换 Logo？

默认校徽路径为：

```text
figures/school_logo.png
```

如果你想更换 Logo，有两种方法。

---

### 方法一：直接替换图片

把你的新 Logo 命名为：

```text
school_logo.png
```

然后替换：

```text
figures/school_logo.png
```

这是最简单的方法。

---

### 方法二：修改样式文件中的路径

打开：

```text
beamerthemeMUST.sty
```

找到 Logo 路径定义，例如：

```latex
\newcommand{\mustlogo}{figures/school_logo.png}
```

改成你的图片路径：

```latex
\newcommand{\mustlogo}{figures/my_logo.png}
```

---

## 🧱 如何修改封面？

封面页通常由下面命令生成：

```latex
\musttitlepage
```

你只需要在 `main.tex` 中修改标题、作者、学院、日期即可。

例如：

```latex
\title{你的论文标题}
\subtitle{副标题（可选）}
\author{作者 A \quad 作者 B}
\institute{课程名称 / 学院名称}
\date{2026 年 5 月 6 日}
```

如果想深度修改封面布局，需要编辑：

```text
beamerthemeMUST.sty
```

---

## 🗂️ 推荐写作流程

对于新手，推荐按照下面顺序完成 slides：

```text
1. 先改 main.tex 中的标题、作者、日期
2. 再修改 introduction.tex，写研究背景
3. 然后修改 method.tex，写方法和公式
4. 再修改 experiment.tex，写实验和结果
5. 最后检查参考文献 references.bib
6. 编译生成 PDF
7. 检查排版、图片和页码
```

---

## ✅ 新手检查清单

在提交或展示前，建议检查：

- [ ] 标题是否正确
- [ ] 作者姓名是否正确
- [ ] 课程 / 学院信息是否正确
- [ ] 日期是否正确
- [ ] PDF 是否能正常打开
- [ ] 图片是否全部显示
- [ ] 表格是否超出页面
- [ ] 公式是否显示正常
- [ ] 参考文献是否成功生成
- [ ] 页码是否正常
- [ ] 是否还有“XXX”“数值”“描述”等占位文字
- [ ] 是否使用 `XeLaTeX` 编译

---

## 🛠️ 常见问题 FAQ
<summary>❓ 为什么一定要用 XeLaTeX？</summary>

因为模板使用了中文支持和字体设置，例如：

```latex
ctex
fontspec
```

这些内容需要使用 `XeLaTeX` 编译。如果使用 `pdfLaTeX`，很可能会出现中文乱码或字体报错。


---


<summary>❓ 编译后中文乱码怎么办？</summary>

请确认你使用的是：

```text
XeLaTeX
```

而不是：

```text
pdfLaTeX
```

如果仍然乱码，请检查你的 LaTeX 发行版是否完整安装了中文字体支持。



---


    
<summary>❓ 为什么图片显示不出来？</summary>

请检查：

1. 图片是否真的放在 `figures/` 文件夹中
2. 文件名是否写对
3. 后缀是否一致，例如 `.png` 不要写成 `.jpg`
4. 路径中不要使用中文或空格

例如：

```latex
\includegraphics{figures/school_logo.png}
```



---


    
<summary>❓ 为什么参考文献不显示？</summary>

请确认你已经运行了完整编译流程：

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

如果只运行一次 `xelatex`，参考文献通常不会完整显示。



---


    
<summary>❓ 表格太宽超出页面怎么办？</summary>

可以缩小表格：

```latex
\resizebox{\linewidth}{!}{
\begin{tabular}{lccc}
    \toprule
    Model & 指标 A & 指标 B & 指标 C \\
    \midrule
    Baseline & 80.1 & 75.3 & 78.2 \\
    Ours & 86.7 & 81.2 & 84.9 \\
    \bottomrule
\end{tabular}
}
```



---


    
<summary>❓ Overleaf 编译失败怎么办？</summary>

请检查：

1. 是否把编译器改成了 `XeLaTeX`
2. 是否上传了完整项目，而不是只上传 `main.tex`
3. 是否包含 `beamerthemeMUST.sty`
4. 是否包含 `figures/school_logo.png`
5. 是否包含 `sections/` 文件夹



---


    
<summary>❓ 我只想快速改成自己的汇报，需要改哪些地方？</summary>

最少只需要改：

```text
main.tex
sections/introduction.tex
sections/method.tex
sections/experiment.tex
```

如果不改样式，不需要动：

```text
beamerthemeMUST.sty
```



---

## 🔧 高级自定义

如果你已经熟悉 LaTeX，可以进一步修改：

| 目标 | 修改位置 |
|---|---|
| 修改主题颜色 | `beamerthemeMUST.sty` |
| 修改封面布局 | `beamerthemeMUST.sty` |
| 修改章节页样式 | `beamerthemeMUST.sty` |
| 修改页眉页脚 | `beamerthemeMUST.sty` |
| 修改 block 样式 | `beamerthemeMUST.sty` |
| 添加新的章节文件 | `sections/` |
| 添加图片资源 | `figures/` |

---

## 🧪 示例页面内容

当前模板中包含了一个完整的论文汇报结构：

```text
1. 引言与背景
   - 论文卡片
   - 问题背景
   - 研究动机

2. 方法
   - 核心思想
   - 模型架构
   - 核心公式
   - 其他组件

3. 实验
   - 实验设置
   - 主要结果
   - 消融实验
   - 可视化结果

4. 总结与展望
   - Take-aways
   - Thank you
   - References
```

你可以直接把占位内容替换成自己的论文内容。

---

## 📌 适合谁使用？

这个模板特别适合：

- 👶 LaTeX 新手
- 🎓 澳门科技大学学生
- 📚 需要做论文汇报的同学
- 🧪 需要做科研组会的研究生
- 🧑‍🏫 需要制作课程 slides 的同学
- 💻 想要一个简洁学术风 Beamer 模板的人

---

## ⚠️ 注意事项

- 请使用 `XeLaTeX` 编译
- 不建议使用 `pdfLaTeX`
- 图片路径尽量不要包含中文和空格
- 如果修改了 `.bib` 文件，请记得运行 `bibtex`
- 如果上传到 Overleaf，请上传完整 ZIP 项目
- 如果 PDF 没有更新，可以尝试删除辅助文件后重新编译

常见辅助文件包括：

```text
.aux
.bbl
.blg
.log
.nav
.out
.snm
.toc
```

这些文件不是源代码，删除后重新编译会自动生成。

---

## 📄 License / 使用说明

本模板主要用于学习、课程展示和学术交流。

如果你使用了学校校徽或相关视觉元素，请遵守澳门科技大学相关标识使用规范。

> 本项目不代表澳门科技大学官方发布，仅作为 LaTeX Beamer 模板学习与交流用途。

---

## 🙌 致谢

感谢 LaTeX、Beamer、CTeX 等开源项目提供的排版能力。

如果这个模板对你有帮助，欢迎：

- ⭐ Star 这个仓库
- 🍴 Fork 后改成自己的版本
- 🐛 提 Issue 反馈问题
- 📢 推荐给需要做 slides 的同学

---
