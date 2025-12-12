![](images/ccdf0de34a9c27eff926c0349e590a56ac257c57a97d61b1d8fd0590d8ac7cdb.jpg)

# 概率论模拟卷大复盘 (2026版)

# 速成满分概率论

by B站up 夜雨教你考研竞赛

# 目录

# 随机事件及概率 4

维恩图解抽象概率计算 4

# 一维随机变量及分布 6

分布函数的性质与判定 6

一维随机变量函数的分布

类型一：求  $Y = g(X)$  的分布，  $X$  连续型，  $g$  是连续的函数.  
类型二：求  $Y = g(X)$  的分布，  $X$  连续型，  $g$  是分段函数. 8

巧用正态分布绝对值的期望 8  
均匀分布的一个特别结论 9  
伯努利试验及  $n$  重伯努利分布 ..... 10  
随机变量的无记忆性 10

# 二维随机变量及其分布 11

已知联合概率密度  $f(x,y)$  ，求  $F(x,y)$  及  $g(X,Y)$  的分布. 11  
两个随机变量的函数的分布 11

类型一：求  $Z = g(X,Y)$  分布，  $X$  连续型，  $Y$  连续型 11  
类型二：求  $Z = g(X,Y)$  分布，  $X$  离散型，  $Y$  连续型 12

类型三：  $Z$  是一个分段函数，  $Z = \left\{ \begin{array}{ll}g_{1}(X,Y), & (X,Y)\in S\\ g_{2}(X,Y), & (X,Y)\in \overline{S} \end{array} \right.$

随机变量的可加性 13  
最值符号的处理 14  
独立同分布的最大值和最小值 15

二维正态分布的性质 16

独立性判断 17

随机变量类型判断 17

随机变量的数字特征 18

数理统计 22

三大分布的判断 22

利用卡方分布的数字特征 23

分位点问题 24

大数定律和中心极限定理 25

参数估计 27

最大似然估计 27

矩估计 29

假设检验与置信区间 30

双边检验 31

单边检验 32

两类错误 32

# 概率论模拟卷大复盘 26版

# 主讲人 夜雨

集主流模拟卷（张宇八套卷、李林六套卷、李永乐武忠祥六套卷、李永乐武忠祥三套卷、李艳芳三套卷、汤家凤八套卷、新东方五套卷、欧几里得、李良五套卷、张天德五套卷、超越5+5套卷）之精华，帮助大家形成一套知识框架方法体系用最短的时间拿下概率论！

# 随机事件及概率

维恩图解抽象概率计算

张天德五套卷卷一

16. 设  $A, B, C$  为三个随机事件，已知  $P(A) = P(B) = P(C) = \frac{1}{4}, P(AB) = P(BC) = 0,$ $P(AC) = \frac{1}{8}$ ，则  $A, B, C$  全不发生的概率为

李林六套卷卷三

8.设  $A, B$  是两个随机事件， $P(A) = 0.2, P(B|A) = P(B|\overline{A}), P(A \cup B) = 0.6$ ，则  $P(\overline{A} \cup \overline{B}) =$

A.0.4.

B.0.5.

C.0.8.

D.0.9.

李艳芳三套卷卷一

（16）设  $A, B, C$  为三个随机事件，已知  $A$  与  $C$  相互独立， $B$  与  $C$  互不相容， $A, B, C$  都不发生的概率为  $\frac{1}{12}$ 。若  $P(C) = \frac{1}{4}, P(B \cup C \mid A) = \frac{1}{3}, P(A\overline{B}) = P(\overline{A}B)$ ，则  $P(A \cup \overline{B}) =$  ______.

超越卷卷一

（16）已知随机事件  $A, B, C$  恰好有一个不发生的概率为  $\frac{1}{3}$ ，且  $A, B$  互斥， $\mathrm{P}(A) = \mathrm{P}(B) = \frac{2}{5}$ ，则  $\mathrm{P}(C|A \cup B) = \_$ 。

超越卷卷八

（8）若事件  $A$  与  $B$  同时发生时，则事件  $C$  发生，若  $A$  与  $B$  都不发生时，则  $C$  也不发生，下列命题正确的个数为（ ）.

$①$ $\mathrm{P}(A\bigcup B\bigcup C) > \mathrm{P}(A\bigcup B),$ $②$ $\mathrm{P}(C - A)\leqslant \mathrm{P}(B - A),$  
③  $\mathrm{P}(C) \leqslant \mathrm{P}(A) + \mathrm{P}(B) - 1$ ，④  $\mathrm{P}(C) = \mathrm{P}(AB)$ .

(A) 1

(B) 2

(C) 3

(D)4

李永乐六套卷卷三

8. 对事件  $A, B$ ，以下结论中必然成立的是

A.  $P(A \cup B) = P(A) + P(B)$ .

B.  $P(AB) = P(A)P(B)$ .

C.  $P(A \cup B)P(AB) \geqslant P(A)P(B)$ .

D.  $P(A \cup B)P(AB) \leqslant P(A)P(B)$ .

李林六套卷卷二

8. 设  $A, B, C$  是三个随机事件， $P(ABC) = 0, 0 < P(C) < 1$ ，则正确的是

A.  $P(ABC) = P(A)P(B)P(C)$ .  
B.  $P(A \cup B \cup C) = P(A) + P(B) + P(C)$ .  
C.  $P\left[(A \cup B) \mid \overline{C}\right] = P(A \mid \overline{C}) + P(B \mid \overline{C})$  
D.  $P[(A \cup B) \mid C] = P(A \mid C) + P(B \mid C)$ .

张宇八套卷卷四

16.已知  $A$  发生且  $B$  不发生的概率为  $\frac{1}{2}$  ，在  $A$  发生或  $B$  不发生的条件下  $B$  发生的概率为  $\frac{1}{4}$  若  $A$  发生的概率为  $\frac{7}{10}$  则  $B$  发生的概率为

超越卷卷八

（10）已知随机变量  $X$  和  $Y$  同分布， $X$  的密度函数  $f(x)$  满足  $f(1 - x) = f(1 + x)$ ，若  $\mathrm{P}(X \geqslant 2, Y \geqslant 0) = p\left(0 < p < \frac{1}{2}\right)$ ，则  $\mathrm{P}(X < 2, Y < 0) = (\quad)$ .

(A)  $1 - p$

(B)  $1 - \frac{p}{2}$

(C)  $1 - 2p$

(D)  $p$

超越卷卷八

(8) 已知  $\mathrm{P}(A) = \frac{3}{5}, \mathrm{P}(B) = \frac{4}{5}$ ，记  $p = \mathrm{P}(B|A) \cdot \mathrm{P}(B|\overline{A})$ ，则  $p$  的最大值与最小值的差为（ ）.

(A)  $\frac{1}{3}$

(B)  $\frac{1}{4}$

(C)  $\frac{1}{5}$

(D)  $\frac{1}{6}$

# 一维随机变量及分布

分布函数的性质与判定

分布函数  $F(x) = P\{X \leqslant x\}$  的性质

性质一：  $F(x)$  是一个不减的非负函数  $(0\leqslant F(x)\leqslant 1)$

性质二：  $F(-\infty) = 0$  ，  $F(+\infty) = 1$  ，其中  $F(-\infty) = \lim_{x\to -\infty}F(x)$  ，  $F(+\infty) = \lim_{x\to +\infty}F(x)$

性质三：  $F(x + 0) = F(x)$  即  $F(x)$  是右连续的，其中  $F(x + 0) = \lim_{t\to x^{+}}F(t)$

李永乐六套卷卷一

8. 设连续型随机变量  $X$  的分布函数为  $F(x)$ ，且  $F(0) = 0$ ，则下列函数可作为分布函数的是

$$
\begin{array}{l} \mathrm {A}. G _ {1} (x) = \left\{ \begin{array}{c c} 1 + F \left(\frac {1}{x}\right), & x > 1, \\ 0, & x \leqslant 1. \end{array} \right. \\ \mathrm {B}. G _ {2} (x) = \left\{ \begin{array}{c c} 1 - F \left(\frac {1}{x}\right), & x > 1, \\ 0, & x \leqslant 1. \end{array} \right. \\ \mathrm {C}. G _ {3} (x) = \left\{ \begin{array}{c c} F (x) + F \left(\frac {1}{x}\right), & x > 1, \\ 0, & x \leqslant 1. \end{array} \right. \\ \mathrm {D}. G _ {4} (x) = \left\{ \begin{array}{c l} F (x) - F \left(\frac {1}{x}\right), & x > 1, \\ 0, & x \leqslant 1. \end{array} \right. \\ \end{array}
$$

# 一维随机变量函数的分布

类型一：求  $Y = g(X)$  的分布， $X$  连续型， $g$  是连续的函数

核心：从  $g(X)\leqslant y$  反解出  $X$

李林六套卷卷一

22.（本题满分12分）

设随机变量  $X$  的概率密度为  $f(x) = \frac{1}{\pi(1 + x^2)} (-\infty < x < +\infty), Y = \operatorname{arccot} X$ ，随机变量  $Z \sim N(0,1)$ ，且  $Y$  与  $Z$  相互独立.

（I）求  $Y$  的分布函数与概率密度；  
（II）求  $U = Z + Y$  的概率密度

李林六套卷卷三

22.（本题满分12分）

设随机变量  $X$  在区间  $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$  内服从均匀分布,  $Y$  的分布律为  $P\{Y = 0\} = P\{Y = 1\} = \frac{1}{2}$ , 且  $X$  与  $Y$  相互独立, 记  $Z = |\sin X|$ .

（I）求  $Z$  的概率密度；  
（II）求  $V = Y + Z$  的概率密度

类型二：求  $Y = g(X)$  的分布， $X$  连续型， $g$  是分段函数

1）根据分段的情况作全集拆分2）找分段点

超越卷卷七

(22) (本题满分12分) 设随机变量  $X$  的概率密度为  $f_{X}(x) = \begin{cases} \frac{1}{\sqrt{2\pi}} e^{-\frac{x^{2}}{2}}, & x \leqslant 0, \\ e^{-2x}, & x > 0. \end{cases}$

令  $Z = \mathrm{g}(X) = \left\{ \begin{array}{ll}X, & X <   0,\\ X^2, & 0\leqslant X\leqslant 1,\\ X, & X > 1. \end{array} \right.$

（I）求  $Z$  的概率密度；（Ⅱ）求期望EZ.

![](images/aaf19b615d0ef1659552a5335e7c97f86b9bf48d2b33d00eab564a5db4958f1b.jpg)

# 巧用正态分布绝对值的期望

若  $X \sim N(0,1)$ ，则  $E(|X|) = \sqrt{\frac{2}{\pi}}$  （记）， $D(|X|) = E(|X|^2) - E^2(|X|) = 1 - \frac{2}{\pi}$  （不记）

最值符号也可以和绝对值联系到一起

$$
\begin{array}{l} \min  \{X, Y \} = \frac {X + Y - | X - Y |}{2} \\ \max  \{X, Y \} = \frac {X + Y + | X - Y |}{2} \\ \end{array}
$$

张宇八套卷卷八

$$
\begin{array}{l} E (| x |) = \int_ {- \infty} ^ {+ \infty} | x | \cdot \varphi (x) d x = 2 \int_ {0} ^ {+ \infty} X \varphi (x) d x \\ \therefore \frac {2}{\sqrt {x}} \int_ {0} ^ {+ \infty} x \cdot e ^ {\frac {x ^ {2}}{2}} d x \\ \end{array}
$$

$$
\frac {1}{6} = a (z) = \sqrt {\frac {2}{\pi}}
$$

16. 设  $X_{1}, X_{2}$  为来自总体  $N(0,1)$  的简单随机样本，记  $\hat{\sigma} = a\left|X_{1} - X_{2}\right|(a > 0)$ ，若  $D(\hat{\sigma}) = 1$ ，则  $a =$

$$
2 = x _ {1} - x _ {2} \wedge (0, 2) \quad E (\hat {G}) = E (a ^ {2} z ^ {2}) - E ^ {2} (a z) = a ^ {2} (E (z ^ {2}) - E ^ {2} (z))
$$

李永乐六套卷卷三

$$
E (z) + D (z) = 1 \frac {2}{\pi}
$$

10. 设随机变量  $\left( {\xi ,\eta }\right)$  服从二维正态分布,  $\xi$  和  $\eta$  均服从  $N\left( {0,\frac{1}{2}}\right)$  分布,  $\left( {\xi ,\eta }\right)$  的相关系数为  $\rho  \in  \left( {-1,1}\right)$  , 则  $E\left\lbrack  {\min \left( {\xi ,\eta }\right) }\right\rbrack   =$

A. 0.

$$
\mathrm {B}. 2 \sqrt {\frac {1 - \rho}{\pi}}.
$$

$$
C. \sqrt {\frac {1 - \rho}{\pi}}.
$$

$$
D. - \sqrt {\frac {1 - \rho}{\pi}}.
$$

汤家凤八套卷卷一

9. 设随机变量  $X \sim N(1, 1), Y \sim N(1, 1), X, Y$  相互独立，则  $E(\min\{X, Y\}) = (\quad)$

A.  $1 + \frac{1}{\sqrt{\pi}}$

B.  $1 - \frac{1}{\sqrt{\pi}}$

C.  $1 - \frac{2}{\sqrt{\pi}}$

D.  $1 + \frac{2}{\sqrt{\pi}}$

张宇八套卷卷一

9. 设  $X_{1}, X_{2}, \dots, X_{n} (n \geqslant 2)$  为来自正态总体  $X$  的简单随机样本， $E(X) = \mu, D(X) = \sigma^{2}$ ， $\sigma > 0$ ，记  $Y = \frac{1}{n} \sum_{i=1}^{n} |X_{i} - \mu|$ ，则  $D(Y) =$

A.  $\frac{\sigma^2}{n}\left(1 - \frac{2}{\pi}\right)$

B.  $\frac{\sigma^2}{n}\left(1 - \frac{\pi}{2}\right)$

C.  $\frac{\sigma^2}{n^2}\left(1 - \frac{2}{\pi}\right)$

D.  $\frac{\sigma^2}{n^2}\left(1 - \frac{\pi}{2}\right)$

均匀分布的一个特别结论

若  $F(x)$  是  $X$  的分布函数，则  $F(X)\sim U(0,1)$

张宇八套卷卷二

16. 设随机变量  $X$  的概率密度为  $f(x) = \begin{cases} \frac{x}{2}, & 0 < x < 2, \\ 0, & \text{其他}, \end{cases}$ $F_{X}(x)$  是  $X$  的分布函数，若  $Y = -\ln [1 - F_X(X)]$

则  $P\left\{Y > \frac{1}{2}\right\} = \underline{\quad}$

新东方五套卷卷三

(8) 设随机变量  $X \sim E(\lambda), F(x)$  为其分布函数, 则随机变量  $Y = F(X)$  的分布函数 ( )

(A) 处处可导

(B) 恰有 1 个不可导点

(C) 恰有2个不可导点

(D) 恰有3个不可导点

# 伯努利试验及  $n$  重伯努利分布

定义：将只有两个结果  $A$  和  $\overline{A}$  的随机试验称为伯努利试验，将伯努利试验独立重复进行  $n$  次称为  $n$  重伯努利试验，记  $n$  重伯努利试验中  $A$  出现的次数为  $X$  ，每次试验中  $A$  出现的概率为  $p$  ，则称  $X$  服从  $n$  重伯努利分布或二项分布，记为  $X\sim B(n,p)$

1）若  $X \sim B(n, p)$ ，当  $k = [(n + 1)p]$  时， $P\{X = k\}$  达到最大值

（换言之，  $X$  最有可能取到  $[(n + 1)p]$  ）

2）若  $X \sim B(n, p)$ ，则当  $p$  充分小而  $n$  充分大且  $np$  适中时， $X$  近似服从参数为  $\lambda = np$  的泊松分布，即  $P\{X = k\} = C_n^k p^k (1 - p)^{n - k} \approx \frac{\lambda^k}{k!} e^{-\lambda}$  （其中  $\lambda = np$ ）（泊松定理）

张宇八套卷卷三

16. 设有 40 个盒子, 100 个球, 每个球等可能地放入任一盒子中, 则指定某一个盒子中最有可能出现的球的个数为

# 张宇八套卷卷二

10. 设总体  $X$  服从参数为 1 的指数分布,  $X_{1}, X_{2}, \dots, X_{n}$  为来自总体  $X$  的简单随机样本, 记  $\nu_{n}(1)$  为  $n$  个观测值中不大于 1 的个数, 则  $\frac{\nu_{n}(1)}{n}$  的方差为

A.  $\frac{e - 1}{n e^{2}}$ .

B.  $\frac{e - 1}{n e}$ .

C.  $\frac{\mathrm{e}(\mathrm{e} - 1)}{n}$ .

D.  $\frac{\mathrm{e} - 1}{n}$ .

# 随机变量的无记忆性

几何分布具有“无记忆性”

$$
P (X > m + n | X > m) = P (X > n)
$$

$$
P (X <   m + n | X > m) = P (X <   n)
$$

$$
P (X = m + n \mid X > m) = P (X = n)
$$

指数分布具有“无记忆性”

$$
P (X > s + t | X > t) = P (X > s)
$$

$$
P (X <   s + t | X > t) = P (X <   s)
$$

# 二维随机变量及其分布

已知联合概率密度  $f(x,y)$ ，求  $F(x,y)$  及  $q(X,Y)$  的分布

核心：分情况求二重积分

超越卷卷九

（22）（本题满分12分）设随机变量  $X$  的密度函数  $f_{X}(x) = \left\{ \begin{array}{ll}ax^{2}\mathrm{e}^{-x}, & x > 0,\\ 0, & \text{其他，} \end{array} \right.$  在  $X = x(x > 0)$  条件下，随机变量  $Y\sim \mathrm{U}(0,x)$

（I）求常数  $a$  ，以及  $(X,Y)$  的联合分布函数  $F(x,y)$  
（Ⅱ）求  $Y$  的密度函数  $f_{Y}(y)$  
（Ⅲ）求  $Z = X - Y$  的密度函数  $f_{Z}(z)$

两个随机变量的函数的分布

类型一：求  $Z = g(X,Y)$  分布， $X$  连续型， $Y$  连续型

汤家凤八套卷

22.（本题满分12分）

设随机变量  $X \sim U(-1, 1), Y \sim E(1), X, Y$  相互独立.

（1）求  $Z = X + 2Y$  的概率密度函数；  
(2) 求  $\rho_{XZ}$ .

类型二：求  $Z = g(X,Y)$  分布， $X$  离散型， $Y$  连续型

核心：根据离散型变量作全集拆分

李林六套卷卷三

22.（本题满分12分）

设随机变量  $X$  在区间  $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$  内服从均匀分布,  $Y$  的分布律为  $P\{Y = 0\} = P\{Y = 1\} = \frac{1}{2}$ , 且  $X$  与  $Y$  相互独立, 记  $Z = |\sin X|$ .

（I）求  $Z$  的概率密度；  
（II）求  $V = Y + Z$  的概率密度

类型三：  $Z$  是一个分段函数，  $Z = \left\{ \begin{array}{ll}g_{1}(X,Y), & (X,Y)\in S\\ g_{2}(X,Y), & (X,Y)\in \overline{S} \end{array} \right.$

根据情况  $(X,Y)\in S,(X,Y)\in \bar{S}$  作全集拆分

$$
F _ {Z} (z) = P \left\{Z \leqslant z, (X, Y) \in S \right\} + P \left\{Z \leqslant z, (X, Y) \in \bar {S} \right\}
$$

超越卷卷三

（22）（本题满分12分）设随机变量  $X$  与  $Y$  相互独立， $X$  服从区间  $[0,2]$  上的均匀分布， $Y$  服从参数为1的指数分布，令  $Z = \begin{cases} Y, & 0 \leqslant X \leqslant 1, \\ X, & 1 < X \leqslant 2. \end{cases}$

（I）求  $Z$  的概率密度；（Ⅱ）求协方差  $\operatorname {Cov}(X,Z)$

# 随机变量的可加性

正态分布、泊松分布、二项分布、 $\chi$  分布、 $\Gamma$  分布都具有可加性

设  $X$  和  $Y$  是两个相互独立的随机变量， $X \sim N(\mu_1, \sigma_1^2), Y \sim N(\mu_2, \sigma_2^2)$ ，则  $X + Y \sim N(\mu_1 + \mu_2, \sigma_1^2 + \sigma_2^2)$

设  $X$  和  $Y$  是两个相互独立的随机变量， $X \sim B(n_1, p), Y \sim B(n_2, p)$ ，则  $X + Y \sim B(n_1 + n_2, p)$

设  $X$  和  $Y$  是两个相互独立的随机变量， $X \sim P(\lambda_1), Y \sim P(\lambda_2)$ ，则  $X + Y \sim P(\lambda_1 + \lambda_2)$

设  $X$  和  $Y$  是两个相互独立的随机变量， $X \sim \chi^2(n), Y \sim \chi^2(m)$ ，则  $X + Y \sim \chi^2(n + m)$

设  $X$  和  $Y$  是两个相互独立的随机变量， $X \sim \Gamma(\alpha, \theta), Y \sim \Gamma(\beta, \theta)$ ，则  $X + Y \sim \Gamma(\alpha + \beta, \theta)$

注：指数分布、均匀分布、几何分布不具有可加性

特别地，正态分布还有如下性质

1）若随机变量  $X$  服从正态分布，则  $Y = aX + b(a\neq 0)$  也服从正态分布  
2）若  $X_{1},X_{2},\dots ,X_{n}$  相互独立且都服从正态分布，则  $Y = a_{1}X_{1} + a_{2}X_{2} + \dots +a_{n}X_{n}$  和

[ Z = a_{1}X_{1} + a_{2}X_{2} + \dots +a_{n}X_{n} + b(a_{i}\neq 0) ] 也服从正态分布

超越卷

（16）设随机变量  $X_{1}, X_{2}, \dots, X_{n}$  相互独立，且  $X_{i} \sim \mathrm{P}(\lambda_{i})$  ， $\lambda_{i} > 0$  ， $i = 1, 2, \dots, n$  。已知  $\mathrm{P}\left\{\sum_{i=1}^{n} X_{i} \geqslant 1\right\} = 1 - \mathrm{e}^{-1}$ ，则期望  $\mathrm{E}(2^{i-1}) =$

张宇八套卷卷五

8. 设  $X, Y$  与  $X + Y$  均服从同一种分布，其中  $X, Y$  相互独立，则下列分布一定可以成立的是

A. 均匀分布.

B. 泊松分布.

C. 指数分布.

D.二项分布.

张宇八套卷卷一（好题）

8. 设  $X, Y$  分别服从参数为  $n, m$  的泊松分布，且  $n > m$  ， $F_{X}(x), F_{Y}(y)$  分别是  $X, Y$  的分布函数， $-\infty < z < +\infty$  ，则

A.  $P\{X \geqslant Y\} = 1$

B.  $P\{X \leqslant Y\} = 1$

C.  $F_{X}(z) \geqslant F_{Y}(z)$ .

D.  $F_{X}(z) \leqslant F_{Y}(z)$ .

# 最值符号的处理

$$
\begin{array}{l} \min  \{x, y \} <   \triangle \xrightarrow {\text {对 立 事 件}} \min  \{x, y \} > \triangle \\ \max  \{x, y \} > \triangle \xrightarrow {\text {对 立 事 件}} \max  \{x, y \} <   \triangle \\ \end{array}
$$

超越卷卷五

（9）设二维随机变量  $(X,Y)$  的概率密度  $f(x,y) = \left\{ \begin{array}{ll}Ax\mathrm{e}^{-y}, & 0 < x < y < + \infty ,\\ 0, & \text{其他}. \end{array} \right.$  记  $M = \max \{X,Y\} ,N = \min \{X,Y\}$  ，则  $\mathrm{P}\{M < 2,N < 1\} = ()$

(A)  $1 - \frac{1}{\mathrm{e}}$

(B)  $1 - \frac{1}{\mathrm{e}} -\frac{1}{\mathrm{e}^2}$

(C)  $1 - \frac{2}{\mathrm{e}^2}$

(D)  $1 - \frac{2}{\mathrm{e}} - \frac{1}{2\mathrm{e}^2}$

# 李永乐三套卷名校版

8. 已知随机变量  $X$  与  $Y$  均服从正态分布  $N(\mu, \sigma^2)$ ，如果存在常数  $\alpha$ ，有  $P\{\max(X, Y) > \alpha\} = P\{\min(X, Y) \leqslant \alpha\}$ ，则  $\alpha$  必为

A.  $\frac{\mu}{2}$ .

B.  $-\frac{\mu}{2}$ .

C.  $\mu$

D.  $-\mu$

# 汤家凤八套卷卷七

10. 设随机变量  $X \sim E(2), Y = \min \{X, 2\}, Y$  的分布函数为  $F_{Y}(y)$ ，则（ ）.

A.  $F_{Y}(y)$  为可导函数

B.  $F_{Y}(y)$  连续，但不可导

C.  $F_{Y}(y)$  有一个跳跃间断点

D.  $F_{Y}(y)$  有两个间断点

# 独立同分布的最大值和最小值

当  $X_{1},X_{2},\dots ,X_{n}$  相互独立时且具有相同分布函数  $F(x)$  时，有  $F_{\max}(z) = [F(x)]^n$  ，  $F_{\min}(x) = 1 - [1 - F(x)]^n$  推论：  $X_{1},X_{2},\dots ,X_{n}$  独立同分布于  $E(\lambda)\Rightarrow \min \{X_1,X_2,\dots ,X_n\} \sim E(n\lambda)$

推广：  $X_{1},X_{2},\dots ,X_{n}$  分布于  $E(\lambda_1),E(\lambda_2),\dots ,E(\lambda_n)$  且独立  $\Longrightarrow \min \{X_1,X_2,\dots ,X_n\} \sim E(\lambda_1 + \lambda_2 + \dots +\lambda_n)$  证明如下

$$
F _ {\max } (x) = P \left\{\max  \left\{X _ {1}, X _ {2}, \dots , X _ {n} \right\} \leqslant x \right\} = P \left\{X _ {1} \leqslant x \right\} P \left\{X _ {2} \leqslant x \right\} \dots P \left\{X _ {n} \leqslant x \right\} = [ F (x) ] ^ {n}
$$

$$
\begin{array}{l} F _ {\min } (x) = P \left\{\min  \left\{X _ {1}, X _ {2}, \dots , X _ {n} \right\} \leqslant x \right\} = 1 - P \left\{\min  \left\{X _ {1}, X _ {2}, \dots , X _ {n} \right\} > x \right\} \\ = 1 - P \left\{X _ {1} > x \right\} P \left\{X _ {2} > x \right\} \dots P \left\{X _ {n} > x \right\} \\ = 1 - \left(1 - P \left\{X _ {1} \leqslant x \right\}\right) \left(1 - P \left\{X _ {2} \leqslant x \right\}\right) \dots \left(1 - P \left\{X _ {n} \leqslant x \right\}\right) \\ = 1 - [ 1 - F (x) ] ^ {n} \\ \end{array}
$$

# 超越卷卷四

（9）设  $X$  与  $Y$  相互独立， $X \sim \mathrm{E}(\lambda_1), Y \sim \mathrm{E}(\lambda_2) (\lambda_1 > 0, \lambda_2 > 0), Z = \min \{X, Y\}$  且  $\mathrm{P}\{Z \leqslant 1\} = 1 - \mathrm{e}^{-2}$ ，则  $\mathrm{EZ}^2 = (\quad)$ .

(A)  $\frac{1}{4}$

(B)  $\frac{3}{4}$

(C)  $\frac{1}{2}$

(D)  $\frac{3}{2}$

# 李永乐六套卷卷二

9. 设随机变量  $X$  和  $Y$  均服从指数分布  $E(1)$ , 且  $X, Y$  相互独立, 则  $P\{1 \leqslant \min(X, Y) \leqslant 2\} =$

A.  $\mathrm{e}^{-1}(1 - \mathrm{e}^{-1})$

B.  $e^{-1}(1 - e^{-2})$

C.  $e^{-2}(1 - e^{-1})$

D.  $e^{-2}(1 - e^{-2})$

# 李永乐六套卷卷六

8. 已知随机变量  $X_{1}, X_{2}, X_{3}$  相互独立且均服从指数分布，参数依次为  $\lambda_{1}, \lambda_{2}, \lambda_{3}$  （均大于0），则  $P\{X_{1} = \min(X_{1}, X_{2}, X_{3})\} =$

A. 0.

B.  $\frac{1}{3}$ .

C.  $\frac{\lambda_{1}}{\lambda_{1} + \lambda_{2} + \lambda_{3}}$ .

D.  $\frac{\lambda_{2} + \lambda_{3}}{\lambda_{1} + \lambda_{2}\lambda_{3}}$ .

# 新东方五套卷卷一

(8) 在  $(0,1)$  上任取  $n$  个点，则最远两点间距离的数学期望为（

(A)  $\frac{n - 2}{n}$

(B)  $\frac{n - 1}{n}$

(C)  $\frac{n - 1}{n + 1}$

(D)  $\frac{n}{n + 1}$

# 二维正态分布的性质

性质一：若  $(X,Y)\sim N(\mu_1,\mu_2;\sigma_1^2,\sigma_2^2;\rho)$  ，则  $X\sim N(\mu_1,\sigma_1^2),Y\sim N(\mu_2,\sigma_2^2)$

注：  $X$  和  $Y$  均服从正态分布  $\neq (X,Y)$  服从二维正态分布

性质二：  $X\sim N(\mu_1,\sigma_1^2),Y\sim N(\mu_2,\sigma_2^2)$  且  $X$  与  $Y$  相互独立，则  $(X,Y)\sim N(\mu_1,\mu_2;\sigma_1^2,\sigma_2^2;0)$

性质三：若  $(X,Y)\sim N(\mu_1,\mu_2;\sigma_1^2,\sigma_2^2;\rho)$  ，则  $X$  与  $Y$  相互独立  $\Leftrightarrow X$  与  $Y$  不相关（即  $cov(X,Y) = 0$  ）

性质四：若  $(X,Y)$  服从二维正态分布，且  $\left| \begin{array}{ll}a & b\\ c & d \end{array} \right|\neq 0$  ，则  $(aX + bY,cX + dY)$  服从二维正态分布

性质五：若  $(X,Y)\sim N(\mu_1,\mu_2,\sigma_1^2,\sigma_2^2,\rho)$  ，则  $aX + bY\sim N(a\mu_1 + b\mu_2,a^2\sigma_1^2 +b^2\sigma_2^2 +2ab\rho \sigma_1\sigma_2)$  （其中  $a,b$  不全为零）张天德五套卷

9. 已知  $(X, Y) \sim N\left(0, 0; 1^{2}, 2^{2}; \frac{1}{2}\right)$ ，若  $Z = aX + Y$  与  $Y$  独立，则  $a$  等于（ ）.

A. 2.

B. -2.

C. 4.

D. -4.

张宇八套卷卷六

8. 设随机变量  $(X_{1}, X_{2}) \sim N(0, 0; \sigma_{1}^{2}, \sigma_{2}^{2}; \rho)$ ,  $\sigma_{1} \neq \sigma_{2}$ , 若  $Y_{1} = X_{1} \cos \alpha + X_{2} \sin \alpha$  与  $Y_{2} = X_{2} \cos \alpha - X_{1} \sin \alpha$  相互独立,  $\cos 2\alpha \neq 0$ , 则  $\tan 2\alpha =$

A.  $\rho \frac{\sigma_1^2\sigma_2^2}{\sigma_1^2 - \sigma_2^2}$

B.  $\rho \frac{\sigma_{1}^{2}\sigma_{2}^{2}}{\sigma_{2}^{2} - \sigma_{1}^{2}}$

C.  $2 \rho \frac{\sigma_{1} \sigma_{2}}{\sigma_{1}^{2} - \sigma_{2}^{2}}$ .

D.  $2 \rho \frac{\sigma_{1} \sigma_{2}}{\sigma_{2}^{2} - \sigma_{1}^{2}}$ .

李林六套卷卷一

9. 设  $(X, Y) \sim N\left(1, 0; 9, 16; -\frac{1}{2}\right), Z = \frac{1}{3} X + \frac{1}{2} Y$ ，则

A.  $X$  与  $Z$  不相关

B.  $X$  与  $Z$  不相互独立

C.  $Y$  与  $Z$  不相关

D.  $Y$  与  $Z$  相互独立

# 独立性判断

对于二维连续型随机变量  $(X,Y)$ ， $X$  和  $Y$  相互独立  $\iff F(x,y) = F_X(x)F_Y(y) \iff f(x,y) = f_X(x)f_Y(y)$

对于二维离散型随机变量  $(X,Y)$ ， $X$  和  $Y$  相互独立  $\iff P\{X = x_i, Y = y_j\} = P\{X = x_i\} P\{Y = y_j\}$

李林六套卷卷二

9.设随机变量  $X_{1}\sim B(1,p),X_{2}\sim B(2,p)(0 <   p <   1)$  ，且  $X_{1}$  与  $X_{2}$  相互独立，记  $Z_{1} =$

$2X_{1} + X_{2},Z_{2} = X_{1} - X_{2}$  ，则

A.  $Z_{1}$  与  $Z_{2}$  不相关,  $Z_{1}$  与  $Z_{2}$  相互独立

B.  $Z_{1}$  与  $Z_{2}$  不相关,  $Z_{1}$  与  $Z_{2}$  不相互独立

C.  $Z_{1}$  与  $Z_{2}$  相关,  $Z_{1}$  与  $Z_{2}$  相互独立

D.  $Z_{1}$  与  $Z_{2}$  相关,  $Z_{1}$  与  $Z_{2}$  不相互独立

# 随机变量类型判断

相互独立的连续型随机变量  $+$  离散型随机变量，是连续型随机变量

比如  $X \sim \left( \begin{array}{cccc} p_1 & p_1 & \dots & p_n \\ x_1 & x_2 & \dots & x_n \end{array} \right)$ ， $Y \sim f(y)$ ，且  $X, Y$  独立，则  $U = X + Y$  是连续型随机变量

$$
\begin{array}{l} F _ {U} (u) = P \{U \leqslant u \} \\ = P \left\{U \leqslant u, X = x _ {1} \right\} + P \left\{U \leqslant u, X = x _ {2} \right\} + \dots + P \left\{U \leqslant u, X = x _ {n} \right\} \\ = P \{X + Y \leqslant u, X = x _ {1} \} + P \{X + Y \leqslant u, X = x _ {2} \} + \dots + P \{X + Y \leqslant u, X = x _ {n} \} \\ = P \left\{Y \leqslant u - x _ {1}, X = x _ {1} \right\} + P \left\{Y \leqslant u - x _ {2}, X = x _ {2} \right\} + \dots + P \left\{Y \leqslant u - x _ {n}, X = x _ {n} \right\} \\ = p _ {1} \int_ {- \infty} ^ {u - x _ {1}} f (y) d y + p _ {2} \int_ {- \infty} ^ {u - x _ {2}} f (y) d y + \dots + p _ {n} \int_ {- \infty} ^ {u - x _ {n}} f (y) d y \\ = p _ {1} \int_ {- \infty} ^ {u} f (t - x _ {1}) d t + p _ {2} \int_ {- \infty} ^ {u} f (t - x _ {2}) d t + \dots + p _ {n} \int_ {- \infty} ^ {u} f (t - x _ {n}) d t \\ = \int_ {- \infty} ^ {u} \left[ p _ {1} f (t - x _ {1}) + p _ {2} f (t - x _ {2}) + \dots + p _ {n} f (t - x _ {n}) \right] d t \\ \end{array}
$$

$p_1f(t - x_1) + p_2f(t - x_2) + \dots +p_nf(t - x_n)$  就是  $U = X + Y$  的概率密度

# 超越卷卷七

(10) 已知随机变量  $X \sim \mathrm{N}(0, 1), Y \sim B\left(1, \frac{1}{2}\right)$ ，且  $X$  和  $Y$  相互独立，记  $Z_{1} = X + Y, Z_{2} = X \cdot Y$  则下列结论正确的是（ ）.

（A）  $Z_{1},Z_{2}$  均为非连续型随机变量  
(B)  $Z_{1}$  为非连续型随机变量， $Z_{2}$  为连续型随机变量  
（C）  $Z_{1}$  为连续型随机变量，  $Z_{2}$  为非连续型随机变量  
(D)  $Z_{1}, Z_{2}$  均为连续型随机变量

# 随机变量的数字特征

# 期望

1）  $E(X) = \sum_{k = 1}^{\infty}x_kp_k$  或  $\int_{-\infty}^{+\infty}xf(x)dx$  （常用）  
2)  $E(g(X)) = \sum_{k=1}^{\infty} g(x_k)p_k$  或  $\int_{-\infty}^{+\infty} g(x)f(x)dx$  （常用）  
3）  $E(g(X,Y)) = \sum_{k = 1}^{\infty}g(x_k,y_k)p_k$  或  $\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}g(x,y)f(x,y)dxdy$  （常用）  
4)  $E(C) = C$  
5)  $E(CX) = CE(X)$  
6)  $E(X + Y) = E(X) + E(Y)$  
7）  $X,Y$  不相关  $\Longleftrightarrow E(XY) = E(X)E(Y)$  （常用）  $cov(X,Y) = E(XY) - E(X)E(Y)$  方差

1)  $D(X) = E\left\{\left[X - E(X)\right]^2\right\} = \sum_{k=1}^{\infty}\left[x_k - E(X)\right]^2 p_k$  或  $\int_{-\infty}^{+\infty}[x - E(X)]^2 f(x)dx$  （不常用）  
2)  $D(X) = E(X^2) - [E(X)]^2$  （最常用）  
3)  $D(C) = 0$  
4)  $D(CX) = C^2 D(X)$ ,  $D(X + C) = D(X)$  
5)  $D(X + Y) = D(X) + D(Y) + 2cov(X,Y)$  
6）若  $X,Y$  相互独立，则有  $D(X + Y) = D(X) + D(Y)$  
7)  $D(X) = 0 \iff P\{X = E(X)\} = 1$

# 协方差

1)  $\operatorname{Cov}(X, Y) = E\{[X - E(X)][Y - E(Y)]\} = \sum_{j=1}^{\infty} \sum_{i=1}^{\infty} [x_i - E(X)][y_j - E(Y)] p_{ij}$  （不常用）  
或  $\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}[x - E(X)][y - E(Y)]f(x,y)dxdy$  （不常用）  
2)  $\operatorname{Cov}(X, Y) = \frac{1}{2} [D(X + Y) - D(X) - D(Y)]$  （不常用）  
3)  $Cov(X,Y) = E(XY) - E(X)E(Y)$  （最常用）  
4)  $\operatorname{Cov}(X, Y) = \operatorname{Cov}(Y, X)$  
5)  $\operatorname{Cov}(X, X) = D(X)$  
6)  $\text{Cov}(aX, bY) = ab\text{Cov}(X, Y)$  
7)  $\operatorname{Cov}(X_1 + X_2, Y) = \operatorname{Cov}(X_1, Y) + \operatorname{Cov}(X_2, Y)$

# 相关系数

1)  $\rho_{XY} = \frac{Cov(X,Y)}{\sqrt{D(X)}\sqrt{D(Y)}}$  
2）  $|\rho_{XY}| = 1\Leftrightarrow$  存在常数  $a,b$  ，使得  $P\{Y = aX + b\} = 1$

当  $\rho_{XY} = 1\Leftrightarrow$  存在常数  $a,b$  ，使得  $P\{Y = aX + b\} = 1$  且  $a > 0$

$\rho_{XY} = -1 \Leftrightarrow$  存在常数  $a, b$ ，使得  $P\{Y = aX + b\} = 1$  且  $a < 0$

新东方五套卷卷二

(16) 设  $X_{1}, X_{2}$  为来自总体  $X \sim N(\mu, \sigma^{2})$  的简单随机样本， $\bar{X} = \frac{1}{2}(X_{1} + X_{2})$ ，则  $X_{1} - \bar{X}$  与  $X_{2} - \bar{X}$  的相关系数  $\rho = \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.$

注意：  $\left(X_{1} - \overline{X}\right) + \left(X_{2} - \overline{X}\right) = X_{1} + X_{2} - 2\overline{X} = 0$

李林六套卷

9.设  $X_{1}$  与  $X_{2}$  相互独立，且均服从  $N\left(\mu ,\sigma^2\right),\overline{X} = \frac{1}{2}\left(X_1 + X_2\right)$  ，则

A.  $X_{1} - \overline{X}$  与  $X_{2} - \overline{X}$  相互独立

B.  $X_{1} - \overline{X}$  与  $X_{2} - \overline{X}$  相关

C.  $X_{1} + X_{2}$  与  $X_{1} - X_{2}$  不相互独立

D.  $X_{1} + X_{2}$  与  $X_{1} - X_{2}$  相关

超越卷卷八

（16）已知随机变量  $X\sim \mathrm{P}(1)$  ，记  $Y = \arctan X,Z = 2\operatorname {arccot}X$  ，则相关系数  $\rho_{YZ} =$

张宇八套卷卷七

8. 设存在非零常数  $a$  使得  $P\{aX + Y = 0\} = 1$ ，则随机变量  $X$  与  $Y$  的相关系数  $\rho$  满足

A.  $\rho = \frac{a}{|a|}$ .

B.  $\rho = -\frac{a}{|a|}$ .

C.  $-1 < \rho < 1$

D.  $|\rho| = |a|$ .

李永乐三套卷过线版

16. 设总体  $X$  的数学期望  $EX = \mu$ ，方差  $DX = \sigma^2, X_1, X_2, \dots, X_n$  为来自总体  $X$  的简单随机样本， $\overline{X} = \frac{1}{n}\sum_{i=1}^{n}X_i$ ，则  $X_i - \overline{X}$  与  $X_j - \overline{X}$  的相关系数  $\rho (i \neq j, i, j = 1, 2, \dots, n) = \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_$ .

汤家凤八套卷卷六

10. 设总体  $X \sim N(1,4), X_1, X_2, X_3, X_4$  为来自总体  $X$  的简单随机样本， $Y_i = X_i - \overline{X} (i = 1,2,3,4)$ ，则  $\operatorname{Cov}(2Y_1 - Y_2, Y_3 + Y_4) = (\quad)$ .

A. -2

B. -1

C. 2

D. 1

# 李林六套卷卷三

9. 设  $X_{1}, X_{2}$  相互独立，且均服从参数为  $\frac{1}{2}$  的0-1分布，记  $U = -\left(X_{1} + X_{2}\right) + X_{1}X_{2}$ ， $V = -\left(X_{1} + X_{2}\right) - X_{1}X_{2}$ ，则  $\operatorname{Cov}(U, V) =$

A.  $\frac{1}{16}$ .

B.  $\frac{3}{16}$ .

C.  $\frac{5}{16}$ .

D.0.

# 超越卷卷五

（8）设随机变量  $X$  的密度函数为  $f(x) = ae^{\frac{x(2 - x)}{2}}(-\infty <  x <   + \infty)$  ，则  $\operatorname {E}(X^{2}\mathrm{e}^{X}) = (\quad)$

(A)  $5 \mathrm{e}^{\frac{1}{2}}$

(B)  $3\mathrm{e}^{\frac{1}{2}}$

(C)  $5 \mathrm{e}^{\frac{3}{2}}$

(D)  $3 \mathrm{e}^{\frac{3}{2}}$

# 汤家凤八套卷

9. 设总体  $X$  的概率密度函数为  $f(x) = k\mathrm{e}^{2x - x^2}, X_1, X_2, \dots, X_n$  为来自总体  $X$  的简单随机样本，则  $E(X_1S^2) = (\quad)$ .

A.  $\frac{1}{2}$

B. 1

C.  $\frac{1}{2 n}$

D.  $\frac{1}{n}$

欧几里得

10. 设  $X_{1}, X_{2}, \dots, X_{n}$  是来自总体  $X \sim N(0,1)$  的简单随机样本，则下列说法正确的是（）

(A)  $E(X_{1}S^{2}) = 0,E\big(\overline{X}^{2}S^{4}\big) > \frac{1}{n}.$

(B)  $E\big(X_{1}S^{2}\big)\neq 0,E\big(\overline{X}^{2}S^{4}\big) > \frac{1}{n}.$

(C)  $E(X_{1}S^{2}) = 0,E\big(\overline{X}^{2}S^{4}\big) <   \frac{1}{n}.$

(D)  $E(X_{1}S^{2})\neq 0,E(\overline{X}^{2}S^{4}) <   \frac{1}{n}$

汤家凤八套卷卷六

9. 设随机变量  $X \sim U(0,1)$ , 当  $X = x (0 < x < 1)$  时,  $Y \sim E(x)$ , 则  $E(X^3 Y) = (\quad)$ .

A.  $\frac{1}{3}$

B.  $\frac{1}{4}$

C.  $\frac{2}{3}$

D.  $\frac{1}{2}$

汤家凤八套卷卷三

9. 设随机变量  $X$  的分布函数为  $F(x) = 0.4\Phi(2x - 1) + 0.6\Phi(x - 2)$ ，其中  $\Phi(x)$  为标准正态分布的分布函数，则  $E(X) = (\quad)$ .

A. 1.4

B. 1.2

C. 1

D. 0.8

张宇八套卷卷二

9. 设随机变量  $X$  服从参数为  $\mu, \sigma^2$  的正态分布，其概率密度为  $f(x)$ ，则  $\int_{-\infty}^{+\infty} f(x) \ln f(x) \mathrm{d}x$

A.与  $\mu$  有关，与  $\sigma$  无关.

B.与  $\mu$  有关，与  $\sigma$  有关

C.与  $\mu$  无关，与  $\sigma$  有关.

D.与  $\mu$  无关，与  $\sigma$  无关

# 数理统计

# 三大分布的判断

$\chi^2$  分布：设  $X_{1}, X_{2}, \dots, X_{n}$  相互独立且都服从标准正态分布  $N(0,1)$ ，则称统计量  $\chi^2 = X_1^2 + X_2^2 + \dots + X_n^2$  服从自由度为  $n$  的  $\chi^2$  分布，记为  $\chi^2 \sim \chi^2(n)$

可加性：设  $\chi_1^2\sim \chi^2 (n_1)$  ，  $\chi_2^2\sim \chi^2 (n_2)$  ，并且  $\chi_1^2,\chi_2^2$  相互独立，则有  $\chi_1^2 +\chi_2^2\sim \chi^2 (n_1 + n_2)$

期望和方差：  $E(\chi^2 (n)) = n$  ，  $D(\chi^2 (n)) = 2n$

$$
X \sim \chi^ {2} (2) \Longleftrightarrow X \sim E \left(\frac {1}{2}\right)
$$

$F$  分布：设  $U\sim \chi^2 (n_1)$  ，  $V\sim \chi^{2}(n_{2})$  ，且  $U,V$  相互独立，则称随机变量  $F = \frac{U / n_1}{V / n_2}$  服从自由度为  $(n_{1},n_{2})$  的  $F$  分布，记为  $F\sim F(n_{1},n_{2})$

性质：若  $F\sim F(n_{1},n_{2})$  ，则  $1 / F\sim F(n_{2},n_{1})$  （推论：  $F(1,1)$  与  $\frac{1}{F(1,1)}$  同分布）

$t$  分布：设  $X \sim N(0,1), Y \sim \chi^2(n)$ ，且  $X$  与  $Y$  相互独立，则称随机变量  $t = \frac{X}{\sqrt{Y / n}}$  服从自由度为  $n$  的  $t$  分布，记为  $t \sim t(n)$

特别地，若  $X, Z \sim N(0, 1)$  且相互独立， $\frac{X}{|Z|} \sim t(1)$  （经常考察）

若  $t\sim t(n)$  ，则  $t^2\sim F(1,n)$

$t$  分布的概率密度函数是对称的

# 通常需要利用到样本均值和样本方差的分布

设  $X \sim N(\mu, \sigma^2)$ ， $X_1, X_2, \dots, X_n$  是来自总体  $X$  的一个样本， $\overline{X}, S^2$  分别是样本均值和样本方差，则有如下结论

一：  $\overline{X}\sim N(\mu ,\sigma^2 /n)$  （可得  $\frac{\overline{X} - \mu}{\sigma / \sqrt{n}}\sim N(0,1))$  
二：  $\frac{(n - 1)S^2}{\sigma^2}\sim \chi^2 (n - 1)$  
三： $\overline{X}$  与  $S^2$  相互独立（可得  $\frac{\overline{X} - \mu}{\sigma / \sqrt{n}}$  与  $\frac{(n - 1)S^2}{\sigma^2}$  相互独立）  
四：  $\frac{\sqrt{n}(\overline{X} - \mu)}{S}\sim t(n - 1)$  
五：  $\frac{n\left(\overline{X} - \mu\right)^2}{S^2}\sim F(1,n - 1)$

超越卷卷二

（10）设随机变量  $X_{1}$  与  $X_{2}$  相互独立， $X_{1} \sim \mathrm{N}(0,1), X_{2} \sim \mathrm{N}(0,1)$ . 记  $T = \frac{X_{1} - X_{2}}{|X_{1} + X_{2}|}$ ，给定  $\alpha (0 < \alpha < 0.5)$ ，常数  $C$  满足  $\mathrm{P}\{T > C\} = \alpha$ ，则  $\mathrm{P}\left\{\frac{1}{T^2} > C^2\right\} = (\quad)$ .

(A)  $\alpha$

(B)  $1 - \alpha$

(C)  $2\alpha$  
(D)  $1 - 2\alpha$

# 超越卷卷七

(9) 设总体  $X$  服从标准正态分布， $X_{1}, X_{2}$  为的简单随机样本，则下列命题中：

①  $X_{1}^{2} + X_{2}^{2}\sim \operatorname {E}\left(\frac{1}{2}\right),\quad ② \frac{X_{1} + X_{2}}{\left|X_{1} - X_{2}\right|}\sim \mathrm{t}(1),\quad ③ \frac{1}{2} +\frac{X_{2}^{2}}{2X_{1}^{2}}\sim \mathrm{F}(2,1),$

正确的个数为（ ）.

(A) 0

(B) 1

(C) 2

(D) 3

# 超越卷卷四

（10）设  $X_{1}, X_{2}, X_{3}, X_{4}, X_{5}$  为来自总体  $X \sim \mathrm{N}(0, \sigma^{2})$  的简单随机样本， $\overline{X} = \frac{1}{5} \sum_{i=1}^{5} X_{i}, S^{2} = \frac{1}{4} \sum_{i=1}^{5} (X_{i} - \overline{X})^{2}$ ，则下列结论中：

①  $\sqrt{\frac{3}{2}}\frac{X_1 + X_2}{|X_3 + X_4 + X_5|} \sim t(1)$ ;

②  $\frac{5\overline{X}^2}{\sigma^2}\sim \chi^2 (5),$

③  $\frac{1}{\sigma^2} [(X_1 - 2X_2)^2 +(2X_3 + X_4)^2 ]\sim \chi^2 (2)$

④  $\frac{(X_1 - 2X_2)^2}{(2X_3 + X_5)^2} \sim \mathrm{F}(1,1)$

正确的个数有（ ）.

(A) 1

(B)2

(C)3

(D) 4

# 李林六套卷卷四

16. 设总体  $X$  与总体  $Y$  相互独立,且都服从  $N\left(0,\sigma^{2}\right)\left(\sigma >0\right),X_{1},X_{2},\dots ,X_{n}$  与  $Y_{1},Y_{2},\dots ,Y_{m}$  分别为来自总体  $X$  与  $Y$  的简单随机样本,若  $T = \frac{2\sum_{i = 1}^{n}X_{i}}{\sqrt{\sum_{i = 1}^{m}Y_{i}^{2}}}$  服从  $t$  分布，则  $\frac{n}{m} = \_ .$

# 利用卡方分布的数字特征

8. 设  $X_{1}, X_{2}, \cdots, X_{10}$  是来自标准正态总体  $X$  的简单随机样本， $Y = \frac{9}{10} \left( X_{10} - \frac{1}{9} \sum_{i=1}^{9} X_{i} \right)^{2}$ ，则  $D(Y) =$

A. 2 .

B. 1 .

C.  $\frac{1}{100}$ .

D.  $\frac{81}{100}$ .

李林六套卷卷五

10. 设  $X_{1}, X_{2}, \dots, X_{n}$  是来自总体  $X \sim N(0,1)$  的简单随机样本， $Y = \frac{1}{m} \left( \sum_{i=1}^{m} X_{i} \right) + \frac{1}{n - m} \left( \sum_{i=m+1}^{n} X_{i} \right)^{2} (m < n)$ ，则  $E(Y)$  与  $D(Y)$  分别为

A.  $0, n$

B.  $0,2$

C.  $n, 2 n$

D.2,4.

李林六套卷卷六

10. 设  $X_{1}, X_{2}, \dots, X_{2n}$  为来自总体  $X \sim N(0,1)$  的简单随机样本，记  $T_{1} = \sum_{i=1}^{2n}\left(X_{i} - \frac{1}{2n}\sum_{i=1}^{2n}X_{i}\right)^{2}$ ， $T_{2} = \frac{1}{2}\sum_{i=1}^{2n}X_{i}^{2} + \sum_{i=1}^{n}X_{2i-1}X_{2i}$ ，则

A.  $E\left(T_{1}\right) = 2 n, D\left(T_{2}\right) = n$

B.  $E\left(T_{1}\right) = n, D\left(T_{2}\right) = 2n - 1$

C.  $E\left(T_{2}\right) = n, D\left(T_{1}\right) = 2(2n - 1)$ .

D.  $E\left(T_{2}\right) = 2 n, D\left(T_{1}\right) = 2 n - 1$

分位点问题

重要结论

$$
F _ {\alpha} (m, n) F _ {1 - \alpha} (n, m) = 1
$$

新东方五套卷卷二

(10)已知正态总体  $X\sim N(\mu ,\sigma^2),(X_1,X_2,\dots ,X_{10})$  为简单随机样本，已知  $P(X > F_{\alpha}) = \alpha ,\overline{X}$  为样本均值，  $S^2$  为样本方差，  $Y = \frac{\overline{X} - \mu}{\sqrt{\frac{S}{\sqrt{10}}}}$  ，且已知  $P(Y^{2} > x) = \alpha ,0 <   \alpha <  1$  ，则  $x = ()$

(A)  $\frac{1}{F_{\alpha}(1,9)}$

(B)  $\frac{1}{F_{\alpha}(9,1)}$

(C)  $\frac{1}{F_{1 - \alpha}(1,9)}$

(D)  $\frac{1}{F_{1 - \alpha}(9,1)}$

超越卷卷一

（10）设  $(X_{1},X_{2},\dots ,X_{n})$  和  $(Y_{1},Y_{2},\dots ,Y_{n})$  为来自总体  $X\sim \mathrm{N}(\mu ,\sigma^2)$  的两个独立样本，其样本均值分别为  $\overline{X}$  和  $\overline{Y}$  ，样本方差分别为  $S_X^2$  和  $S_Y^2$  ，记  $W = S_X^2 +S_Y^2$  .对任意  $0 <   \alpha <  1$  ，以下各式中正确的是（）.

(A)  $\mathrm{P}\left\{\chi_{1 - \frac{\alpha}{2}}^2 (2n) < \frac{(n - 1)W}{\sigma^2} < \chi_{\frac{\alpha}{2}}^2 (2n)\right\} = 1 - \alpha$  
(B)  $\mathrm{P}\left\{\chi_{1 - \frac{\alpha}{2}}^2 (2n - 2) < \frac{(n - 1)W}{\sigma^2} < \chi_{\frac{\alpha}{2}}^2 (2n - 2)\right\} = 1 - \alpha$  
(C)  $\mathrm{P}\left\{-t_{\frac{\alpha}{2}}(2n) < \frac{\sqrt{n}(\overline{X} - \overline{Y})}{W} < t_{\frac{\alpha}{2}}(2n)\right\} = 1 - \alpha$  
(D)  $\mathrm{P}\left\{-t_{\frac{\alpha}{2}}(2n - 2) < \frac{\sqrt{n}(\overline{X} - \overline{Y})}{W} < t_{\frac{\alpha}{2}}(2n - 2)\right\} = \alpha$

# 大数定律和中心极限定理

# 切比雪夫大数定律

设随机变量  $X_{1}, X_{2}, \dots, X_{n}, \dots$  相互独立，数学期望  $EX_{k}$  和方差  $DX_{k}$  都存在，并且方差有公共上界（即  $DX_{k} \leqslant M$  ， $k = 1, 2, \dots$ ）则对于任意正数  $\varepsilon$  ， $\lim_{n \to \infty} P\left\{\left|\frac{1}{n}\sum_{k=1}^{n} X_{k} - E\left(\frac{1}{n}\sum_{k=1}^{n} X_{k}\right)\right| < \varepsilon\right\} = 1$

（即  $\frac{1}{n}\sum_{k = 1}^{n}X_{k}\xrightarrow{P}E\left(\frac{1}{n}\sum_{k = 1}^{n}X_{k}\right)$  或  $\lim_{n\to \infty}\frac{1}{n}\sum_{k = 1}^{n}X_{k}\stackrel {P}{=}E\left(\frac{1}{n}\sum_{k = 1}^{n}X_{k}\right)$

注：伯努利大数定律和辛钦大数定律都是切比雪夫大数定律的特殊情形，故只需记住切比雪夫大数定律

# 切比雪夫不等式

设随机变量  $X$  具有数学期望  $EX = \mu$  ，方差  $DX = \sigma^2$  ，则对于任意正数  $\varepsilon$  ，不等式  $P\{|X - \mu |\geqslant \varepsilon \} \leqslant \frac{\sigma^2}{\varepsilon^2}$  成立注：由  $P\{|X - \mu |\geqslant \varepsilon \} \leqslant \frac{\sigma^2}{\varepsilon^2}$  可得  $P\{|X - \mu | <   \varepsilon \} \geqslant 1 - \frac{\sigma^2}{\varepsilon^2}$

列维一林德伯格定理：设随机变量  $X_{1}, X_{2}, \dots, X_{n}, \dots$  相互独立，服从同一分布，且具有数学期望和方差  $E(X_{k}) = \mu, D(X_{k}) = \sigma^{2} > 0 (k = 1, 2, \dots)$ ，则对于任意的  $x$ ，恒有  $\lim_{n \to \infty} P\left\{\frac{1}{\sigma \sqrt{n}} \left( \sum_{k=1}^{n} X_{k} - n \mu \right) \leqslant x\right\} = \Phi(x)$  当  $n$  很多大时， $\frac{1}{\sigma \sqrt{n}} \left( \sum_{k=1}^{n} X_{k} - n \mu \right)$  近似地服从  $N(0,1)$

注：棣莫弗—拉普拉斯定理是列维—林德伯格定理的特殊情形，故只需记住列维—林德伯格定理

李林六套卷卷四

10. 设  $X_{1}, X_{2}, \dots, X_{n}$  为来自总体  $X$  的简单随机样本,  $X$  服从参数  $\lambda = 1$  的泊松分布,  $\Phi(x)$  为  $N(0,1)$  的分布函数, 则  $\lim_{n\to \infty}P\left\{\sum_{k = 1}^{n}X_{k}\leq n\right\} =$

A.  $\Phi(0)$ .

B.  $\Phi \left(\frac{1}{2}\right)$

C.  $\Phi(1)$ .

D.  $\Phi (\sqrt{2})$

# 张宇八套卷

9. 设生产每件产品的时间服从指数分布，且平均时间为10分钟，生产各件产品的时间相互独立，由中心极限定理，在15小时至20小时之间生产100件产品的概率约为

A.  $\Phi (2) - \Phi (1)$

B.  $2\Phi (1) - \Phi (2)$

C.  $\Phi (1) + \Phi (2) - 1$

D.  $2[\varPhi(1)-\varPhi(-2)]$

# 新东方五套卷卷一

(10) 设  $\Phi(x)$  为标准正态分布函数， $X_{i} = \begin{cases} 0, & A \text{不发生}, \\ 1, & A \text{发生} \end{cases} (i = 1,2,\dots,100)$ ，且  $P(A) = 0.8$ ， $X_{1}, X_{2}, \dots, X_{100}$  相互独立，令  $Y = \sum_{i=1}^{100} X_{i}$ ，则由中心极限定理知  $Y$  的分布函数  $F(y)$  近似于（）

(A)  $\Phi (y)$

(B)  $\Phi \left(\frac{y - 80}{4}\right)$

(C)  $\Phi (16y + 8)$

(D)  $\Phi (4y + 80)$

# 超越卷卷七

(16) 设总体  $X \sim \mathrm{N}(0, \sigma^2), (X_1, \dots, X_9)$  为来自总体  $X$  的简单随机样本， $\overline{X}$  为样本均值， $S^2$  为样本方差，则根据切比雪夫不等式估计概率  $\mathrm{P}\{-\sigma^2 < 9\overline{X}^2 + S^2 < 5\sigma^2\} \geqslant \_$ .

# 参数估计

最大似然估计

使得似然函数  $L(\theta) = f(x_{1};\theta)\dots f(x_{n};\theta)$  达到最大的  $\theta$  就是最大似然估计

二维情形：  $L(\theta) = f(x_{1},y_{1};\theta)\dots f(x_{n},y_{n};\theta)$

张宇八套卷卷三

10.设  $(X_{1},Y_{1}),(X_{2},Y_{2}),\dots ,(X_{n},Y_{n})$  是来自总体  $(X,Y)$  的简单随机样本，且  $(X,Y)\sim f(x,y) = \left\{ \begin{array}{ll}\frac{1}{2\theta^2}\mathrm{e}^{-\frac{2x + y}{2\theta}}, & x > 0,y > 0,\\ 0, & \text{其他，} \end{array} \right.$  其中  $\theta$  为大于0的参数.记  $\overline{X} = \frac{1}{n}\sum_{i = 1}^{n}X_{i},\overline{Y} = \frac{1}{n}\sum_{j = 1}^{n}Y_{j}$  ，则  $\theta$  的最大似

然估计量  $\hat{\theta}$  与  $D(\hat{\theta})$  分别为

A.  $\overline{X} +\frac{\overline{Y}}{2},\frac{\theta^2}{4n}$

B.  $\frac{\overline{X}}{2} + \frac{\overline{Y}}{4}, \frac{\theta^2}{2n}$ .

C.  $\overline{X} + \frac{\overline{Y}}{2}, \frac{\theta^2}{2n}$ .

D.  $\frac{\bar{X}}{2} + \frac{\bar{Y}}{4}, \frac{\theta^2}{4n}$ .

10.【答案】B

【分析】设  $(X_{1},Y_{1}),(X_{2},Y_{2}),\dots ,(X_{n},Y_{n})$  的观测值为  $(x_{1},y_{1}),(x_{2},y_{2}),\dots ,(x_{n},y_{n})$  ，则似然函数为

$$
L (\theta) = \left\{ \begin{array}{l l} { \frac {1}{2 ^ {n} \bullet \theta^ {2 n}} \mathrm {e} ^ {- \frac {1}{\theta} \sum_ {i = 1} ^ {n} x _ {i} - \frac {1}{2 \theta} \sum_ {j = 1} ^ {n} y _ {j}},} & {x _ {i} > 0, y _ {j} > 0, i, j = 1, 2, \dots ,} \\ {0,} & {\text {其 他}.} \end{array} \right.
$$

当  $x_{i} > 0, y_{j} > 0$  时，  $\ln L(\theta) = -n\ln 2 - 2n\ln \theta - \frac{1}{\theta}\sum_{i=1}^{n}x_{i} - \frac{1}{2\theta}\sum_{j=1}^{n}y_{j},$

$$
\frac {\mathrm {d} [ \ln L (\theta) ]}{\mathrm {d} \theta} = - \frac {2 n}{\theta} + \frac {1}{\theta^ {2}} \sum_ {i = 1} ^ {n} x _ {i} + \frac {1}{2 \theta^ {2}} \sum_ {j = 1} ^ {n} y _ {j},
$$

令  $\frac{\mathrm{d}[\ln L(\theta)]}{\mathrm{d}\theta} = 0$  ，解得

$$
\theta = \frac {1}{2 n} \left(\sum_ {i = 1} ^ {n} x _ {i} + \frac {1}{2} \sum_ {j = 1} ^ {n} y _ {j}\right).
$$

因此  $\theta$  的最大似然估计量为

$$
\hat {\theta} = \frac {1}{2 n} \left(\sum_ {i = 1} ^ {n} X _ {i} + \frac {1}{2} \sum_ {j = 1} ^ {n} Y _ {j}\right) = \frac {\bar {X}}{2} + \frac {\bar {Y}}{4}.
$$

李永乐三套卷名校版

9. 设总体  $X$  的概率密度为

$$
f (x; \theta) = \left\{ \begin{array}{l l} \frac {1}{| \theta |}, & \theta \leqslant x \leqslant \theta + | \theta |, \\ 0, & \text {其 他}. \end{array} \right.
$$

从  $X$  中抽得简单随机样本： $X_{1}, X_{2}, \dots, X_{n}, \overline{X}$  为样本均值. 如果  $\theta < 0, \theta$  的最大似然估计为  $\hat{\theta}_{1}$ ，如果  $\theta > 0, \theta$  的最大似然估计为  $\hat{\theta}_{2}$ ，则

A.  $\hat{\theta}_{1} = \min_{1\leqslant i\leqslant n}X_{i},\hat{\theta}_{2} = \max_{1\leqslant i\leqslant n}X_{i}.$

B.  $\widehat{\theta}_{1} = 2\overline{X}, \widehat{\theta}_{2} = \frac{2}{3}\overline{X}$

C.  $\hat{\theta}_{1} = \min_{1\leqslant i\leqslant n}X_{i},\hat{\theta}_{2} = \frac{1}{2}\max_{1\leqslant i\leqslant n}X_{i}.$

D.  $\hat{\theta}_{1} = \max_{1\leqslant i\leqslant n}X_{i},\hat{\theta}_{2} = \min_{1\leqslant i\leqslant n}X_{i}.$

矩估计

$$
\left\{ \begin{array}{l} E (X) = \frac {1}{n} \left(X _ {1} + \dots + X _ {n}\right) \\ E \left(X ^ {2}\right) = \frac {1}{n} \left(X _ {1} ^ {2} + \dots + X _ {n} ^ {2}\right) \\ \dots \\ E \left(X ^ {k}\right) = \frac {1}{n} \left(X _ {1} ^ {k} + \dots + X _ {n} ^ {k}\right) \end{array} \right.
$$

两个未知参数  $\left\{ \begin{array}{l} E(X) = \frac{1}{n} (X_1 + \dots + X_n) \\ E(X^2) = \frac{1}{n} (X_1^2 + \dots + X_n^2) \end{array} \right.$

一个未知参数  $E(X) = \frac{1}{n} (X_1 + \dots +X_n)$

李永乐六套卷

# 22.（本题满分12分）

已知随机变量  $X$  的概率密度为

$$
f (x; \theta) = \left\{ \begin{array}{c c} \frac {4 x ^ {2}}{\theta^ {3} \sqrt {\pi}} \mathrm {e} ^ {- (\frac {x}{\theta}) ^ {2}}, & x > 0, \\ 0, & x \leqslant 0. \end{array} \right.
$$

其中  $\theta > 0$  是未知参数， $X_{1}, X_{2}, \dots, X_{n}$  是  $X$  的简单随机样本.

（1）求  $\theta$  的矩估计量和最大似然估计量  $\hat{\theta}$

# 假设检验与置信区间

设  $X_{1}, X_{2}, X_{3}$  是来自总体  $N(\mu, 4^{2})$  的一个样本

根据样本值  $x_{1} = 1.1, x_{2} = 1.2, x_{3} = 1.5$

来检验  $H_0$  ：  $\mu = 1$  ，  $H_{1}$  ：  $\mu \neq 1$

如果  $|\bar{x} - 1|$  足够小  $(\bar{x} = \frac{x_1 + x_2 + x_3}{3})$ ，可以接受  $H_0: \mu = 1$

那怎样算足够小？需要建立一个标准！

衡量  $|\overline{x} - 1|$  大小，可变为衡量  $\left|\frac{\overline{x} - 1}{4 / \sqrt{3}}\right|$  大小（即  $\left|\frac{\overline{x} - 1}{\sigma^2 / \sqrt{n}}\right|$ ）

选取  $k$  ，当  $\left|\frac{\bar{x} - 1}{4 / \sqrt{3}}\right| \geqslant k$  ，就认为拒绝  $H_{0}$  ；当  $\left|\frac{\bar{x} - 1}{4 / \sqrt{3}}\right| < k$  ，就认为接受  $H_{0}$

令  $P\left\{\left|\frac{\overline{X} - 1}{4 / \sqrt{3}}\right| \geqslant k\right\} = \alpha$  ，这里的  $\alpha$  为显著水平，得  $k = z_{\frac{\alpha}{2}}$

接受域  $\left|\frac{\overline{X} - \mu_0}{4 / \sqrt{3}}\right| < z_{\frac{\alpha}{2}} \Longleftrightarrow \overline{X} - \frac{4}{\sqrt{3}} z_{\frac{\alpha}{2}} < \mu_0 < \overline{X} + \frac{4}{\sqrt{3}} z_{\frac{\alpha}{2}}$

得双侧置信区间  $\left(\overline{X} -\frac{4}{\sqrt{3}} z_{\frac{\alpha}{2}},\overline{X} +\frac{4}{\sqrt{3}} z_{\frac{\alpha}{2}}\right)$  ，这里的  $1 - \alpha$  为置信水平（也叫置信度）

# 双边检验

设  $X_{1}, X_{2}, \dots, X_{n}$  是来自总体  $N(\mu, \sigma^{2})$  的一个样本

情形一： $\sigma^2$  为已知， $\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}} \sim N(0,1)$  作为统计量

双边检验  $H_0$  ：  $\mu = \mu_0$  ，  $H_{1}$  ：  $\mu \neq \mu_0$

选取  $k$  ，使得  $\left|\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}}\right| \geqslant k$  ，就拒绝  $H_0$  ；  $\left|\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}}\right| < k$  ，就接受  $H_0$

令  $P\left\{\left|\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}}\right| \geqslant k\right\} = \alpha$  ，这里的  $\alpha$  为显著水平，得  $k = z_{\frac{\alpha}{2}}$

接受域  $\left|\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}}\right| < z_{\frac{\alpha}{2}} \Longleftrightarrow \overline{X} - \frac{\sigma}{\sqrt{n}} z_{\frac{\alpha}{2}} < \mu_0 < \overline{X} + \frac{\sigma}{\sqrt{n}} z_{\frac{\alpha}{2}}$

得双侧置信区间  $\left(\overline{X} -\frac{\sigma}{\sqrt{n}} z_{\frac{\alpha}{2}},\overline{X} +\frac{\sigma}{\sqrt{n}} z_{\frac{\alpha}{2}}\right),1 - \alpha$  为置信度

情形二： $\sigma^2$  为未知， $\frac{\overline{X} - \mu_0}{S / \sqrt{n}} \sim t(n - 1)$  作为统计量

双边检验  $H_0$  ：  $\mu = \mu_0$  ，  $H_{1}$  ：  $\mu \neq \mu_0$

选取  $k$  ，使得  $\left|\frac{\overline{X} - \mu_0}{S / \sqrt{n}}\right| \geqslant k$  ，就拒绝  $H_0$  ；  $\left|\frac{\overline{X} - \mu_0}{S / \sqrt{n}}\right| < k$  ，就接受  $H_0$

令  $P\left\{\left|\frac{\overline{X} - \mu_0}{S / \sqrt{n}}\right| \geqslant k\right\} = \alpha$  ，这里的  $\alpha$  为显著水平，得  $k = t_{\frac{\alpha}{2}}(n - 1)$

接受域  $\left|\frac{\overline{X} - \mu_0}{S / \sqrt{n}}\right| < t_{\frac{\alpha}{2}}(n - 1) \Longleftrightarrow \overline{X} - \frac{S}{\sqrt{n}} t_{\frac{\alpha}{2}}(n - 1) < \mu_0 < \overline{X} + \frac{S}{\sqrt{n}} t_{\frac{\alpha}{2}}(n - 1)$

得置信区间  $\left(\overline{X} -\frac{S}{\sqrt{n}} t_{\frac{\alpha}{2}}(n - 1),\overline{X} +\frac{S}{\sqrt{n}} t_{\frac{\alpha}{2}}(n - 1)\right),$ $1 - \alpha$  为置信度

# 单边检验

情形一： $\sigma^2$  已知， $\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}} \sim N(0,1)$  作为统计量

单边检验  $H_0$  ：  $\mu \leqslant \mu_0$  ，  $H_{1}$  ：  $\mu >\mu_{0}$

选取  $k$  ，使得  $\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}} \geqslant k$  ，就拒绝  $H_0$  ；  $\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}} < k$  ，就接受  $H_0$

令  $P\left\{\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}} \geqslant k\right\} = \alpha$  ，这里的  $\alpha$  为显著水平，得  $k = z_{\alpha}$

接受域  $\frac{\overline{X} - \mu_0}{\sigma / \sqrt{n}} < z_{\alpha} \Longleftrightarrow \overline{X} - z_{\alpha}\sigma / \sqrt{n} < \mu_0$

得单侧置信区间  $\left(\overline{X} -\frac{\sigma}{\sqrt{n}} z_{\alpha}, + \infty\right)$

单边检验  $H_0$  ：  $\mu \geqslant \mu_0$  ，  $H_{1}$  ：  $\mu <  \mu_{0}$

选取  $k$ , 使得  $\frac{\bar{X} - \mu_0}{\sigma / \sqrt{n}} \leqslant k$ , 就拒绝  $H_0; \frac{\bar{X} - \mu_0}{\sigma / \sqrt{n}} > k$ , 就接受  $H_0$

情形二： $\sigma^2$  未知， $\frac{\overline{X} - \mu}{S / \sqrt{n}} \sim t(n - 1)$  作为统计量

单边检验  $H_{0}$  ：  $\mu \leqslant \mu_0$  ，  $H_{1}$  ：  $\mu >\mu_{0}$

选取  $k$  ，使得  $\frac{\overline{X} - \mu}{S / \sqrt{n}}\geqslant k$  ，就拒绝  $H_{0}$

令  $P\left\{\frac{\overline{X} - \mu}{S / \sqrt{n}} \geqslant k\right\} = \alpha$  ，这里的  $\alpha$  为显著水平，得  $k = t_{\alpha}(n - 1)$

接受域  $\frac{\overline{X} - \mu}{S / \sqrt{n}} < t_{\alpha}(n - 1) \Longleftrightarrow \overline{X} - t_{\alpha}(n - 1) S / \sqrt{n} < \mu_0$

得单侧置信区间  $\left(\overline{X} - t_{\alpha}(n - 1) S / \sqrt{n}, +\infty\right)$

# 两类错误

第一类错误：  $H_0$  为真，拒绝  $H_0$  （犯第一类错误的概率就是在拒绝域的概率）（弃真）

第二类错误： $H_0$  为假，接受  $H_0$  （犯第二类错误的概率就是不在拒绝域的概率）（取伪）

新东方五套卷卷五

(10) 设简单随机样本  $X_{1}, X_{2}, \dots, X_{n}$  来自正态总体  $X \sim N(\mu, \sigma^{2})$ ，其中  $\mu, \sigma^{2}$  均未知，令  $\bar{X} = \frac{1}{n} \sum_{i=1}^{n} X_{i}, S = \sqrt{\frac{1}{n-1} \sum_{i=1}^{n} (X_{i} - \bar{X})^{2}}, S^{*} = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (X_{i} - \bar{X})^{2}}$ ，在检验假设  $H_{0}: \mu = \mu_{0}$  时，需要用统计量（）

(A)  $T = \frac{\sqrt{n - 1}(\bar{X} - \mu_0)}{S}$

(B)  $U = \frac{\sqrt{n - 1}(\bar{X} - \mu_0)}{\sigma}$

(C)  $T = \frac{\sqrt{n - 1}(\bar{X} - \mu_0)}{S^*}$

(D)  $U = \frac{\sqrt{n}(\bar{X} - \mu_0)}{\sigma}$

张宇八套卷

9. 设总体  $X$  的数学期望存在且方差为 1，根据来自  $X$  的容量为 16 的简单随机样本测得样本均值为  $a$ ， $\Phi(1.96) = 0.975$ ，则  $X$  的数学期望的置信度等于 0.95 的置信区间为

A.  $(a - 0.49, a + 0.49)$ .

B.  $(a - 0.327, a + 0.327)$ .

C.  $(a - 0.196, a + 0.196)$ .

D.  $(a - 0.025, a + 0.025)$ .

超越卷卷八

（10）设  $\overline{X}$  为来自总体  $X\sim \mathrm{N}(\mu ,\sigma^2)$  的一个简单随机样本的样本均值，若已知在置信水平  $1 - \alpha$  下， $\mu$  的置信区间的长度为2，则在显著性水平  $\alpha$  下，对于假设检验问题  $H_0:\mu = 1,H_1:\mu \neq 1$  ，要使得检验结果接受  $H_{0}$  ，则应有（ ）.

(A)  $\overline{X} \in (-1, 1)$

(B)  $\overline{X} \in (-1, 3)$

(C)  $\overline{X} \in (-2, 0)$

(D)  $\overline{X} \in (0, 2)$

新东方五套卷卷三

(10) 假设总体  $X \sim N(\mu, \sigma^2)$ , 其中  $\sigma^2$  已知, 检验假设:  $H_0: \mu \leqslant \mu_0, H_1: \mu > \mu_0$ , 如果取  $H_0$  的拒绝域为  $\{(x_1, x_2, \dots, x_n) | \overline{X} > c\}$ , 其中  $\overline{X}$  为样本均值, 那么对固定的样本容量  $n$ , 犯第一类错误的概率  $\alpha(\quad)$

(A) 随  $c$  的增大而减小

(B) 随  $c$  的增大而增大

(C) 随  $c$  的增大保持不变

(D) 增减性不定

张宇八套卷卷一

10. 设总体  $X \sim N(\mu, 1), H_0: \mu = 0, H_1: \mu = 1$ . 来自总体  $X$  的样本容量为 9 的简单随机样本均值为  $\overline{X}$ ，设拒绝域为  $W = \{\overline{X} \geqslant 0.55\}$ ，则不犯第二类错误的概率为

A.  $1 - \Phi (1.35)$

B.  $\varPhi(1.35)$  ：

C.  $\varPhi(1.65)$

D.  $1 - \varPhi (1.65)$

# 李艳芳三套卷卷一

(10) 设总体  $X$  服从正态分布  $N\left(\mu, \sigma^{2}\right)$ , 其中  $\mu$  未知. 第一组来自总体  $X$  的简单随机样本的样本方差等于 10 ,第二组来自总体  $X$  的简单随机样本的样本方差等于 8 ,两组样本的样本容量相同, 利用第一组样本得到  $\sigma^{2}$  的置信度为 0.95 的置信区间的长度为  $L_{1}$ , 则下列说法中, 正确的是 ( )

（A）利用第一组样本得到  $\sigma^2$  的置信度为0.90的置信区间的长度大于  $L_{1}$  
（B）利用第一组样本得到  $\sigma^2$  的置信度为0.98的置信区间的长度小于  $L_{1}$  
（C）利用第二组样本得到  $\sigma^2$  的置信度为0.95的置信区间的长度小于  $0.8L_{1}$  
（D）利用第二组样本得到  $\sigma^2$  的置信度为0.98的置信区间的长度大于  $0.8L_{1}$

张宇八套卷卷六

9. 设总体  $X$  的数学期望存在且方差为 1，根据来自  $X$  的容量为 16 的简单随机样本测得样本均值为  $a$ ， $\Phi(1.96) = 0.975$ ，则  $X$  的数学期望的置信度等于 0.95 的置信区间为

A.  $(a - 0.49, a + 0.49)$ .

B.  $(a - 0.327, a + 0.327)$ .

C.  $(a - 0.196, a + 0.196)$ .

D.  $(a - 0.025, a + 0.025)$ .