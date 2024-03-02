<style>
.bjimg{
  position: fixed;
  top: 0;
  left: 0;
  width:100%;
height:100%;
min-width: 1000px;
z-index:-10;
zoom: 1;
  background-image: url();
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center 0;
  opacity: 0.3;
  }
</style>
<head>
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>
<div class="bjimg"></div>

# 问题有不小进展并且武汉终于天晴了所以完成上篇杂记的练习同时高呼三声Oscillatory Integrals万岁

<font size="2" color="grey">发布于2024.3.2</font><br/>
我们在上一篇[杂记](https://senyuyangpdelearner.github.io/blog3)中留下一道最小数原理(良序原理)的练习，现在来证明它.

> **定理.** 每个自然数都可以分解为有限个素数的乘积(质因数分解的存在性).

*证明*. 用反证法. 假设所有不能分解为有限个素数乘积的自然数构成的集合$A\subset\mathbb{N}$非空，根据最小数原理存在$A$中的最小数$n$. 首先$n$不是素数，存在$a,b\in \mathbb{N}, a,b\neq 1$使得$n=ab$. 自然$a<n, b<n$，所以$a,b\notin A$，所以$a,b$可分解为有限个素数的乘积，那么$n=ab$也可以分解为有限个素数的乘积，与假设矛盾！因此定理成立.    $\Box$

还可以依葫芦画瓢用最小数原理证明数学归纳法.

> **定理.** 最小数原理$\Rightarrow$数学归纳法

*证明*. 用反证法. 任给一个满足归纳假设的关于自然数的命题$P(n)$：
- $P(1)$为真；
- $P(n)$为真$\Rightarrow$ $P(n+1)$为真.
假设所有使$P(n)$不真的自然数构成的集合$C$非空，根据最小数原理存在$C$中的最小数$n$. 首先$1\notin C$，所以$n>1$,，$n-1\in\mathbb{N}$. 由于$P(n-1)$为真，由归纳假设$P(n)$为真，这与假设矛盾！所以数学归纳法成立.    $\Box$

<font size="2">Oscillatory Integrals万岁！Oscillatory Integrals万岁！Oscillatory Integrals万岁！(捧读)</font>

<br/>
[少女祈祷中…](https://senyuyangpdelearner.github.io)
