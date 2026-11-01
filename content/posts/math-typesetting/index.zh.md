+++
title = "把数学写清楚：公式排版示例"
date = 2026-11-01T08:00:00+08:00
description = "从行内公式到矩阵，看看数学在这里的呈现方式。"
categories = ["数学"]
tags = ["LaTeX", "写作"]
math = true
toc = true
example = true
+++

## 行内与独立公式

勾股定理写作 $a^2+b^2=c^2$。独立公式可以单独占一行：

$$
\int_0^1 x^2\,dx=\frac{1}{3}.
$$

## 一个简短推导

对任意正整数 $n$，有：

$$
\sum_{k=1}^{n} k=\frac{n(n+1)}{2}.
$$

将序列正向和反向相加，每一对的和都是 $n+1$，共 $n$ 对，再除以二即可。

## 矩阵与多行公式

$$
A=\begin{pmatrix}1&2\\3&4\end{pmatrix},\qquad \det A=-2.
$$

$$
\begin{aligned}
(a+b)^2 &= (a+b)(a+b)\\
&=a^2+2ab+b^2.
\end{aligned}
$$

## 写作提示

在文章开头设置 `math = true`，即可启用数学公式。仅加载本地公式资源；不依赖外部字体服务。

