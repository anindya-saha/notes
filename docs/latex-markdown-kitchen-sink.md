---
layout: default
title: Latex MathJax Markdown Cheatsheet
nav_order: 100
---

Description
===========

Cheatsheet for LaTex, using Markdown for markup. 

To enable $$\LaTeX{}$$ in Jekyll follow this [tutorial](https://quuxplusone.github.io/blog/2018/08/05/mathjax-in-jekyll/).

Further Reference and source: ftp://ftp.ams.org/pub/tex/doc/amsmath/short-math-guide.pdf

For inline expression use either `\\( 1/x^{2} \\)` which will render to \\( 1/x^{2} \\) or use `$$ 1/x^{2} $$` which also renders to $$ 1/x^{2} $$.

For block expression use `\\[ \frac{1}{n^{2}} \\]` or `$$ a * b = c ^ b $$` in a new line.

\\[ \frac{1}{n^{2}} \\]

$$ a * b = c ^ b $$


Sample Sentence  
... a given wire happens to be carrying $$\lvert 0\rangle$$. By that we mean that it's carrying the linear combination
$$\begin{pmatrix} 1 \\ 0 \end{pmatrix}$$...



Example expressions / functions
===============================

Input                           | Rendered                      |
:-------------------------------|:------------------------------|
`$$ a = b + c − d $$`           | $$ a = b + c − d$$            |
`$$ \sqrt{?\frac{\pi}{2}} $$`   | $$ \sqrt{\frac{\pi}{2}} $$    |
`$$ y = a x_1^2 + b x_2 + c $$` | $$ y = a x_1^2 + b x_2 + c $$ |
`$$ a * b = c ^ b $$`           | $$ a * b = c ^ b $$           |
`$$ 2^{\frac{n-1}{3}} $$`       | $$ 2^{\frac{n-1}{3}}$$        |
`$$ \int_{a}^b f(x)dx $$`       | $$ \int_{a}^b f(x)dx $$       |

Example LateX Derivatives, Limits, Sums, Products and Integrals
===============================================================

Partial firt order derivative `$$\frac{\partial f}{\partial x}$$` : $$\frac{\partial f}{\partial x}$$

Limit at plus infinity `$$\lim_{x \to +\infty} f(x)$$` : $$\lim_{x \to +\infty} f(x)$$

Sum off n first integers `$$\sum_{i=1}^n i^2 = \frac{n(n+1)(2n+1)}{6}$$` : $$\sum_{i=1}^n i^2 = \frac{n(n+1)(2n+1)}{6}$$

Product with limits	`$$\prod\limits_{j=1}^k A_{\alpha_j}$$` : $$\prod\limits_{j=1}^k A_{\alpha_j}$$

Integral limits	`$$\int_{a}^b f(x)dx$$` : $$\int_{a}^b f(x)dx$$

For more on [LateX Derivatives, Limits, Sums, Products and Integrals](
https://math-linux.com/latex-26/faq/latex-faq/article/latex-derivatives-limits-sums-products-and-integrals).

Example Matrices
================

Create a matrix without brackets:
`$$\begin{matrix} a & b \\ c & d \end{matrix}$$` : $$\begin{matrix} a & b \\ c & d \end{matrix}$$

Create a matrix with round brackets: `$$\begin{pmatrix} a & b \\ c & d \end{pmatrix}$$` : $$\begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

Create a matrix with square brackets: `$$\begin{bmatrix} 1 & 2 & 1 \\ 3 & 0 & 1 \\ 0 & 2 & 4 \end{bmatrix}$$` :
$$\begin{bmatrix} 1 & 2 & 1 \\ 3 & 0 & 1 \\ 0 & 2 & 4 \end{bmatrix}$$

Use `\left` and `\right` to enclose an arbitrary expression in brackets: `$$\left( \frac{p}{q} \right)$$` :
$$\left( \frac{p}{q} \right)$$

For more on [LateX Matrices](
https://www.math.ubc.ca/~pwalls/math-python/jupyter/latex/).

Special characters / Symbols
============================
### Latin:
##### No dot:

`$$\imath$$` $$\rightarrow$$ $$\imath$$  
`$$\jmath$$` $$\rightarrow$$ $$\jmath$$  

##### Hat:  
`$$\hat{\imath}$$`  $$\rightarrow$$ $$\hat{\imath}$$  
`$$\hat{\jmath}$$`  $$\rightarrow$$ $$\hat{\jmath}$$  

### Greek Letters:
#### Capital:

LaTex         |             |LaTex       |          |
:-------------|:------------|:-----------|:---------|
`$$\Gamma$$`  | $$\Gamma$$  |`$$\Delta$$`|$$\Delta$$|
`$$\Lambda$$` | $$\Lambda$$ |`$$\Phi$$`  |$$\Phi$$  |
`$$\Pi$$`     | $$\Pi$$     |`$$\Psi$$`  |$$\Psi$$  |
`$$\Sigma$$`  | $$\Sigma$$  |`$$\Theta$$`|$$\Theta$$|
`$$\Upsilon$$`| $$\Upsilon$$|`$$\Xi$$`   |$$\Xi$$   |
`$$\Omega$$`  | $$\Omega$$  |            |          |

#### Lowercase:

LaTex          |             | LaTex       |           |
:--------------|:------------|:------------|:----------|
`$$\alpha$$`   | $$\alpha$$  |`$$\nu$$`    |$$\nu$$    |
`$$\beta$$`    | $$\beta$$   |`$$\kappa$$` |$$\kappa$$ |
`$$\gamma$$`   | $$\gamma$$  |`$$\lambda$$`|$$\lambda$$|
`$$\delta$$`   | $$\delta$$  |`$$\mu$$`    |$$\mu$$    |    
`$$\epsilon`   | $$\epsilon$$|`$$\zeta$$`  |$$\zeta$$  |
`$$\eta$$`     | $$\eta$$    |`$$\theta$$` |$$\theta$$ |
`$$\iota$$`    | $$\iota$$   |`$$\xi$$`    |$$\xi$$    |
`$$\pi$$`      | $$\pi$$     |`$$\rho$$`   |$$\rho$$   |
`$$\sigma$$`   | $$\sigma$$  |`$$\tau$$`   |$$\tau$$   |
`$$\upsilon$$` | $$\upsilon$$|`$$\phi$$`   |$$\phi$$   |
`$$\chi$$`     | $$\chi$$    |`$$\psi$$`   |$$\psi$$   |
`$$\omega$$`   | $$\omega$$  |             |           |

#### Other:

LaTex          |             | LaTex           |               |
:--------------|:------------|:----------------|:--------------|
`$$\digamma$$` |$$\digamma$$ |`$$\varepsilon$$`|$$\varepsilon$$|
`$$\varkappa$$`|$$\varkappa$$|`$$\varphi$$`    |$$\varphi$$    |
`$$\varpi$$`   |$$\varpi$$   |`$$\varrho$$`    |$$\varrho$$    |
`$$\varsigma$$`|$$\varsigma$$|`$$\vartheta$$`  |$$\vartheta$$  |
`$$\eth$$`     |$$\eth$$     |`$$\hbar$$`      |$$\hbar$$      |


### Other:
#### Other Symbols

LaTex         |            | LaTex              |                  |
:-------------|:-----------|:-------------------|:-----------------|
`$$\partial$$`|$$\partial$$|`$$\infty$$`        |$$\infty$$        |
`$$\wedge$$`  |$$\wedge$$  |`$$\vee$$`          |$$\vee$$          |
`$$\neg$$`    |$$\neg$$    |`$$\not$$`          |$$\not$$          |
`$$\bot$$`    |$$\bot$$    |`$$\top$$`          |$$\top$$          |
`$$\nabla$$`  |$$\nabla$$  |`$$\varnothing$$`   |$$\varnothing$$   |
`$$\angle$$`  |$$\angle$$  |`$$\measuredangle$$`|$$\measuredangle$$|
`$$\surd$$`   |$$\surd$$   |`$$\forall$$`       |$$\forall$$       |
`$$\exists$$` |$$\exists$$ |`$$\nexists$$`      |$$\nexists$$      |

#### Relational Symbols

LaTex                |                   | LaTex               |                   |
:--------------------|:------------------|:--------------------|:------------------|
`$$\hookrightarrow$$`|$$\hookrightarrow$$|`$$\Rightarrow$$`    |$$\Rightarrow$$    |
`$$\rightarrow$$`    |$$\rightarrow$$    |`$$\Leftrightarrow$$`|$$\Leftrightarrow$$|
`$$\nrightarrow$$`   |$$\nrightarrow$$   |`$$\mapsto$$`        |$$\mapsto$$        |
`$$\geq$$`           |$$\geq$$           |`$$\leq$$`           |$$\leq$$           |
`$$\equiv$$`         |$$\equiv$$         |`$$\sim$$`           |$$\sim$$           |
`$$\gg$$`            |$$\gg$$            |`$$\ll$$`            |$$\ll$$            |
`$$\subset$$`        |$$\subset$$        |`$$\subseteq$$`      |$$\subseteq$$      |
`$$\in$$`            |$$\in$$            |`$$\notin$$`         |$$\notin$$         |
`$$\mid$$`           |$$\mid$$           |`$$\propto$$`        |$$\propto$$        |
`$$\perp$$`          |$$\perp$$          |`$$\parallel$$`      |$$\parallel$$      |
`$$\vartriangle$$`   |$$\vartriangle$$   |

#### Binary operators

LaTex       |          | LaTex    |        |
:-----------|:---------|:---------|:-------|
`$$\wedge$$`|$$\wedge$$|`$$\vee$$`|$$\vee$$|
`$$\neg$$`  |$$\neg$$  |`$$\not$$`|$$\not$$|

#### Cumulative operators

LaTex        |             | LaTex         |             |
:------------|:------------|:--------------|:------------|
`$$\int$$`   |`$$\int$$`   |`$$\iint$$`    |$$\iint$$    |
`$$\iiint$$` |`$$\iiint$$` |`$$\idotsint$$`|$$\idotsint$$|
`$$\prod$$`  |`$$\prod$$`  |`$$\sum$$`     |$$\sum$$     |
`$$\bigcup$$`|`$$\bigcup$$`|`$$\bigcap$$`  |$$\bigcap$$  |

#### Named operators  
`$$\arccos$$` $$\rightarrow$$ $$\arccos$$  
`$$\arcsin$$` $$\rightarrow$$ $$\arcsin$$  
`$$\arctan$$` $$\rightarrow$$ $$\arctan$$  
`$$\arg$$` $$\rightarrow$$ $$\arg$$  
`$$\cos$$` $$\rightarrow$$ $$\cos$$  
`$$\cosh$$` $$\rightarrow$$ $$\cosh$$  
`$$\cot$$` $$\rightarrow$$ $$\cot$$  
`$$\coth$$` $$\rightarrow$$ $$\coth$$  
`$$\deg$$` $$\rightarrow$$ $$\deg$$  
`$$\det$$` $$\rightarrow$$ $$\det$$  
`$$\dim$$` $$\rightarrow$$ $$\dim$$  
`$$\exp$$` $$\rightarrow$$ $$\exp$$  
`$$\gcd$$` $$\rightarrow$$ $$\gcd$$  
`$$\hom$$` $$\rightarrow$$ $$\hom$$  
`$$\inf$$` $$\rightarrow$$ $$\inf$$  
`$$\injlim$$` $$\rightarrow$$ $$\injlim$$  
`$$\lg$$` $$\rightarrow$$ $$\lg$$  
`$$\lim$$` $$\rightarrow$$ $$\lim$$  
`$$\liminf$$` $$\rightarrow$$ $$\liminf$$  
`$$\limsup$$` $$\rightarrow$$ $$\limsup$$  
`$$\ln$$` $$\rightarrow$$ $$\ln$$  
`$$\log$$` $$\rightarrow$$ $$\log$$  
`$$\max$$` $$\rightarrow$$ $$\max$$  
`$$\min$$` $$\rightarrow$$ $$\min$$  
`$$\Pr$$` $$\rightarrow$$ $$\Pr$$  
`$$\projlim$$` $$\rightarrow$$ $$\projlim$$  
`$$\sec$$` $$\rightarrow$$ $$\sec$$  
`$$\sin$$` $$\rightarrow$$ $$\sin$$  
`$$\sinh$$` $$\rightarrow$$ $$\sinh$$  
`$$\sup$$` $$\rightarrow$$ $$\sup$$  
