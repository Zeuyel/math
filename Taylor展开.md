---
tags:
  - 考研
  - math
  - knowledge
---
分组记忆，首先是
$$
e^{x} = \sum _{n=0}^{\infty} \frac{x^{n}}{n!}= 1 + x + \frac{x^{2}}{2} + \frac{x^{3}}{6} + \dots + \frac{x^{k}}{k!} + o(x^{k})
$$
对于 $(1+x)^{\alpha}$ 来说，我们自然的按照定义写出他的展开：

$$
(1+x)^{\alpha} = 1 + \alpha x +  \frac{\alpha(\alpha-1)}{2!}x^{2} + \dots, x \in (-1,1)
$$
并且他还有另外一个名字也就是广义二项式定理，因此他的每一项前的系数为：

$$(1+x)^{\alpha} = \sum_{n=0}^{\infty} \binom{\alpha}{n} x^n$$
取 $\alpha = -1$ 得到了：

$$
\frac{1}{1+x} = 1 - x + x^2 -x^{3} + x^{4} + \dots + (-x)^{k} + \dots \tag{1}
$$

求积分得到了：

$$
\begin{equation}
\ln(1+x) = \sum _{n=0}^{\infty}(-1)^{n} \frac{x^{n+1}}{n+1} = \sum _{n=0}^{\infty} = x - \frac{x^{2}}{2} + \frac{x^{3}}{3} - \dots+ \frac{(-1)^{k}x^{k+1}}{k+1} , x \in (-1,1]
\end{equation}
$$ 
对（1）式代换入 $x^{2}$ 得到了： 

$$
\frac{1}{1+x^{2}} = 1 +(-x^{2}) +(-x^{2})^{2}+ (-x^{2})^{3} + \dots + (-1)^{k}x^{2n}
$$

求积分得到了：

$$
\arctan x = x - \frac{1}{3}x^{3} + \frac{1}{5}x^{5} + \dots + (-1)^{k} \frac{x^{2k+1}}{2k+1}
$$
继续的我们有：

$$ \frac{d}{dx} \arcsin(x) = \frac{1}{\sqrt{1-x^2}} = (1-x^2)^{-\frac{1}{2}} \tag{2}$$
进一步的我们有：
$$(1-x^2)^{-\frac{1}{2}} = \sum_{n=0}^{\infty} \binom{-\frac{1}{2}}{n} (-x^2)^n$$

$$
\begin{align*} 
\binom{-1/2}{n} & = \frac{(-\frac{1}{2})(-\frac{3}{2})(-\frac{5}{2})\dots(-\frac{1}{2}-n+1)}{n!} \\
& = \frac{(-1)^n \cdot (\frac{1}{2})(\frac{3}{2})(\frac{5}{2})\dots(\frac{2n-1}{2})}{n!} \\
& = \frac{(-1)^n \cdot 1 \cdot 3 \cdot 5 \cdot \dots \cdot (2n-1)}{2^n \cdot n!} 
\end{align*}
$$

把偶数项补上我们得到了，$2 \cdot 4 \cdot 6 \cdots (2n) = 2^n \cdot n!$：

$$\binom{-1/2}{n} = \frac{(-1)^n (2n)!}{2^{2n} (n!)^2}$$
那么我们代入回（2）得到了：

$$ 
(1-x^2)^{\frac{1}{2}} = \sum_{n=0}^{\infty} \frac{(-1)^n (2n)!}{2^{2n}(n!)^2} (-x^2)^n
$$
注意到了$(-1)^n \cdot (-1)^{2n} = 1$， 负号被消掉了！所以导致展开所有项都是正的：

$$\frac{d}{dx} \arcsin(x) = \sum_{n=0}^{\infty} \frac{(2n)!}{2^{2n}(n!)^2} x^{2n}$$

写出几项（记忆这个）：

$$1 + \frac{x^2}{2} + \frac{1 \cdot 3}{2 \cdot 4} x^4 + \frac{1 \cdot 3 \cdot 5}{2 \cdot 4 \cdot 6} x^6 + … $$

我们求积分

$$\arcsin(x) = \int \sum_{n=0}^{\infty} \frac{(2n)!}{2^{2n}(n!)^2} x^{2n} dx $$

其实主要对$x^{2n}$ 操作了 ，也就是：

$$ \arcsin(x) = C + \sum_{n=0}^{\infty} \frac{(2n)!}{2^{2n}(n!)^2} \frac{x^{2n+1}}{2n+1} $$

因为 $\arcsin(0) = 0$, 所以积分常数 $C = 0$.

展开形式为：

$$\arcsin(x) = x + \frac{x^3}{2 \cdot 3} + \frac{1\cdot 3 x^5}{2 \cdot 4 \cdot 5} + \frac{1 \cdot 5 x^7}{2 \cdot 6 \cdot 7} + \cdots $$

注意taylor公式也能够帮助我们写出函数的级数展开式。下面就省略了。

三角函数都是隔项的，因此 写余项的时候往后在写一项，这是某些题目的关键。$\sin$ 和 $\cos$ 是震荡的，或者说有界的，肯定是符号交错。$\sin 0 = 0,\cos 0 =1$   ，因此：

$$\sin x  = x - \frac{x^{3}}{6} + \dots + \frac{(-1)^{k}}{(2k+1)!} x^{2k+1} + \dots
$$

$$
\cos x = 1 - \frac{x^{2}}{2} + \frac{x^{4}}{24} + \frac{(-1)^{k}}{2k!} x^{2k} + \dots
$$



事实上 $\sec = \frac{1}{\cos}, \csc = \frac{1}{\sin}$ 实际当中如果忘记可以用长除法得到他们的渐近估计。[[Stolz定理#^ts6kce|长除法估计]]
