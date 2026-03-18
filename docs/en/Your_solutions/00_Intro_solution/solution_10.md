# Mathematical Analysis: The Spiral Ant Path
**Pattern:** $1\text{m E}, \frac{1}{2}\text{m N}, \frac{1}{3}\text{m W}, \frac{1}{4}\text{m S}, \frac{1}{5}\text{m E}, \dots$

---

## 1. Objective
To determine the final $(x, y)$ coordinates of an ant moving in a rectangular spiral where each step is the reciprocal of the step number ($1/n$) and rotates 90° counter-clockwise.



---

## 2. Modeling the Movement
We can represent the directions using the Cartesian coordinate system:
* **East/West (x-axis):** Alternating steps $1, -1/3, 1/5, -1/7, \dots$
* **North/South (y-axis):** Alternating steps $1/2, -1/4, 1/6, -1/8, \dots$

---

## 3. Calculating the Coordinates

### Step A: Final X-Coordinate
The x-position is the sum of the odd-numbered steps with alternating signs:
$$x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$$
This is the famous **Leibniz formula for $\pi$**. We know that $\arctan(1) = \frac{\pi}{4} = 1 - \frac{1}{3} + \frac{1}{5} \dots$
**$$x = \frac{\pi}{4} \approx 0.785$$**

### Step B: Final Y-Coordinate
The y-position is the sum of the even-numbered steps with alternating signs:
$$y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots$$
We can factor out $1/2$:
$$y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)$$
The term in the parentheses is the **alternating harmonic series**, which converges to $\ln(2)$.
**$$y = \frac{1}{2} \ln(2) \approx 0.347$$**

---

## 4. Final Position
The ant's final destination is the point:
### **$$(x, y) = \left( \frac{\pi}{4}, \frac{1}{2} \ln(2) \right)$$**
**Decimal Approximation:** $(0.785, 0.347)$

---

## 5. Conclusion
* **Convergence:** Even though the standard harmonic series ($1 + 1/2 + 1/3 \dots$) diverges to infinity, the alternating signs cause this "spiral" to converge to a specific point.
* **Complex Connection:** This movement can be represented by the complex series $\sum_{n=1}^{\infty} \frac{i^{n-1}}{n}$, which is related to the complex logarithm $\ln(1+i)$.