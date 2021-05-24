# ECNUThesis-Undergraduate

[![](https://img.shields.io/badge/Overleaf-ECNUthesis-brightgreen.svg)](https://www.overleaf.com/latex/templates/ecnuthesis-latex-thesis-template-for-east-china-normal-university/szppdtkvgvpk)

> This repository is forked from [Koyamin/ECNUThesis-Undergraduate](https://github.com/Koyamin/ECNUThesis-Undergraduate). I just make some changes to satisfy the latest format requirements. This repo will be outdated soon.

### 华东师范大学本科生学士学位论文模版

本模版使用 LaTeX3 重构了 [YijunYuan](https://github.com/YijunYuan) 的 [ECNU-Undergraduate-LaTeX](https://github.com/YijunYuan/ECNU-Undergraduate-LaTeX)，
并将个人信息的填写、个性化设置、命令、环境等进行了一定的封装，让使用者可以更加方便地使用 LaTeX 进行创作。

## 使用环境

本模版只能使用 XeLaTeX 进行编译，使用其它 LaTeX 引擎将会导致编译失败。所以请安装最新版的 TeX Live ，并使用 XeLaTeX 进行编译。

若您的个人计算机中仍安装了老旧的 CTeX 套装，请毫不犹豫地卸载它，并安装最新版的 TeX Live。

## 编译方法

假设 TeX 源文件为 `thesis.tex`，请在命令行中执行
```
latexmk -xelatex thesis
```
以编译。

## 使用方法

请移步 [Wiki](https://github.com/Koyamin/ECNUThesis-Undergraduate/wiki) 阅读相关文档。

## 不足与改进

本模版仍有一些不足与值得改进之处。已知的不足如下所示。

- 尾注功能未实现；
- ……

## 参考

- Kunth D E. 的 The TeXBook: Computers & Typesetting.
- CTEX.ORG 的 CTeX 宏集手册
- CTEX.ORG 的 xeCJK 宏包
- The LaTeX3 Project 的 The LaTeX3 Sources
- [stone-zeng](https://github.com/stone-zeng) 的 [fduthesis](https://github.com/stone-zeng/fduthesis)
- [YijunYuan](https://github.com/YijunYuan) 的 [ECNU-Undergraduate-LaTeX](https://github.com/YijunYuan/ECNU-Undergraduate-LaTeX)

## 软件许可证

华东师范大学校徽图案 (`inner-cover(contains_font).eps`) 版权归华东师范大学所有。

其他部分使用 LPPL 授权。
