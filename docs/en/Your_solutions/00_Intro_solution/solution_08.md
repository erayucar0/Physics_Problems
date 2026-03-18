# Mathematical Analysis: Definite Integrals
**Function:** $f(x) = \sin(x)$  
**Interval:** From $x = 0$ to $x = \pi$

---

## 1. Objective
To calculate the exact area under the curve of the sine function over one half-period (from 0 to $\pi$) using the Fundamental Theorem of Calculus.



---

## 2. Theoretical Framework
The area $A$ under a curve $f(x)$ between $x = a$ and $x = b$ is given by the definite integral:
$$A = \int_{a}^{b} f(x) \, dx$$

---

## 3. Step-by-Step Calculation

### Step A: Set up the Integral
Substitute the function and the limits of integration:
$$A = \int_{0}^{\pi} \sin(x) \, dx$$

### Step B: Find the Antiderivative
Recall that the derivative of $\cos(x)$ is $-\sin(x)$. Therefore, the antiderivative of $\sin(x)$ is $-\cos(x)$:
$$\int \sin(x) \, dx = -\cos(x)$$

### Step C: Apply the Fundamental Theorem of Calculus
Evaluate the antiderivative at the upper limit ($\pi$) and subtract the value at the lower limit ($0$):
$$A = \left[ -\cos(x) \right]_{0}^{\pi}$$
$$A = (-\cos(\pi)) - (-\cos(0))$$

### Step D: Evaluate Trigonometric Values
* $\cos(\pi) = -1$
* $\cos(0) = 1$

Substitute these values:
$$A = (-(-1)) - (-1)$$
$$A = 1 + 1$$
**$$A = 2$$**

---

## 4. Final Result
The area under the curve of $f(x) = \sin(x)$ from $0$ to $\pi$ is exactly:
### **$$2 \text{ units}^2$$**

---

## 5. Conclusion
* **Symmetry:** The sine function is symmetric; the area from $0$ to $\pi/2$ is exactly $1$, and from $\pi/2$ to $\pi$ is also $1$.
* **Net Area:** Over a full period ($0$ to $2\pi$), the net area would be $0$ because the area under the x-axis is considered negative.