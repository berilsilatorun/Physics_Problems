## Problem 1. Vector Algebra (Step-by-Step Solution)

Given vectors: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

### a) Magnitude of each vector
The formula for the magnitude of a 3D vector is:

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

For $\vec{a}$:

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}
$$

For $\vec{b}$:

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}
$$

### b) The dot product $\vec{a} \cdot \vec{b}$

$$
\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3
$$

### c) The cross product $\vec{a} \times \vec{b}$

$$
\vec{a} \times \vec{b} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}
$$

$$
= \hat{i}(1 \cdot 1 - (-3)(-2)) - \hat{j}(2 \cdot 1 - (-3)(4)) + \hat{k}(2(-2) - 1 \cdot 4)
$$

$$
= \hat{i}(1 - 6) - \hat{j}(2 + 12) + \hat{k}(-4 - 4) = [-5, -14, -8]
$$

### d) The angle between vectors $\vec{a}$ and $\vec{b}$

$$
\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{3}{\sqrt{14} \sqrt{21}} = \frac{3}{\sqrt{294}}
$$

$$
\theta = \arccos\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ
$$