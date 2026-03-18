# Logic & Series: The Fly and the Bicycle
**Initial Distance:** $10\text{ meters}$  
**Bicycle Speed ($v_b$):** $1\text{ m/s}$  
**Fly Speed ($v_f$):** $2\text{ m/s}$  

---

## 1. Objective
To calculate the total distance traveled by a fly that bounces back and forth between a moving bicycle and a wall until the bicycle reaches the wall.



---

## 2. Two Ways to Solve

### Method A: The Infinite Series (Complex)
One could calculate the distance of the first trip to the wall, then the return trip to the bike, then the next trip to the wall...
* This creates a **converging geometric series**.
* While mathematically sound, it involves complex summations of decreasing time intervals.

### Method B: The Logical Shortcut (Simple)
Instead of tracking the fly's path, we track the **total time** the fly is in the air.
> **Key Insight:** The fly stops moving only when the bicycle hits the wall.

---

## 3. Step-by-Step Calculation

### Step A: Find the Total Time ($t$)
The bicycle must travel $10\text{ meters}$ at a constant speed of $1\text{ m/s}$.
$$t = \frac{\text{Distance}}{\text{Speed}}$$
$$t = \frac{10\text{ m}}{1\text{ m/s}}$$
**$$t = 10\text{ seconds}$$**

### Step B: Calculate the Fly's Distance
The fly travels at a constant speed of $2\text{ m/s}$ for the entire duration of those $10\text{ seconds}$, regardless of how many times it turns around.
$$\text{Distance}_{fly} = \text{Speed}_{fly} \times t$$
$$\text{Distance}_{fly} = 2\text{ m/s} \times 10\text{ s}$$
**$$\text{Distance}_{fly} = 20\text{ meters}$$**

---

## 4. Conclusion
* **Total Distance Traveled:** $20\text{ meters}$.
* **Mathematical Takeaway:** Complex-looking series problems can often be simplified by identifying a constant variable—in this case, the **total time of flight**.

---

## 5. Fun Fact
Legend has it that when this problem was posed to the famous mathematician **John von Neumann**, he solved it in his head in seconds. When asked if he knew the "shortcut," he replied, "Shortcut? I just summed the infinite series!"