# onzekerheids analyse en toleranties


$$x=\mu \pm \frac{\sigma}{\sqrt{N}}$$

$$\sigma = \left[ \frac{1}{N-1} \sum_{i=1}^N (x_i -\mu )^2  \right]^\frac{1}{2}$$

$$\frac{\sigma}{\sqrt{N}}$$

$$U(Z)=\left[ \left( \frac{\partial Z}{\partial A}\right)^2 U(A)^2 + \left( \frac{\partial Z}{\partial B}\right)^2 U(B)^2 + \left( \frac{\partial Z}{\partial C}\right)^2 U(C)^2 \right] ^\frac{1}{2}$$

$$U(Z)=\left[\left[ Z(A+u(A),B,C)-Z(A,B,C) \right]^2 + [\left[ Z(A,B+u(B),C)-Z(A,B,C) \right]^2 + [\left[ Z(A,B,C+u(C))-Z(A,B,C) \right]^2 \right]^\frac{1}{2}$$

$$\left( \frac{u(Z)}{Z} \right) ^2 = \frac{\left[ \left( \frac{\partial Z}{\partial A}\right)^2 U(A)^2 + \left( \frac{\partial Z}{\partial B}\right)^2 U(B)^2 + \left( \frac{\partial Z}{\partial C}\right)^2 U(C)^2 \right]}{Z^2}$$

$$= \frac{\left[ \left( \alpha A^{\alpha-1} B^{\beta} C^{-\gamma} \right)^2 U(A)^2 + \left(  A^{\alpha} \beta B^{\beta-1} C^{-\gamma} \right)^2 U(B)^2  +  \left( -A^{\alpha} B^{\beta} \gamma C^{-\gamma-1} \right)^2 U(C)^2 \right]}{\left( A^\alpha B^\beta C^{-\gamma} \right)^2}$$


$$= \left( \left( \alpha A^-1 \right)^2 u(A)^2 + \left( \beta B^-1 \right)^2 u(B)^2 + \left( \gamma C^-1 \right)^2 u(C)^2 \right) = \left( \left( \alpha \frac{U(A)}{A} \right)^2 +  \left( \beta \frac{U(B)}{B} \right)^2 +  \left( \gamma \frac{U(C)}{C} \right)^2 
\right) $$

