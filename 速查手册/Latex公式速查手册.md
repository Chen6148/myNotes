### 1.基本的运算符符号
拉丁字母（$x$、$y$、$z$）、阿拉伯数字（$1$、$2$、$3$）和运算符($+$、$-$、$*$、$/$、)均可以直接通过键盘输入获得；
其他无法直接从键盘输入的符号，如下所示:

| **运算符名称** | **运算符** | **lates形式** |
| :--: | :--: | :--: |
| 点乘号 | $\cdot$ | \\cdot |
| 叉乘号 | $\times$ | \\times |
| 除号 | $\div$ | \\div |
| 百分号 | $\%$ | \\% |
| 根号 | $\sqrt{x}$ | \\sqrt{x} |
| 分式 | $\frac{x}{y}$ | \\frac{x}{y} |
|单字符上标| $x^2$ | x^2 |
|单字符下标| $x_1$ | x_1 |
|多字符上标| $x^{21}$ | x^{21} |
|多字符下标| $x_{i, j}$ | x_{i, j} |
|向量| $\vec{a}$ | \\vec{a} |
|多字符向量（箭头向右）| $\overrightarrow{AB}$| \\overrightarrow{AB} |
|多字符向量（箭头向右）| $\overleftarrow{CD}$| \\overleftarrow{CD} |
### 2.数学表达式
2.1 **积分**

2.2 **极限**

2.3 **求和**

2.4 **乘积**

2.5 **上下标记**

2.6 **矩阵运算**

### 3.多行公式
通过`cases`环境实现公式的组合，`&`分隔公式和条件，还可以通过`\limits`来让`x→0`位于`lim`的正下方而非默认在`lim`符号的右下方显示;
>latex表达式：
```text
$$D(x) = \begin{cases}
\lim\limits_{x \to 0} \frac{a^x}{b+c}, & x<3 \\
\pi, & x=3 \\
\int_a^{3b}x_{ij}+e^2 \mathrm{d}x,& x>3 \\
\end{cases}$$
```

>latex显示效果：
$$D(x) = \begin{cases}
\lim\limits_{x \to 0} \frac{a^x}{b+c}, & x<3 \\
\pi, & x=3 \\
\int_a^{3b}x_{ij}+e^2 \mathrm{d}x,& x>3 \\
\end{cases}$$

---

### 4.长公式换行
$$\begin{split}
\cos 2x &= \cos^2x - \sin^2x \\
&=2\cos^2x-1
\end{split}$$


### 5.希腊字母（小写）
| **希腊字母** | **latex形式** | **希腊字母** | **latex形式** | **希腊字母** | **latex形式** | **希腊字母** | **latex形式** |
| :---: | :--- | :---: | :--- | :---: | :--- | :---: | :--- |
| $\alpha$ | \\alpha | $\theta$ | \\theta | $o$ | o | $\upsilon$ | \\upsilon |
| $\beta$ | \\bata | $\vartheta$ | \\vartheta | $\pi$ | \\pi | $\phi$ | \\phi |
| $\gamma$ | \\gamma | $\iota$ | \\iota | $\varpi$ | \\varpi | $\varphi$ | \\varphi |
| $\delta$ | \\delta | $\kappa$ | \\kappa | $\rho$ | \\rho | $\chi$ | \\chi |
| $\epsilon$ | \\epsilon | $\lambda$ | \\lambda | $\varrho$ | \\varrho | $\psi$ | \\psi |
| $\varepsilon$ | \\varepsilon | $\mu$ | \\mu | $\sigma$ | \\sigma | $\omega$ | \\omega |
| $\zeta$ | \\zeta | $\nu$ | \\nu | $\varsigma$ | \\varsima |  |  |
| $\eta$ | \\eta | $\xi$ | \\xi | $\tau$ | \\tau |  |  |
### 6.希腊字母（大写）
| **希腊字母** | **latex形式** | **希腊字母** | **latex形式** | **希腊字母** | **latex形式** | **希腊字母** | **latex形式** |
| :--: | :--- | :--: | :--- | :--: | :--- | :--: | :--- |
| $\Gamma$ | \\Gamma | $\Lambda$ | \\Lambda | $\Sigma$ | \\Sigma | $\Psi$ | \\Psi |
| $\Delta$ | \\Delta | $\Xi$ | \\Xi | $\Upsilon$ | \\Upsilon | $\Omega$ | \\Omega |
| $\Theta$ | \\Theta | $\Pi$ | \\Pi | $\Phi$ | \\Phi |  |  |
