# p-积分（反常积分）敛散性结论与应用 
---
## 一、两类基本p-积分的敛散性 
### ① 瑕积分（无界函数反常积分）：$\displaystyle \int_{0}^{1} \frac{1}{x^p} \, dx$ $$ \int_{0}^{1} \frac{1}{x^p} \, dx \begin{cases} \text{收敛}, & 0 < p < 1, \\ \text{发散}, & p \ge 1. \end{cases} $$ - **关键说明**：$p=1$ 是临界值，此时 $$ \int_{0}^{1} \frac{1}{x} \, dx = \lim_{\varepsilon \to 0^+} \int_{\varepsilon}^{1} \frac{1}{x} \, dx = \lim_{\varepsilon \to 0^+} (\ln 1 - \ln \varepsilon) = +\infty $$ 故积分发散。 
>记忆：看下限是0，很小，所以p越小越收敛
--- 
### ② 无穷区间反常积分：$\displaystyle \int_{1}^{+\infty} \frac{1}{x^p} \, dx$ $$ \int_{1}^{+\infty} \frac{1}{x^p} \, dx \begin{cases} \text{收敛}, & p > 1, \\ \text{发散}, & p \le 1. \end{cases} $$ - **关键说明**：$p=1$ 是临界值，此时 $$ \int_{1}^{+\infty} \frac{1}{x} \, dx = \lim_{b \to +\infty} \int_{1}^{b} \frac{1}{x} \, dx = \lim_{b \to +\infty} (\ln b - \ln 1) = +\infty $$ 故积分发散。
>记忆：看上限是正无穷，所以p越大越收敛

--- 
## 二、等价无穷小/无穷大的推广应用 
### 1. 瑕积分中的等价无穷小替换 当 $x \to 0^+$ 时，有 $\sin x \sim x$，这意味着 $\sin x$ 与 $x$ 趋于 $0$ 的“速度”相同。因此，瑕积分 $$ \int_{0}^{1} \frac{1}{\sin^p x} \, dx \quad (\text{或 } \int_{0}^{\frac{\pi}{2}} \frac{1}{\sin^p x} \, dx) $$的敛散性与 $\int_{0}^{1} \frac{1}{x^p} \, dx$ 一致： 
- 推广：凡是与 $x$ 趋于 $0$ 的“速度”相同的函数 $f(x)$（即 $f(x) \sim x$ 当 $x \to 0^+$），均可按此方法讨论其 $p$ 次幂倒数的瑕积分敛散性。 
- ---
- ### 2. 无穷区间积分中的等价无穷大替换 当 $x \to +\infty$ 且 $a>0$ 时，$ax+b$ 与 $x$ 趋于 $+\infty$ 的“速度”相同。因此，当 $ax+b \ge k>0$ 时，无穷积分 $$ \int_{1}^{+\infty} \frac{1}{(ax+b)^p} \, dx $$ 的敛散性与 $\int_{1}^{+\infty} \frac{1}{x^p} \, dx$ 一致： $$ \int_{1}^{+\infty} \frac{1}{(ax+b)^p} \, dx \begin{cases} \text{收敛}, & p > 1, \\ \text{发散}, & p \le 1. \end{cases} $$ > 原理验证：由极限形式的比较判别法， 
$$ > \lim_{x \to +\infty} \frac{(ax+b)^p}{(ax)^p} = \lim_{x \to +\infty} \left( 1 + \frac{b}{ax} \right)^p = 1 > $$ 
故二者是同阶无穷大，积分敛散性相同

--- 
## 补充：$\int \frac{lnx}{x^P}$
>因为lnx的趋近速度太慢了，所以对原积分都没有影响，可以等价看作$\displaystyle \int_{0}^{1} \frac{1}{x^p} \, dx$ 和$\displaystyle \int_{1}^{+\infty} \frac{1}{x^p} \, dx$


