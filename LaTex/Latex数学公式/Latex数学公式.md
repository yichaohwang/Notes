---
title: Latex数学公式
date: 2022-06-17 22:44:51
tags: LaTex
categories: 
- IT
- LaTex
---

## 排版数学公式

## 4.1 AMS宏集

> 美国数学学会（American Mathematical Society)提供的对LATEX原生的数学公式排版的扩展

- 核心：amsmath宏包

 > 支持多行公式的排版

- 拓展1：amsfonts宏包及基于amsfonts的amssymb宏包

 > 提供丰富的数学符号

- 拓展2：amsthm宏包

 > 扩展了LATEX定理证明格式

## 4.2 公式排版基础

数学公式有两种排版方式：

- 行内公式：

  ```latex
  Add $a$ squared and $b$ squared to get $c$ squared. Or, using a more mathematical approach:$a^2+b^2=c^2$
  ```

  | Add $a$ squared and $b$ squared to get $c$ squared. Or, using a more mathematical approach:$a^2+b^2=c^2$ |
  | ------------------------------------------------------------ |
  |                                                              |

- 行间公式：
  
  ```latex
  Add $a$ squared and $b$ squared to get $c$ squared
  \begin{equation}
  a^2+b^2= c^2
  \end{equation}
  Einstein says
  \begin{equation}
  E=mc^2\label{clever}
  \end{equation}
  This is a reference to 
  \eqref{clever}.

  ```
  
  演示：
