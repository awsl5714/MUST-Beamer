# MUST Beamer 模版

澳门科技大学 (Macau University of Science and Technology) Beamer 演示文稿模版。

## 文件结构

```
must-beamer-template/
├── main.tex                  % 主文件
├── beamerthemeMUST.sty       % 主题样式文件
├── references.bib            % 参考文献
├── README.md
├── sections/
│   ├── introduction.tex      % 引言与背景
│   ├── method.tex            % 方法
│   └── experiment.tex        % 实验
└── figures/
    └── school_logo.png       % 校徽 logo
```

## 编译方法

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

> **注意**：必须使用 `xelatex` 编译（因为使用了 `ctex` 中文支持和 `fontspec`）。

## 可用命令

| 命令 | 说明 | 用法 |
|------|------|------|
| `\musttitlepage` | 封面页（对角切割风格） | 直接调用 |
| `\mustsection{标题}{副标题}` | 章节分隔页 | 两个参数 |
| `\mustthankspage{文字}` | 结尾感谢页 | 一个参数 |
| `\cmark` | 绿色 ✓ | 行内使用 |
| `\xmark` | 红色 ✗ | 行内使用 |
| `\warn` | 金色 △ | 行内使用 |

## 配色

| 颜色名 | 色值 | 用途 |
|--------|------|------|
| `mustblue` | `#001E62` | 主色（深蓝） |
| `mustred` | `#D50032` | 辅色（红） |
| `mustteal` | `#1E83A0` | 示例色（青） |
| `mustgold` | `#F2A900` | 金色 |
| `mustgray` | `#53565A` | 灰色文字 |

## 自定义

- **更换 Logo**：替换 `figures/school_logo.png`，并在 `.sty` 中修改 `\mustlogo` 路径
- **修改配色**：在 `.sty` 中修改 `\definecolor` 定义
- **添加章节**：在 `sections/` 下新建 `.tex` 文件，在 `main.tex` 中用 `\input` 引入
