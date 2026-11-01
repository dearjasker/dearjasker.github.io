+++
title = "Writing mathematics clearly"
date = 2026-11-01T08:00:00+08:00
description = "From inline equations to matrices: a small typesetting specimen."
categories = ["Mathematics"]
tags = ["LaTeX", "Writing"]
math = true
toc = true
example = true
+++

## Inline and display mathematics

The Pythagorean theorem reads $a^2+b^2=c^2$. Display equations get their own line:

$$
\int_0^1 x^2\,dx=\frac{1}{3}.
$$

## A short derivation

For every positive integer $n$:

$$
\sum_{k=1}^{n} k=\frac{n(n+1)}{2}.
$$

Pair the sequence with its reverse. Each pair sums to $n+1$; there are $n$ pairs, and dividing by two gives the result.

## Matrices and aligned equations

$$
A=\begin{pmatrix}1&2\\3&4\end{pmatrix},\qquad \det A=-2.
$$

$$
\begin{aligned}
(a+b)^2 &= (a+b)(a+b)\\
&=a^2+2ab+b^2.
\end{aligned}
$$

## Writing tip

Set `math = true` at the top of an article to enable mathematical notation. Math resources are served locally.

