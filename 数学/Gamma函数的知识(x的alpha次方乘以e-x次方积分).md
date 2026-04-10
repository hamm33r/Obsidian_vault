---
tags:
  - 定积分
---
p254
  > 计算积分时，若能用上“$\Gamma$ 函数”的知识，会既快速又准确。 
 
### (1) 定义 $$ \Gamma(\alpha) = \int_{0}^{+\infty} x^{\alpha-1} \mathrm{e}^{-x} \mathrm{d}x \xlongequal{x = t^2} 2\int_{0}^{+\infty} t^{2\alpha-1} \mathrm{e}^{-t^2} \mathrm{d}t \quad (x, t > 0) $$
## 有递推式$$\Gamma(\alpha+1)=\alpha\Gamma(\alpha)$$
### 当$e^{-x}$e的次方是一次时$$\Gamma(n+1)=n!$$
### 当$e^{-t^2}$e的次方是二次时### 📐 $\Gamma$ 函数递推应用公式 $$ \Gamma(\alpha+1) = \alpha\Gamma(\alpha), \quad \Gamma\left(\frac{1}{2}\right) = \sqrt{\pi}. $$ $$ \Gamma\left(\frac{3}{2}\right) = \Gamma\left(\frac{1}{2}+1\right) = \frac{1}{2}\Gamma\left(\frac{1}{2}\right) = \frac{1}{2}\sqrt{\pi}. $$ $$ \Gamma\left(\frac{5}{2}\right) = \Gamma\left(\frac{3}{2}+1\right) = \frac{3}{2}\Gamma\left(\frac{3}{2}\right) = \frac{3}{4}\sqrt{\pi}. $$