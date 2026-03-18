# Mathematical Analysis: Optimization Problem
**Function:** $y = 3 - x^2$  
**Constraint:** Rectangle located in the **first quadrant**.

---

## 1. Objective
To find the dimensions ($x$ and $y$) of the rectangle inscribed under the curve $y = 3 - x^2$ that results in the **maximum possible area**.



---

## 2. Setting up the Problem

### Step A: Define the Area Function
For a rectangle in the first quadrant with one corner at $(0,0)$ and the opposite corner on the curve at $(x, y)$:
* **Width:** $x$
* **Height:** $y = 3 - x^2$
* **Area ($A$):** $A = \text{Width} \times \text{Height}$
**$$A(x) = x(3 - x^2) = 3x - x^3$$**

### Step B: Determine the Domain
Since the rectangle is in the first quadrant:
* $x$ must be greater than $0$.
* $y$ must be greater than $0$, which means $3 - x^2 > 0 \implies x < \sqrt{3}$.

---

## 3. Finding the Maximum (Calculus)

### Step A: Find the First Derivative
To find the critical points, we differentiate the area function with respect to $x$:
$$A'(x) = \frac{d}{dx}(3x - x^3)$$
**$$A'(x) = 3 - 3x^2$$**

### Step B: Solve for Critical Points
Set $A'(x) = 0$:
$$3 - 3x^2 = 0$$
$$3x^2 = 3$$
$$x^2 = 1$$
**$$x = 1$$** (We ignore $x = -1$ as it is not in the first quadrant).

### Step C: Verify with Second Derivative
$$A''(x) = -6x$$
At $x = 1$, $A''(1) = -6$. Since $A''(x) < 0$, the point is a **local maximum**.

---

## 4. Final Dimensions and Area
Plug $x = 1$ back into the original equations:
* **Width ($x$):** $1$
* **Height ($y$):** $3 - (1)^2 = 2$
* **Maximum Area:** $1 \times 2 = 2 \text{ units}^2$

---

## 5. Conclusion
* **Optimal Dimensions:** The rectangle should be **1 unit wide** and **2 units high**.
* **Geometric Insight:** The maximum area occurs when the height is exactly double the width in this specific parabolic constraint.