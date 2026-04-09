
 注 > 计算积分时，若能用上“$\Gamma$ 函数”的知识，会既快速又准确。 
 
### (1) 定义 $$ \Gamma(\alpha) = \int_{0}^{+\infty} x^{\alpha-1} \mathrm{e}^{-x} \mathrm{d}x \xlongequal{x = t^2} 2\int_{0}^{+\infty} t^{2\alpha-1} \mathrm{e}^{-t^2} \mathrm{d}t \quad (x, t > 0) $$
##### (2) 递推式 $$ \Gamma(\alpha+1) = \int_{0}^{+\infty} x^{\alpha} \mathrm{e}^{-x} \mathrm{d}x = -\int_{0}^{+\infty} x^{\alpha} \mathrm{d}(\mathrm{e}^{-x}) = \left. -x^{\alpha} \mathrm{e}^{-x} \right|_{0}^{+\infty} + \int_{0}^{+\infty} \mathrm{e}^{-x} \alpha x^{\alpha-1} \mathrm{d}x = \alpha\Gamma(\alpha) $$ 其中 $\Gamma(1)=1$，$\Gamma\left(\dfrac{1}{2}\right)=\sqrt{\pi}$，故 $$ \Gamma(n+1)=n!,\quad \Gamma(2)=1,\quad \Gamma\left(\dfrac{5}{2}\right)=\dfrac{3}{2}\cdot\dfrac{1}{2}\cdot\Gamma\left(\dfrac{1}{2}\right)=\dfrac{3}{4}\sqrt{\pi} $$
 
  
  --- 
  $$ \Gamma(1) = \int_{0}^{+\infty} \mathrm{e}^{-x} \mathrm{d}x = 1 $$ $$ \Gamma\left(\dfrac{1}{2}\right) = 2\int_{0}^{+\infty} \mathrm{e}^{-t^2} \mathrm{d}t = \sqrt{\pi} $$ > 左图：$y=\mathrm{e}^{-x}$ 在 $[0,+\infty)$ 上的积分（阴影面积）为 $1$ > 右图：$y=\mathrm{e}^{-t^2}$ 在 $[0,+\infty)$ 上的积分（阴影面积）为 $\dfrac{\sqrt{\pi}}{2}$ —— 为什么？例14.11会告诉我们