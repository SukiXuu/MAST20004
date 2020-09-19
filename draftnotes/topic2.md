# Topic02-Univariate Distribution

## Discrete Random Variables

* State Space $S\_X$

  The set of possible values S\_X is **countable**

  =&gt; X **can only take countable number** of values

  就是所有可能的函数值

## Probability Mass Function $P\_X\(x\)$

若X is a Discrete Random Variables, 它的 $P\_X\(x\) = P\(X = x\)$

> e.g. Dice Two Fair Coin P\(2\) = P\(X=2\) = P\({1,1}\) = 1/36 P\(3\) = P\(X=3\) = P\({1,2}, {2,1}\) = 2/36 = 1/18
>
> * Theorem
> * P\_X\(x\) ≥ 0, ∀ X
> * 所有S\_X的probability之和=1
> * Distribution Function
>
>   F\_X\(x\) = P\(X≤x\), ∀ x∊ℝ

## Cumulative Distribution Function\(Cdf\)

> e.g. Dice a Fair Coin $ S\_X = {1,2,3,4,5,6}\ P\_X\(x\) = 1/6, x = 1,2,3,4,5,6\ \begin{align_} \quad&F\_X\(x\) = \begin{cases} 0\quad\quad\quad\quad x&lt;1\ 1/6 \quad 1≤x&lt;2\ 2/6 \quad 2≤x&lt;3\ 3/6 \quad 3≤x&lt;4\ 4/6 \quad 4≤x&lt;5\ 5/6 \quad 5≤x&lt;6\ \end{cases} \end{align_} $
>
> * Probability Distribution Function
> * 0≤F\_X\(x\)≤1
> * P\(a&lt;X≤b\) = F\(b\)-F\(a\), a &lt; b
> * F\_X is non-decreasing
> * F\_X\(-∞\) = 0, F\_X\(∞\) = 1
> * F_X is Continuous from the right =&gt; $lim_\(n-&gt;0^+\)F\_X\(x+h\) = F\_X\(x\)$
> * P\(X=x\) is the jump in F_X at x, =&gt; $F\_X\(x\) = lim_\(n-&gt;0^-\)F\_X\(x+h\)$

## Continuous Random Variables

如果一个 Random Variable x is Continuous the Cdf F\_X is Continuous

* State Space S\_X is uncountable

  P\(X = x\) = 0,  ∀ x∊ℝ

  所以看一个range的P

  **Probability Density Function\(pdf\) of X**

  -∞ to x 对于$f\_X\(x\)$的积分 = $F\_X\(x\)$

  almost all:

  $d/dx F\_X = f\_X\(x\)$

* Properties of the pdf
* f\_X\(x\)≥0 因为F\_X是increase函数
* a to b f\_X\(t\)dt = P\(a&lt;X&lt;B\) = F\(b\)-F\(a\)
* -∞ to ∞ f\_X\(t\)dt = 1, 因为F\(∞\) = 1, F\(-∞\) = 0, F\(∞\)-F\(-∞\) = 1

  ![&#x622A;&#x5C4F;2020-09-12 &#x4E0B;&#x5348;3.18.01](https://github.com/SukiXuu/websetting/tree/0aadb01b81fe627c447b9ad1e936219cc6e1a8cd/Users/suki/Documents/GitHub/websetting/courses/MAST20004/draftnotes/截屏2020-09-12%20下午3.18.01-9887948.png)

## Expectation

* Discrete E\[X\] = $\sum\(x=1to6\)xP\_X\(x\)$ 不一定是样本空间里面的元素
* Continuous E\[X\] $\_\(X∊S\_X\)xf\_X\(x\)dx
* Expectation of functions

  ![&#x622A;&#x5C4F;2020-09-12 &#x4E0B;&#x5348;3.50.20](../../../.gitbook/assets/aaa.png)

## Variance

V\(X\): Consistency of Outcome $V\(X\) = E\[\(x - E\(x\)\)^2\]$ 有三个求Variance的公式 $E\(x^2\)-E\(x\)^2$ $E\(x\(x-1\)\)+E\(x\)-E\(x\)^2$

