# Math Formula Markdown Tutorial

## 1. Inline VS Display

This is an example of inline formulae: $\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}​$

This is a formula in display mode:
$$
\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}
$$

## 2. Superscripts (^) or Subscripts (_)
$x_i^2​$                $x_{min}^2​$

## 3. Greek Letters

lower cases: $\alpha$ $\beta$ $\delta$ $\omega$

upper cases: $\Delta​$ $\Omega​$
$$
a := x^2-y^3+\cos(\theta)
$$

## 4. Multi-line

$$
f(x)=\sigma(x)=\frac{1}{1+e^{-x}}\\
f'(x)=f(x)(1-f(x))
$$

## 5. Multi-Cases
$$
f(n) =
\begin{cases}
n/2,  & \text{if $n$ is even} \\
3n+1, & \text{if $n$ is odd}
\end{cases}
$$

Note: "&" is for <u>alignment</u>

## 6. Fractions

${a+1\over b+1}​$ $\frac{a+1}{b+1}​$ $\cfrac{a}{b}​$ $\frac{a}{b}​$

## 7. Sums and Integrals

$\sum_1^n​$

$\sum_{i=0}^\infty i^2​$

$\prod​$ $\bigcup​$ $\iint​$ $\idotsint​$
$$
\iint\limits_{(x,y)\in D} f(x)
\mathrm{d}x\mathrm{d}y
$$

## 8. Matrixs

- matrix：无
- bmatrix：方括号
- vmatrix：竖线
- pmatrix：圆括号
- Bmatrix：花括号
- Vmatrix：双竖线

$$
\begin{bmatrix}
1 & 2 & 2 \\
2 & 3 & 4 \\
4 & 4 & 2
\end{bmatrix}
$$

$$
\begin{pmatrix}
1 & 2 & 2 \\
2 & 3 & 4 \\
4 & 4 & 2
\end{pmatrix}
$$

## 9. Radical Signs

$$
\sqrt[3]{\frac xy}
$$

$$
{x}^{\pi}
$$

$$
\sqrt[n]{\frac{x^2+\sqrt 2}{x+y}}
$$

## 10. Special Characters

$$\backslash​$$

## 11. Continued Fractions

$$
\underset{j=1}{\overset{\infty}{\LARGE\mathrm K}}\frac{a_j}{b_j}=\cfrac{a_1}{b_1+\cfrac{a_2}{b_2+\cfrac{a_3}{b_3+\ddots}}}
$$

# Activation Function

- Logistic/Sigmoid Function:

$$
f(x)=\sigma(x)=\frac{1}{1+e^{-x}}\\
f'(x)=f(x)(1-f(x))
$$

- Arctan Function:

$$
f(x)=\tan^{-1}(x)\\
f'(x)=\frac{1}{x^2+1}
$$

- ReLU (Rectified linear unit) Function:

$$
f(x_i) =
\begin{cases}
	ReLU(x_i) & \text{if } i \bmod 2 = 0 \\
	-ReLU(-x_i) & \text{if } i \bmod 2 \neq 0 
\end{cases}
$$

- Tanh Function:

$$
f(x)=\tanh(x)=\frac{(e^{x} - e^{-x})}{(e^{x} + e^{-x})}\\
f'(x)=1-f(x)^2
$$

- Binary Step Function:

$$
f(x) = \begin{cases}
	0 & \text{for } x < 0\\
	1 & \text{for } x \ge 0\end{cases}
$$

# Reference

[MathJax basic tutorial and quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

[Activation Function](https://en.wikipedia.org/wiki/Activation_function)
