Day 1 sets the foundation for everything that follows, so we’ll focus on:

- Number types (natural, whole, integers, primes, etc.)  
- Divisibility rules (2, 3, 5, 9, 10)  
- Light intro to multiples & counting (so LCM/HCF feels natural tomorrow)

Assume **2 hours total**. If you have more/less time, I’ll show how to scale at the end.

---

## Overview of Day 1

**Objectives by end of Day 1:**

1. You can classify a number correctly (natural, whole, integer, rational, prime, composite).  
2. You know and can instantly apply divisibility rules for **2, 3, 5, 9, 10**.  
3. You can quickly count how many numbers in a range are divisible by a given number (e.g., “How many numbers from 1–100 are divisible by 3?”).  
4. You’ve done at least one short **speed drill** with these rules.

---

## Block 1 – Concepts: Number Types & Basic Language (25–30 min)

### 1.1 Number Types (15–20 min)

Open a notebook and make a one‑page summary table.

Write definitions and 2–3 examples for each:

1. **Natural Numbers (N)**  
   - Counting numbers: 1, 2, 3, 4, …  
   - Note: Some definitions include 0, but for aptitude, usually N = {1,2,3,…}.

2. **Whole Numbers (W)**  
   - Natural numbers + 0: 0,1,2,3,…

3. **Integers (Z)**  
   - … –3, –2, –1, 0, 1, 2, 3, …  
   - Include negative whole numbers + zero + positive whole numbers.

4. **Rational Numbers (Q)**  
   - Can be written as p/q, where p and q are integers, q ≠ 0.  
   - Examples: 1/2, –3/4, 5 ( = 5/1 ), 0.25 ( = 1/4 ).  
   - Any terminating or repeating decimal is rational.

5. **Irrational Numbers**  
   - Cannot be written as exact p/q form (with integers p, q).  
   - Non‑terminating, non‑repeating decimals.  
   - Examples: √2, √3, π, e.

6. **Even & Odd Numbers**  
   - Even: divisible by 2 (last digit 0,2,4,6,8).  
   - Odd: not divisible by 2 (last digit 1,3,5,7,9).

7. **Prime & Composite Numbers**  
   - Prime: >1, has only two positive divisors: 1 and itself.  
   - Composite: >1, has more than two divisors.  
   - 1 is **neither prime nor composite** (important to remember).  
   - 2 is the **only even prime**.

**Must‑memorize list today:**  
Primes up to at least **30** (up to 50 is ideal, but up to 30 is enough for Day 1):

2, 3, 5, 7, 11, 13, 17, 19, 23, 29  
(If you can, extend to 31, 37, 41, 43, 47)

Write them down 2–3 times from memory until you don’t hesitate.

### 1.2 Quick Check (5–10 min)

Without overthinking, classify each in your notebook:

- –5, 0, 1, 2, 7, 15, 1/2, 0.333…, √2  

For each number, mark Y/N under these:  
Natural, Whole, Integer, Rational, Irrational, Even, Odd, Prime, Composite.

Then check:

- Did you remember that 1 is not prime or composite?  
- Did you remember that 0 is even but not positive/negative?

---

## Block 2 – Divisibility Rules (Part 1: 2, 3, 5, 9, 10) (30–35 min)

These rules save you huge time in number system, LCM/HCF, and some DI questions.

### 2.1 Learn / Revise the Rules (10–15 min)

Write each rule, plus 2–3 mental examples.

1. **Divisible by 2**  
   - Last digit is 0,2,4,6,8.  
   - Example: 246 (6 is even) → divisible by 2.

2. **Divisible by 5**  
   - Last digit is 0 or 5.

3. **Divisible by 10**  
   - Last digit is 0.

4. **Divisible by 3**  
   - Sum of digits is divisible by 3.  
   - Example: 735 → 7+3+5 = 15 → 15 divisible by 3 → 735 divisible by 3.

5. **Divisible by 9**  
   - Sum of digits is divisible by 9.  
   - Example: 729 → 7+2+9 = 18 → 18 divisible by 9 → 729 divisible by 9.

Create a small **divisibility cheat‑box** in your notebook:

- 2 → last digit even  
- 3 → sum of digits multiple of 3  
- 5 → last digit 0 or 5  
- 9 → sum of digits multiple of 9  
- 10 → last digit 0

### 2.2 Guided Practice – Very Basic (10–15 min)

Take any resource (IndiaBix / PrepInsta / R.S. Aggarwal) or make your own numbers.

**Task 1 – Rule Application**

For each number, mark which these it’s divisible by: 2, 3, 5, 9, 10.

Example set (you can copy these or use book questions):

1. 120  
2. 257  
3. 735  
4. 406  
5. 999  
6. 540  
7. 301  
8. 250  
9. 864  
10. 1001  

Write like:

- 120 → 2, 3, 5, 10 (sum = 3 → 3; last digit 0 → 2,5,10)  
- 257 → none (sum=14 → not 3/9, last digit 7)  

Aim to decide in under **5 seconds per number** once you warm up.

**Task 2 – Create & Answer Your Own 5**

- Write 5 random 3‑digit numbers.  
- For each, quickly call out (or write) all divisibility rules from 2,3,5,9,10 that they satisfy.

---

## Block 3 – Counting Multiples (Intro to LCM/HCF Thinking) (20–25 min)

We’ll gently introduce a very important idea that you’ll use repeatedly:

> “How many numbers between A and B are divisible by k?”

This ties in with divisibility and builds a base for LCM/HCF and simple DI.

### 3.1 Concept (5–10 min)

To find how many numbers from 1 to N are divisible by k:

- Count = ⌊N/k⌋ (integer part of N/k)

Example:

- Numbers from 1 to 100 divisible by 3:  
  - Largest multiple ≤ 100 is 99 = 3 × 33  
  - So there are 33 multiples → floor(100/3) = 33.

Similarly:

- From 1 to 50 divisible by 5 → floor(50/5) = 10.  

For a range [A, B], divisible by k:

- Count = floor(B/k) – floor((A–1)/k)

Example:

- Between 10 and 50 divisible by 4:  
  - floor(50/4) = 12  
  - floor(9/4) = 2  
  - Count = 12 – 2 = 10.

### 3.2 Practice (10–15 min)

Do these in notebook:

1. How many numbers from 1 to 100 are divisible by:  
   a) 2  
   b) 3  
   c) 5  
   d) 9  

2. How many numbers from 1 to 200 are divisible by:  
   a) 4  
   b) 8  
   c) 10  

3. How many numbers from 20 to 80 are divisible by:  
   a) 3  
   b) 5  

Write answer with method (use floor division).

If you struggle with floor division, do it by listing first few and last few multiples to see the pattern (3,6,9, …, 99).

---

## Block 4 – Structured Practice Set (Core Problems) (25–30 min)

Here’s a self‑contained practice set for Day 1. Try solving without looking back at notes at first.

### 4.1 Basic Classification & Divisibility (10–15 min)

1. Classify each as: Natural / Whole / Integer / Rational / Irrational / Prime / Composite / Even / Odd  
   a) –4  
   b) 0  
   c) 1  
   d) 2  
   e) 9  
   f) 11  
   g) 1/3  
   h) √3  

2. Using divisibility rules, state which numbers each is divisible by: 2, 3, 5, 9, 10  

   a) 246  
   b) 735  
   c) 500  
   d) 201  
   e) 999  
   f) 1000  

3. Mark True/False:  
   a) Every integer is a rational number.  
   b) Every rational number is an integer.  
   c) 0 is an even number.  
   d) 1 is a prime number.  
   e) All prime numbers are odd.

### 4.2 Counting Multiples (10–15 min)

4. How many numbers between 1 and 100 are divisible by 4?  
5. How many numbers between 1 and 100 are divisible by 9?  
6. How many numbers between 1 and 50 are divisible by both 2 and 5?  
   (Hint: numbers divisible by both 2 & 5 are divisible by LCM(2,5) = 10; so count multiples of 10.)  
7. How many numbers between 10 and 60 are divisible by 3?

Check your answers using the floor method. If any are wrong, find where you slipped (division or concept).

---

## Block 5 – Speed Drill (Short, Timed) (10–15 min)

This is to start building quick reflexes, not deep thought.

Set a timer for **10 minutes**.

### Drill 1 – Divisibility Reflex (8–10 min)

Take 15 random 3‑digit numbers (from a book or quickly write 15 yourself). For each, in your notebook, write something like:

- 382: 2, not 3, not 5, not 9, not 10  
- 735: 3,5,9  
- 450: 2,3,5,9?,10? etc.

Aim:  
- Average ≤ 30 seconds per number  
- Don’t manually divide; only use rules (last digit, sum of digits…)

### Drill 2 – Mini Reflection (2–5 min)

Immediately after the timer:

- Mark which rules still made you pause (maybe 9 or distinguishing 3 vs 9).  
- Underline 3 examples where you made a mistake and write the **correct reasoning**.

---

## Optional Extension (if you have extra 20–30 min)

If you finish early or want more:

1. Memorize/recall primes up to 50 again without looking.  
2. Do 5 more “how many multiples in a range” questions from any quant book or site.  
3. Try a couple of basic questions like:  
   - “Which is larger: 3/5 or 5/9?” (Cross‑multiply: 3×9 = 27, 5×5 = 25 → 3/5 larger.)  
   This starts connecting with % and ratio intuitions.

---

## How to Scale If Your Time is Different

- **If you have only ~1–1.25 hours**  
  - Block 1: 20 min (concepts)  
  - Block 2: 20 min (rules + a few examples)  
  - Block 3: 10 min (just 2–3 counting problems)  
  - Block 5: 10–15 min (speed drill)  
  - Skip some of the longer practice; keep at least a few of each type.

- **If you have 3+ hours**  
  - Double the practice problems in Blocks 2, 3, 4 using any question bank.  
  - Add 1–2 more speed drills with stricter time (e.g., 20 questions in 12 minutes).

---

## End-of-Day 1 Checklist

By the end of today, confidently answer “yes” to:

1. I can list primes up to 30 without looking.  
2. I can tell if a number is divisible by 2,3,5,9,10 in under 5 seconds.  
3. I understand how to find how many numbers from 1 to N are divisible by k.  
4. I know that:
   - 0 is whole, integer, rational, even (not positive or negative).  
   - 1 is not prime or composite.  
   - Every integer is a rational number.

If any of these are shaky, note them in your notebook as **“Revise at start of Day 2”** and quickly review them tomorrow before moving to divisibility (4, 6, 8, 11) and LCM/HCF.

If you tell me roughly how many hours you can give daily (consistently), I can tune Day 2 in similar detail to match your pace.
