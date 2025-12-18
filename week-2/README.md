Here is the **Daily Plan for Week 2**.

**Theme:** **"The Art of Comparison"**
This week focuses on **Ratios, Averages, and Mixtures**.
**The 80/20 Insight:** The **Rule of Alligation** (Day 5) is the single most powerful technique in this week. It turns complex algebraic equations into a simple visual subtraction game.

---

### **Day 1: Ratio Basics & Balancing**
*Focus: Manipulating relationships between quantities.*

*   **Concept Focus:**
    1.  **Simplification:** Ratio is the simplest form of a fraction (e.g., $1.5 : 2.5$ becomes $3 : 5$).
    2.  **Balancing Ratios (The Bridge):** If $A:B = 2:3$ and $B:C = 4:5$, find $A:B:C$.
        *   *The "Neighbor" Trick:* Write them in a grid. Fill empty spaces with the neighbor number.
        *   Row 1: 2 : 3 : (3)
        *   Row 2: (4) : 4 : 5
        *   Multiply columns: $8 : 12 : 15$.
*   **Problem (Intermediate - PYQ):**
    *   "Rs. 7500 is divided among A, B, and C such that A's share to B's share is 5:2 and B's share to C's share is 7:13. How much did B receive?"
    *   *Steps:* Balance A:B and B:C to get A:B:C ($35:14:26$). Total parts = $35+14+26 = 75$. $1 \text{ part} = 100$. B gets $1400$.

### **Day 2: Partnership**
*Focus: Ratios applied to Money and Time (High frequency in TCS/Infosys).*

*   **Concept Focus:**
    *   $\text{Profit Ratio} = \text{Investment} \times \text{Time Period}$.
    *   If time is not mentioned, assume it is equal for everyone.
*   **Problem (Beginner):**
    *   "A starts a business with Rs. 2000. B joins him after 3 months with Rs. 4000. Find the profit ratio at the end of the year."
    *   *Calculation:* A's time = 12 months. B's time = $12 - 3 = 9$ months.
    *   Ratio: $(2000 \times 12) : (4000 \times 9) \to 24 : 36 \to 2:3$.
*   **Problem (Intermediate - PYQ):**
    *   "A, B, and C enter a partnership. A invests 3 times as much as B, and B invests 2/3 of what C invests. Find the ratio of their capitals."
    *   *Trick:* Work backwards or assume C = 3 (to eliminate fraction).

### **Day 3: Averages (The "Deviation" Method)**
*Focus: Stop adding everything up. Look at the difference.*

*   **Concept Focus:** Average is the "equalizer."
    *   **The Shortcut:** If a new person joins and the Average goes UP, the new person brought *more* than the average.
    *   $\text{New Value} = \text{Old Avg} + (\text{Change in Avg} \times \text{Total New People})$.
*   **Problem (Standard Formula vs. Logic):**
    *   "The average weight of 24 students is 35kg. If the teacher is added, the average rises by 400g. Find the teacher's weight."
    *   *School Method:* $(25 \times 35.4) - (24 \times 35)$. (Too slow).
    *   *Logic Method:* Teacher brings the base 35kg PLUS enough to give 0.4kg to all 25 people.
    *   Teacher = $35 + (0.4 \times 25) = 35 + 10 = 45\text{kg}$. (Done mentally).

### **Day 4: Weighted Averages**
*Focus: Combining groups.*

*   **Concept Focus:**
    *   Formula: $\text{Avg} = \frac{n_1 A_1 + n_2 A_2}{n_1 + n_2}$.
    *   This is used when mixing two classes with different average scores or mixing two rice varieties.
*   **Problem (Intermediate):**
    *   "A class has 20 boys and 30 girls. The average score of boys is 60 and girls is 70. Find the class average."
    *   *Trick:* Simplify the count ratio ($20:30 \to 2:3$). Use 2 and 3 instead of 20 and 30 to keep math small.
    *   $\frac{2(60) + 3(70)}{5} = \frac{120+210}{5} = 66$.

### **Day 5: The Rule of Alligation (The Super Shortcut)**
*Focus: The "X" Method. This is critical for Week 2.*

*   **Concept Focus:** Used when two ingredients are mixed to form a mixture.
    *   **Structure:**
        ```text
          Cheaper Price (C)      Dearer Price (D)
                       \        /
                        Mean (M)
                       /        \
          (D - M)                (M - C)
        ```
    *   **Result:** The ratio of Quantity is $(D-M) : (M-C)$.
*   **Critical Rule:** C, D, and M must be the SAME unit (usually Cost Price). You cannot mix CP, CP, and SP.
*   **Problem (PYQ Classic):**
    *   "In what ratio must rice at Rs. 20/kg be mixed with rice at Rs. 28/kg to create a mixture worth Rs. 25/kg?"
    *   *Calculation:*
        *   Left: 20, Right: 28, Center: 25.
        *   Cross subtract: $(28-25) : (25-20) \to 3 : 5$.
        *   Answer: 3:5. (Solved in 10 seconds).

### **Day 6: Advanced Mixture (Replacement Problems)**
*Focus: Dilution logic.*

*   **Concept Focus:** When you take out pure liquid and replace it with water repeatedly.
    *   **Formula:** $\text{Final Pure Liquid} = \text{Initial} \times (1 - \frac{\text{Amount Replaced}}{\text{Total Capacity}})^n$
    *   where $n$ is the number of times the process happens.
*   **Problem (Advanced):**
    *   "A container has 100L of milk. 10L is removed and replaced with water. This is done a total of 2 times. How much milk is left?"
    *   *Solution:* $100 \times (1 - \frac{10}{100})^2 = 100 \times (0.9)^2 = 100 \times 0.81 = 81\text{L}$.

### **Day 7: Weekly Challenge (Mix & Match)**
*Focus: Identifying WHICH method to use.*

*   **Activity:**
    1.  Solve 5 questions where you have to decide: *Is this a Ratio Balance problem or an Alligation problem?*
    2.  **Mock Drill:** Find 10 Partnership problems on IndiaBix. Set a timer for 10 minutes.
*   **Self-Correction Check:**
    *   In Partnership, did you account for the *months* correctly? (Common error: Ignoring time if investment amounts are complex).
    *   In Alligation, did you ensure the Mean Price is *between* the Cheap and Dear price? (If Mean is 30, and inputs are 20 and 25, you made a mistake).

---

### **Week 2 Checklist for Success:**
*   [ ] I can combine $A:B$ and $B:C$ into $A:B:C$ in under 20 seconds.
*   [ ] I understand that Profit depends on Investment $\times$ Time.
*   [ ] I can use the "Deviation method" (logic) for Average problems instead of big multiplication.
*   [ ] **Crucial:** I can draw the Alligation "X" diagram to solve mixture problems.
