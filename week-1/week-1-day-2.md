# Week 1, Day 2: LCM, HCF & Factor Mastery - Deep Dive

## 🎯 Today's Mission
Master **LCM & HCF calculations** using the fastest methods, and learn **factor counting** - skills that appear in 25% of all aptitude tests.

---

## ⏰ 2-Hour Breakdown

### **Part 1: Quick Day 1 Revision + Theory (35 minutes)**
### **Part 2: LCM & HCF Methods (40 minutes)**
### **Part 3: Factor Counting & Applications (30 minutes)**
### **Part 4: Speed Drills & Review (15 minutes)**

---

## 🔄 PART 1A: DAY 1 QUICK REVISION (10 mins)

### **Lightning Round - Test Your Memory**

Answer these WITHOUT looking at notes:

1. What's the divisibility rule for 9?
2. Is 67 prime?
3. Is 5,832 divisible by 6?

<details>
<summary>✅ Answers</summary>

1. Sum of digits divisible by 9
2. Yes (from memorized list)
3. Check 2: Last digit 2 (even) ✓ | Check 3: 5+8+3+2=18 ✓ | **YES**

If you got all 3: Perfect! Move on.
If you got 1-2: Quick 5-min review of Day 1 card.
If you got 0: Spend 15 mins reviewing Day 1 before continuing.
</details>

---

### **Common Day 1 Mistakes - Let's Fix Them**

**Mistake #1**: Confusing divisibility by 4 and 8
```
❌ Wrong: "Is 7,824 divisible by 4? Check last digit = 4"
✅ Right: "Check last TWO digits = 24 → 24÷4=6 ✓"

For 8: Check last THREE digits
```

**Mistake #2**: Divisibility by 6
```
❌ Wrong: "Last digit is 6, so divisible by 6"
✅ Right: "Must satisfy BOTH 2 AND 3 rules"

Example: 16 - ends in 6, but 1+6=7 (not divisible by 3) → NO
```

**Mistake #3**: The 11 rule
```
Position marking:
4 5 6 2 8
1 2 3 4 5  ← Position numbers

Odd positions (1,3,5): 4 + 6 + 8 = 18
Even positions (2,4): 5 + 2 = 7
Difference: 18 - 7 = 11 → Divisible ✓
```

---

## 📚 PART 1B: THEORY & CONCEPT BUILDING (25 mins)

### **What are LCM and HCF?**

Imagine you have two buses:
- Bus A arrives every 12 minutes
- Bus B arrives every 18 minutes

**LCM (Lowest Common Multiple)** answers: When will both buses arrive together?
**HCF (Highest Common Factor)** answers: What's the biggest time interval that divides both schedules?

In placement tests, you'll see:
- "Three bells ring at intervals of 6, 8, and 12 minutes..."
- "What's the greatest number that divides 145, 218, and 327 leaving same remainder?"

---

### **Concept 1: HCF (Highest Common Factor) [10 mins]**

**Definition**: The largest number that divides all given numbers exactly.

#### **Method 1: Prime Factorization (Best for small numbers)**

**Example**: Find HCF of 24 and 36

**Step-by-step:**
```
24 = 2 × 2 × 2 × 3 = 2³ × 3¹
36 = 2 × 2 × 3 × 3 = 2² × 3²

HCF = Product of LOWEST powers of common primes
    = 2² × 3¹  (take minimum power of each)
    = 4 × 3
    = 12
```

**Visual representation:**
```
24: 2³ × 3¹
36: 2² × 3²
    ↓    ↓
HCF: 2² × 3¹ (minimum powers)
```

---

#### **Method 2: Euclidean Algorithm (FASTEST for large numbers)**

**This is the method you'll use 90% of the time in exams.**

**The Rule**: HCF(a, b) = HCF(b, remainder when a÷b)

**Example**: Find HCF of 1095 and 1168

**Traditional method would take 2+ minutes. Watch this:**

```
Step 1: 1168 = 1095 × 1 + 73
        HCF(1168, 1095) = HCF(1095, 73)

Step 2: 1095 = 73 × 15 + 0
        HCF(1095, 73) = HCF(73, 0) = 73

Answer: HCF = 73
```

**Time taken: 20-30 seconds!**

---

**Practice this method right now:**

**Problem**: Find HCF(252, 105)

<details>
<summary>💭 Try it yourself first - show your steps</summary>

```
Step 1: 252 = 105 × 2 + 42
        HCF(252, 105) = HCF(105, 42)

Step 2: 105 = 42 × 2 + 21
        HCF(105, 42) = HCF(42, 21)

Step 3: 42 = 21 × 2 + 0
        HCF(42, 21) = HCF(21, 0) = 21

Answer: HCF = 21
```

**Verification using prime factorization:**
```
252 = 2² × 3² × 7
105 = 3 × 5 × 7
HCF = 3 × 7 = 21 ✓
```

⏱️ Euclidean: 25 seconds | Prime factorization: 60+ seconds
</details>

---

#### **Method 3: Division Method (Visual learners)**

Same as Euclidean, but written differently:

```
     73
    ----
1095)1168(1
     1095
    -----
  73)1095(15
      1095
     -----
         0

HCF = 73 (last divisor)
```

**Choose whichever visualization works for you!** The math is identical to Euclidean.

---

### **Concept 2: LCM (Lowest Common Multiple) [10 mins]**

**Definition**: The smallest number that is a multiple of all given numbers.

#### **Method 1: Prime Factorization**

**Example**: Find LCM of 24 and 36

```
24 = 2³ × 3¹
36 = 2² × 3²

LCM = Product of HIGHEST powers of all primes
    = 2³ × 3²  (take maximum power of each)
    = 8 × 9
    = 72
```

**Visual:**
```
24: 2³ × 3¹
36: 2² × 3²
    ↓    ↓
LCM: 2³ × 3² (maximum powers)
```

---

#### **Method 2: Division Method (Faster for multiple numbers)**

**Example**: Find LCM of 12, 18, 24

```
2 | 12, 18, 24
  |------------
2 |  6,  9, 12
  |------------
2 |  3,  9,  6
  |------------
3 |  3,  9,  3
  |------------
3 |  1,  3,  1
  |------------
  |  1,  1,  1

LCM = 2 × 2 × 2 × 3 × 3 = 72
```

**How it works:**
1. Divide by smallest prime that divides at least one number
2. Bring down numbers that don't divide
3. Continue until all are 1
4. Multiply all divisors

⏱️ **This becomes VERY fast with practice - target 30 seconds**

---

#### **Method 3: Using HCF (When you have 2 numbers)**

**GOLDEN FORMULA:**
```
LCM(a, b) × HCF(a, b) = a × b

Therefore:
LCM(a, b) = (a × b) / HCF(a, b)
```

**Example**: Find LCM of 252 and 105

We already found HCF = 21 (from earlier example)

```
LCM = (252 × 105) / 21
    = 26,460 / 21
    = 1,260
```

**This is INSTANT if you already know HCF!**

---

**Practice Problem**: Find both HCF and LCM of 48 and 180

<details>
<summary>💭 Try both methods - prime factorization AND formula</summary>

**Method 1: Prime Factorization**
```
48  = 2⁴ × 3¹
180 = 2² × 3² × 5¹

HCF = 2² × 3¹ = 4 × 3 = 12 (minimum powers)
LCM = 2⁴ × 3² × 5¹ = 16 × 9 × 5 = 720 (maximum powers)
```

**Method 2: Using formula**
```
First find HCF using Euclidean:
180 = 48 × 3 + 36
48 = 36 × 1 + 12
36 = 12 × 3 + 0

HCF = 12

Then LCM = (48 × 180) / 12 = 8,640 / 12 = 720
```

**Answer: HCF = 12, LCM = 720**

**Verification:** 12 × 720 = 8,640 = 48 × 180 ✓
</details>

---

### **Concept 3: Factor Counting [5 mins]**

**Definition**: How many divisors does a number have?

**MAGIC FORMULA**: If N = p₁^a × p₂^b × p₃^c

**Number of factors = (a+1) × (b+1) × (c+1)**

**Example**: How many factors does 360 have?

```
Step 1: Prime factorize
360 = 2³ × 3² × 5¹

Step 2: Apply formula
Factors = (3+1) × (2+1) × (1+1)
        = 4 × 3 × 2
        = 24 factors
```

**Without the formula?** You'd have to list: 1, 2, 3, 4, 5, 6, 8, 9, 10, 12, 15, 18, 20, 24, 30, 36, 40, 45, 60, 72, 90, 120, 180, 360... exhausting!

⏱️ **With formula: 15 seconds | Without: 3+ minutes**

---

## 🎯 PART 2: GUIDED PRACTICE - LCM & HCF (40 mins)

### **Set A: HCF Using Euclidean Algorithm (12 mins)**
*Target: 45 seconds per problem*

---

#### **Problem 1**: Find HCF of 144 and 198

<details>
<summary>💭 Set up the division yourself first</summary>

**Solution:**
```
198 = 144 × 1 + 54
144 = 54 × 2 + 36
54 = 36 × 1 + 18
36 = 18 × 2 + 0

HCF = 18
```

**Quick check**: Does 18 divide both?
- 144 ÷ 18 = 8 ✓
- 198 ÷ 18 = 11 ✓

⏱️ Expected time: 30-40 seconds
</details>

---

#### **Problem 2**: Find HCF of 867 and 255

<details>
<summary>💭 Large numbers - perfect for Euclidean!</summary>

**Solution:**
```
867 = 255 × 3 + 102
255 = 102 × 2 + 51
102 = 51 × 2 + 0

HCF = 51
```

**Pro tip**: When remainder is exactly half, it divides evenly next step!

⏱️ Expected time: 35-45 seconds
</details>

---

#### **Problem 3**: Find the greatest number that divides 285, 333, and 429 leaving remainders 9, 13, and 21 respectively.

<details>
<summary>💭 Trick question! What do the remainders tell you?</summary>

**Solution:**

**Key insight**: If remainders are different, subtract them first!

```
285 - 9 = 276
333 - 13 = 320
429 - 21 = 408
```

Now find HCF(276, 320, 408)

**First HCF(276, 320):**
```
320 = 276 × 1 + 44
276 = 44 × 6 + 12
44 = 12 × 3 + 8
12 = 8 × 1 + 4
8 = 4 × 2 + 0

HCF(276, 320) = 4
```

**Now HCF(4, 408):**
```
408 = 4 × 102 + 0
HCF = 4
```

**Answer: 4**

**Verification:**
- 285 ÷ 4 = 71 remainder 1... wait, that's not 9!

**WAIT - Recheck the problem!** 

Actually, the number that leaves these remainders IS the HCF of the differences:
- (285-9), (333-13), (429-21) = 276, 320, 408

HCF = 4... but let me verify:
- 276 ÷ 4 = 69 ✓
- 320 ÷ 4 = 80 ✓  
- 408 ÷ 4 = 102 ✓

So the number is 4, and:
- 285 = 4×71 + 1... Hmm, remainder is 1, not 9

**I need to reconsider this problem type...**

**CORRECT APPROACH:**
The number we seek divides (285-9), (333-13), (429-21) exactly.

HCF(276, 320, 408) = 4 won't work because 285 = 4×71 + 1

Let me find HCF properly:
Actually, we need HCF of the DIFFERENCES of remainders might vary.

**Better approach**: Find HCF of differences between the numbers:
- 333 - 285 = 48
- 429 - 333 = 96
- 429 - 285 = 144

HCF(48, 96, 144):
```
96 = 48 × 2 + 0, so HCF(48,96) = 48
144 = 48 × 3 + 0, so HCF(48,144) = 48

HCF = 48
```

**Check:**
- 285 ÷ 48 = 5 remainder 45 (not 9) ✗

**ACTUAL CORRECT SOLUTION:**

When different remainders, find HCF of (Number - Remainder):
- 285 - 9 = 276 = 4 × 69
- 333 - 13 = 320 = 4 × 80
- 429 - 21 = 408 = 4 × 102

But we need factors common to all three.

Actually, the question might have an error, OR:

**Standard theorem**: Greatest number = HCF of pairwise differences
- |333 - 285| = 48
- |429 - 333| = 96  
- |429 - 285| = 144

HCF(48, 96, 144) = 48

**But check remainders:**
- 285 = 48×5 + 45 (not 9)
- 333 = 48×6 + 45 (not 13)
- 429 = 48×8 + 45 (not 21)

Hmm, all leave remainder 45, not the stated remainders.

**The problem as stated may have inconsistent data.** 

**LEARNING POINT**: For "leaves remainder r when dividing N":
- The divisor must divide (N - r) exactly
- For multiple numbers with same remainder: HCF of (N₁-r, N₂-r, N₃-r)
- For different remainders: Problem needs careful verification

I'll provide a corrected version:

**CORRECTED PROBLEM**: Find greatest number that divides 285, 333, 429 leaving SAME remainder.

**Solution**: HCF of differences = 48, and all leave remainder 45.

⏱️ This type: 90-120 seconds (complex reasoning required)
</details>

I notice this problem type requires more care. Let me provide a clearer version:

---

#### **Problem 3 (REVISED)**: Find the greatest number that divides 245, 365, and 485 leaving the same remainder in each case.

<details>
<summary>💭 When remainder is SAME, work with differences</summary>

**Solution:**

When remainder is same, the number divides the DIFFERENCES evenly.

```
365 - 245 = 120
485 - 365 = 120
485 - 245 = 240
```

Find HCF(120, 120, 240) = 120

**Answer: 120**

**Verification:**
- 245 ÷ 120 = 2 remainder 5
- 365 ÷ 120 = 3 remainder 5  
- 485 ÷ 120 = 4 remainder 5

All leave remainder 5 ✓

⏱️ Expected time: 60 seconds
</details>

---

### **Set B: LCM Problems (12 mins)**

---

#### **Problem 4**: Find LCM of 12, 15, and 20

<details>
<summary>💭 Use division method for 3+ numbers</summary>

**Solution:**

**Method 1: Division**
```
2 | 12, 15, 20
  |------------
2 |  6, 15, 10
  |------------
3 |  3, 15,  5
  |------------
5 |  1,  5,  5
  |------------
  |  1,  1,  1

LCM = 2 × 2 × 3 × 5 = 60
```

**Method 2: Prime Factorization**
```
12 = 2² × 3
15 = 3 × 5
20 = 2² × 5

LCM = 2² × 3 × 5 = 60
```

**Answer: 60**

⏱️ Division method: 30 seconds | Prime: 40 seconds
</details>

---

#### **Problem 5**: Three bells toll at intervals of 9, 12, and 15 minutes. If they toll together at 8:00 AM, when will they next toll together?

<details>
<summary>💭 This is asking for LCM!</summary>

**Solution:**

They toll together after LCM(9, 12, 15) minutes.

```
3 | 9, 12, 15
  |-----------
3 | 3,  4,  5
  |-----------
  | 1,  4,  5

LCM = 3 × 3 × 4 × 5 = 180 minutes
```

180 minutes = 3 hours

**Answer: 11:00 AM** (8:00 AM + 3 hours)

**Common mistake**: Finding 180 but forgetting to convert to hours!

⏱️ Expected time: 45 seconds
</details>

---

#### **Problem 6**: The LCM of two numbers is 864 and their HCF is 144. If one number is 288, find the other.

<details>
<summary>💭 Use the golden formula!</summary>

**Solution:**

**Formula**: LCM × HCF = Product of two numbers

```
864 × 144 = 288 × Other number

Other number = (864 × 144) / 288
             = 124,416 / 288
             = 432
```

**Answer: 432**

**Verification:**
- HCF(288, 432) should be 144
  ```
  432 = 288 × 1 + 144
  288 = 144 × 2 + 0
  HCF = 144 ✓
  ```

- LCM × HCF = 864 × 144 = 124,416
- 288 × 432 = 124,416 ✓

⏱️ Expected time: 40 seconds
</details>

---

### **Set C: Factor Counting (10 mins)**

---

#### **Problem 7**: How many factors does 720 have?

<details>
<summary>💭 Prime factorize first, then apply formula</summary>

**Solution:**

**Step 1: Prime factorization**
```
720 = 16 × 45
    = 2⁴ × 9 × 5
    = 2⁴ × 3² × 5¹
```

**Step 2: Apply formula**
```
Number of factors = (4+1) × (2+1) × (1+1)
                  = 5 × 3 × 2
                  = 30 factors
```

**Answer: 30**

**Challenge**: Can you list a few to verify? 
1, 2, 3, 4, 5, 6, 8, 9, 10, 12, 15, 16, 18, 20, 24, 30, 36, 40, 45, 48, 60, 72, 80, 90, 120, 144, 180, 240, 360, 720

⏱️ Expected time: 35 seconds
</details>

---

#### **Problem 8**: How many factors of 1800 are perfect squares?

<details>
<summary>💭 Perfect squares have all EVEN powers</summary>

**Solution:**

**Step 1: Prime factorization**
```
1800 = 18 × 100
     = 2 × 9 × 4 × 25
     = 2³ × 3² × 5²
```

**Step 2: For perfect square factors, all powers must be EVEN**

We can choose:
- 2^0, 2^2 → 2 choices (0 and 2, we can't use 3)
- 3^0, 3^2 → 2 choices
- 5^0, 5^2 → 2 choices

**Number of perfect square factors = 2 × 2 × 2 = 8**

**Answer: 8**

**What are they?**
1, 4, 9, 36, 25, 100, 225, 900

Let's verify: 1800 = 2³×3²×5²
- 1 = 2⁰×3⁰×5⁰ ✓
- 4 = 2²×3⁰×5⁰ ✓
- 9 = 2⁰×3²×5⁰ ✓
- 25 = 2⁰×3⁰×5² ✓
- 36 = 2²×3²×5⁰ ✓
- 100 = 2²×3⁰×5² ✓
- 225 = 2⁰×3²×5² ✓
- 900 = 2²×3²×5² ✓

⏱️ Expected time: 60 seconds
</details>

---

#### **Problem 9**: N = 2⁴ × 3³ × 5². How many factors of N are divisible by 6?

<details>
<summary>💭 Factors divisible by 6 must contain 2¹×3¹</summary>

**Solution:**

**Step 1**: Understand the constraint
- For divisibility by 6 = 2×3, factor must have at least 2¹ and 3¹

**Step 2**: Count valid combinations
From N = 2⁴ × 3³ × 5²

For factors divisible by 6:
- 2's power: must be ≥1, so 2¹, 2², 2³, 2⁴ → **4 choices**
- 3's power: must be ≥1, so 3¹, 3², 3³ → **3 choices**
- 5's power: can be anything, so 5⁰, 5¹, 5² → **3 choices**

**Number of such factors = 4 × 3 × 3 = 36**

**Answer: 36**

**Alternative thinking:**
- Total factors of N = (4+1)(3+1)(2+1) = 60
- Factors NOT divisible by 2 or 3 = factors using only 5 = (2+1) = 3
- Factors divisible by 2 but not 3 = 4×1×3 = 12
- Factors divisible by 3 but not 2 = 1×3×3 = 9
- Remaining = 60 - 3 - 12 - 9 = 36 ✓

⏱️ Expected time: 75 seconds (this is advanced!)
</details>

---

### **Set D: Mixed Application (6 mins)**

---

#### **Problem 10**: Two numbers are in the ratio 3:4. Their LCM is 180. Find the numbers.

<details>
<summary>💭 Use ratio with LCM properties</summary>

**Solution:**

Let the numbers be 3x and 4x (to maintain ratio 3:4)

**Step 1**: Find LCM(3x, 4x)
```
3x = 3 × x
4x = 4 × x = 2² × x

LCM = 12x (when x has no common factors with 12)
```

Actually, let's be more careful:

**Step 2**: We know LCM = 180

If numbers are in ratio 3:4 with no common factors (simplest form):
```
Numbers are 3k and 4k for some k

HCF(3k, 4k) = k (since HCF(3,4) = 1)
LCM(3k, 4k) = 12k (since LCM(3,4) = 12)

Given: 12k = 180
k = 15
```

**Numbers are: 3×15 = 45 and 4×15 = 60**

**Answer: 45 and 60**

**Verification:**
- Ratio: 45:60 = 3:4 ✓
- LCM(45, 60):
  ```
  45 = 3² × 5
  60 = 2² × 3 × 5
  LCM = 2² × 3² × 5 = 180 ✓
  ```

⏱️ Expected time: 60 seconds
</details>

---

## ⚡ PART 3: SPEED DRILLS (15 mins)

### **Drill 1: Quick HCF (5 mins)**
*Use Euclidean algorithm. Time yourself: 30 seconds each*

| Numbers | Your HCF | Time |
|---------|----------|------|
| 84, 126 |          |      |
| 156, 234 |         |      |
| 414, 621 |         |      |

<details>
<summary>✅ Solutions</summary>

**84, 126:**
```
126 = 84 × 1 + 42
84 = 42 × 2 + 0
HCF = 42
```

**156, 234:**
```
234 = 156 × 1 + 78
156 = 78 × 2 + 0
HCF = 78
```

**414, 621:**
```
621 = 414 × 1 + 207
414 = 207 × 2 + 0
HCF = 207
```

**Pattern noticed?** When one number is exactly 1.5× the other, HCF is half the smaller number!
</details>

---

### **Drill 2: Quick LCM (5 mins)**
*Division method. Target: 40 seconds each*

Find LCM of:
1. 8, 12, 18
2. 15, 25, 30
3. 14, 21, 28

<details>
<summary>✅ Solutions</summary>

**1) LCM(8, 12, 18)**
```
2 | 8, 12, 18
  |-----------
2 | 4,  6,  9
  |-----------
2 | 2,  3,  9
  |-----------
3 | 1,  3,  9
  |-----------
3 | 1,  1,  3
  |-----------
  | 1,  1,  1

LCM = 2³ × 3² = 72
```

**2) LCM(15, 25, 30)**
```
5 | 15, 25, 30
  |------------
5 |  3,  5,  6
  |------------
3 |  3,  1,  6
  |------------
2 |  1,  1,  2
  |------------
  |  1,  1,  1

LCM = 5² × 3 × 2 = 150
```

**3) LCM(14, 21, 28)**
```
7 | 14, 21, 28
  |------------
2 |  2,  3,  4
  |------------
2 |  1,  3,  2
  |------------
3 |  1,  3,  1
  |------------
  |  1,  1,  1

LCM = 7 × 2² × 3 = 84
```
</details>

---

### **Drill 3: Factor Counting Rapid Fire (5 mins)**
*Prime factorize mentally, then count. 30 seconds each*

How many factors does each number have?
1. 100
2. 144
3. 300

<details>
<summary>✅ Solutions</summary>

**1) 100 = 2² × 5²**
```
Factors = (2+1)(2+1) = 9
(They are: 1,2,4,5,10,20,25,50,100)
```

**2) 144 = 2⁴ × 3²**
```
Factors = (4+1)(2+1) = 15
```

**3) 300 = 2² × 3 × 5²**
```
Factors = (2+1)(1+1)(2+1) = 18
```
</details>

---

## 📝 PART 4: REVIEW & TOMORROW PREP (15 mins)

### **Update Your Formula Card**

Add to your Day 1 card:

```
DAY 2 - LCM & HCF
═══════════════════════════

HCF METHODS:
1. Prime Factorization → Lowest powers
2. Euclidean: HCF(a,b) = HCF(b, a mod b)
3. For 3+ numbers: Find pairwise

LCM METHODS:
1. Prime Factorization → Highest powers
2. Division method (for 3+ numbers)
3. Formula: LCM(a,b) = (a×b)/HCF(a,b)

GOLDEN FORMULA:
LCM × HCF = Product of two numbers

FACTOR COUNTING:
If N = p₁^a × p₂^b × p₃^c
Factors = (a+1)(b+1)(c+1)

Perfect square factors: Use only even powers
Factors divisible by k: Account for k's prime factors

KEY INSIGHTS:
• Euclidean is FASTEST for large numbers
• Division method best for 3+ numbers  
• Always verify using LCM×HCF = a×b
```

---

### **Self-Assessment Quiz (5 mins)**

Without notes:

1. What's HCF(54, 81)?
2. What's LCM(12, 18, 24)?
3. How many factors does 2³ × 5² have?

<details>
<summary>Answers</summary>

1. **HCF = 27**
   ```
   81 = 54 × 1 + 27
   54 = 27 × 2 + 0
   ```

2. **LCM = 72**
   ```
   12 = 2² × 3
   18 = 2 × 3²
   24 = 2³ × 3
   LCM = 2³ × 3² = 72
   ```

3. **12 factors**
   ```
   (3+1)(2+1) = 12
   ```

</details>

**Score:**
- 3/3: Excellent! Ready for Day 3 ✓
- 2/3: Good, quick 10-min review
- 0-1: Review Part 1 for 20 mins

---

### **Common Mistakes to Avoid**

**Mistake #1**: Confusing LCM and HCF formulas
```
❌ Wrong: "LCM uses minimum powers"
✅ Right: "LCM uses MAXIMUM powers, HCF uses MINIMUM powers"

Memory trick: LCM is LARGE → MAXimum
```

**Mistake #2**: Factor formula
```
❌ Wrong: "Number of factors = a × b × c"
✅ Right: "Number of factors = (a+1) × (b+1) × (c+1)"

Don't forget the +1!
```

**Mistake #3**: Euclidean algorithm
```
❌ Wrong: "HCF(252, 105) = 105 goes into 252 twice, remainder 42, so HCF = 42"
✅ Right: "Keep going! HCF(105, 42), then HCF(42, 21), then HCF(21, 0) = 21"

Continue until remainder is 0!
```

---

### **Today's Progress**

**You can now:**
- ✓ Find HCF of ANY two numbers in under 45 seconds
- ✓ Find LCM of 3+ numbers using division method
- ✓ Count factors without listing them
- ✓ Solve word problems involving bells, buses, cycles
- ✓ Work backwards from LCM/HCF to find numbers

**These skills apply to:**
- Time and work problems (Week 5)
- Ratio problems (Week 3)
- Simplification questions (every week!)
- Data sufficiency (Week 7)

---

### **Preview: Tomorrow (Day 3)**

You'll learn:
- **Remainders** (Wilson's theorem, negative remainders)
- **Cyclicity** (unit digits, last two digits)
- **Modular arithmetic** shortcuts

**Prep task** (Optional, 10 mins tonight):
- Practice: 7⁰=1, 7¹=7, 7²=49, 7³=343, 7⁴=2401
- Notice unit digit pattern: 7, 9, 3, 1, 7, 9, 3, 1...
- This is "cyclicity" - you'll master it tomorrow!

---

## 🎯 DAY 2 SUCCESS CHECKLIST

- [ ] Can find HCF using Euclidean in under 45 seconds
- [ ] Can find LCM of 3 numbers using division method
- [ ] Understand and can apply: LCM × HCF = a × b
- [ ] Can count factors using (a+1)(b+1)(c+1) formula
- [ ] Solved all guided problems
- [ ] Completed speed drills
- [ ] Updated formula card
- [ ] Self-assessment score: 2+/3

**Progress tracking:**
- Day 1: Divisibility ✓
- Day 2: LCM & HCF ✓
- Combined: You can now handle 40% of number system questions!

---

## 💪 MOTIVATION

**What you achieved today:**

You learned methods that most students don't discover until they've wasted hours doing long division. The Euclidean algorithm alone will save you **50+ hours** across your preparation.

**Real impact:**
- Previous you: "Find HCF of 1095 and 1168" = 3+ minutes ❌
- Today's you: Same problem = 25 seconds ✓

That's a **700% speed increase** in one day!

**Remember:** Every company tests LCM/HCF. You're now faster than 80% of candidates.

---

## 🆘 TROUBLESHOOTING

**"Euclidean algorithm confuses me"**
→ Write out 5 examples by hand. The pattern will click. Also watch it as continuous division - same thing!

**"I keep making calculation errors"**
→ Normal! Speed comes after accuracy. Slow down 20%, errors will reduce by 50%.

**"Factor counting - why the +1?"**
→ Because we include the power 0! Example: 2³ can be used as 2⁰, 2¹, 2², 2³ = 4 choices = 3+1.

**"Division method for LCM is messy"**
→ Use graph paper or lined paper. Keep columns straight. It becomes neat with practice.

---

## 🌟 PRO TIPS FROM DAY 2

1. **Always verify LCM**: Check that your answer is divisible by all original numbers
2. **HCF is fast-check**: If your HCF doesn't divide both numbers evenly, you made an error
3. **Prime factorization first**: For factor counting, always factorize completely before applying formula
4. **Pattern recognition**: 3 numbers, division method; 2 numbers, maybe use formula

---

**Tomorrow we go deeper into the beauty of numbers with remainders and cyclicity - the "magic tricks" of aptitude!** 🎩✨

**End of Day 2** | Time invested: 2 hours | Cumulative: 4 hours | You're 25% through Week 1! 📈
