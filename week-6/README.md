Here’s your **Week 6 (Day 1–7) plan**, focused on the most common, high‑yield parts of:

- Permutation & Combination (P&C)  
- Basic Probability  

Assume ~1–1.5 hours/day. If you have more time, increase the number of practice questions, not the number of topics.

Use aptitude sites and filter by:
- “Permutation and Combination”
- “Probability – Coins / Dice / Cards / Numbers”

---

## Overall Skill Targets for Week 6

By the end of this week you should comfortably:

- Use nPr and nCr for simple “arrangement” vs “selection” questions.  
- Handle basic word/number formation problems.  
- Calculate probabilities for:
  - Coins and dice.
  - Simple card questions.
  - “Number chosen from 1 to N” type events.

---

## Day 1 – Fundamentals of Counting + Permutation Basics

### 1. Concepts (20–25 min)

- Rule of product:
  - If a task can be done in m ways, and for each, another task in n ways → total m × n ways.
- Rule of sum:
  - Mutually exclusive events → add ways.
- Factorial n!:
  - n! = n × (n–1) × … × 1; 0! = 1.
- Basic permutation:
  - **nPr = n! / (n–r)!**
  - Permutation = arrangement (order matters).

Clarify:
- “In how many ways can…” often means “arrangement”.
- Distinguish between:
  - Selecting people (no order) vs arranging people in a row (order matters).

### 2. Guided Practice (30–35 min)

Target: **10–12 beginner questions**.

Problem types:

1. Straight permutation:
   - “In how many ways can 5 people be arranged in a row?”  
   - “In how many ways can 3 students be chosen and arranged from 5?” (5P3)
2. Using rule of product:
   - “A license plate has 2 letters followed by 3 digits. Letters can be A–Z, digits 0–9. How many plates possible (no restrictions)?”

3. Simple restrictions:
   - “In how many ways can 4 students sit in 4 chairs if a particular student must sit in the first chair?”

Reinforces:
- Basic factorial manipulation.
- When to multiply vs add.

### 3. Mixed Drill (10–15 min)

- 4–5 quick questions:
  - 2 easy permutations again (from above, without looking).
  - 2–3 very simple old topics (percent/ratio) as light revision.

### 4. Review (10–15 min)

- Make a small factorial table: 1! to 8! in your notes.
- For each wrong/surprising question, write:
  - “I multiplied these incorrectly because…” or  
  - “I forgot whether order matters.”

---

## Day 2 – Combinations (nCr) + Selection vs Arrangement

### 1. Concepts (20–25 min)

- Combination:
  - **nCr = n! / (r!(n–r)!)**
  - Selection: order does not matter.
- Relationship:
  - nPr = nCr × r! (choose r first, then arrange).
- Key recognition:
  - “Form a committee” ⇒ combination.  
  - “Arrange in a row” ⇒ permutation.

### 2. Guided Practice (30–35 min)

Target: **10–12 beginner→intermediate questions**.

Problem types:

1. Pure selection:
   - “In how many ways can 3 students be chosen from 7?” (7C3)
   - “A committee of 4 from 10 people: how many ways?”
2. Mixed: select then arrange:
   - “From 6 people, in how many ways can 3 be chosen and seated in a row?”
   - Approach: 6C3 × 3! or directly 6P3.
3. Simple word problems:
   - “In how many ways can a team of 2 boys and 2 girls be chosen from 5 boys and 4 girls?”

Reinforces:
- Clear difference between selection and arrangement.
- Translating language to math (e.g., “committee” vs “line-up”).

### 3. Mixed Drill (10–15 min)

- 4–6 questions:
  - 3 combination/permutation mixed.
  - 1–2 previously solved ones to check recall.
  - 1 quick arithmetic/percentage problem.

### 4. Review (10–15 min)

- For each question:
  - Write: “Type: selection / arrangement / selection + arrangement.”
- Note any confusion on whether to use nCr or nPr and why.

---

## Day 3 – Arrangements with Repetition & Constraints (Words, Digits)

### 1. Concepts (20–25 min)

- Arrangements of letters/digits with repetition:
  - For word with letters (total n), some repeated:
    - Total arrangements = n! / (p! q! r! …) where p,q,r… are counts of identical letters.
  - Example: “APPLE”
    - 5 letters, P repeated twice → 5! / 2!
- Basic positional restrictions:
  - “Vowels together” → treat vowels as one block.
  - “Even numbers at end” or “digit cannot be zero at start” → position-wise counting.

### 2. Guided Practice (30–40 min)

Target: **10–12 intermediate questions**.

Problem types:

1. Repetition in words:
   - “In how many ways can the letters of the word ‘APPLE’ be arranged?”  
     → 5! / 2!  
   - “In how many ways can the letters of ‘BALLOON’ be arranged?” (handle multiple repeats)
2. Basic restrictions:
   - “In how many ways can 4-digit numbers be formed from digits {1,2,3,4,5} if repetition is not allowed?”
   - “How many 3-digit even numbers can be formed using digits {1,2,3,4,5} without repetition?”

3. Vowels together (one example):
   - “In how many ways can letters of ‘BANANA’ be arranged so that all A’s are together?”  
     (Treat AAA as one block; handle N,N; etc., but keep 1–2 examples only.)

Reinforces:
- Counting with repeated elements.
- Constructive position-based reasoning.

### 3. Mixed Drill (10–15 min)

- 4–5 problems from:
  - 2 repetition/word problems.
  - 2 digit-formation problems with simple constraints.

### 4. Review (10–15 min)

- Write templates:
  - “Repeated letters: n! / (repeats!)”.
  - “Number formation: Choose the position → choose digits for each position.”
- Note 1 question where your initial counting double-counted or missed some cases.

---

## Day 4 – Probability Basics: Definition, Simple Events

### 1. Concepts (20–25 min)

- Probability of event E:
  - P(E) = (Number of favorable outcomes) / (Total number of equally likely outcomes)
- Complement:
  - P(not E) = 1 – P(E)
- Common simple scenarios:
  - Selecting an object from a group.
  - Picking a random number from 1 to N.

### 2. Guided Practice (30–35 min)

Target: **10–12 beginner probability questions**.

Problem types:

1. Simple selection:
   - “A bag has 5 red and 3 blue balls. One ball is drawn at random. Probability it is red?”
   - “Box with 10 bulbs, 3 defective. Probability bulb chosen is non-defective?”
2. Complement use:
   - “Probability of rain today is 0.3. What is probability it will not rain?”
3. Numbers from 1 to N:
   - “A number is chosen from 1 to 20. Probability it is a multiple of 3.”
   - “A number is chosen from 1 to 50. Probability it is prime (approx, use list up to 50 if needed).”

Reinforces:
- Basic favorable/total concept.
- Using complement when easier.

### 3. Mixed Drill (10–15 min)

- 4–5 questions:
  - 3 simple probability again (redo some quickly).
  - 1–2 combination/permutation problems (from Days 1–3).

### 4. Review (10–15 min)

- Write down:
  - “Total sample space size for each scenario” explicitly.
- Any confusion about “equally likely outcomes” (e.g., picking cards vs numbers) should be noted.

---

## Day 5 – Probability with Coins, Dice, and Simple Cards

### 1. Concepts (20–25 min)

- Coin toss:
  - One coin: {H, T} → 2 outcomes.
  - Two coins: {HH, HT, TH, TT} → 4 outcomes.
- Dice:
  - Single die: {1,2,3,4,5,6} → 6 outcomes.
  - Two dice: 6 × 6 = 36 ordered pairs.
- Cards (basic):
  - Standard deck: 52 cards.
  - 4 suits: Hearts, Diamonds, Clubs, Spades (13 each).
  - Face cards: J, Q, K (12 total).
- Use combination where helpful but keep to common patterns.

### 2. Guided Practice (30–40 min)

Target: **10–14 questions** (easy→intermediate).

Problem types:

1. Coins:
   - “Two coins are tossed. Probability of getting exactly one head?”
   - “Three coins tossed. Probability of at least two heads?”  
     (Use complement or direct counting.)
2. Dice:
   - “A die is rolled. Probability of getting an even number?”
   - “Two dice rolled. Probability sum is 7?”  
     (List pairs or recall standard outcomes.)

3. Cards:
   - “Probability of drawing a king from a standard deck?”
   - “Probability of drawing a red card?”
   - “Probability of drawing either a king or a queen?”  
     (Use addition rule, subtract overlap where needed.)

Reinforces:
- Comfortable with typical sample spaces: 2^n for n coins, 6/36 for common dice events.
- Recognizing when to add probabilities vs count directly.

### 3. Mixed Drill (10–15 min)

- 5–6 questions:
  - 3–4 probability (coins/dice/cards; re-solve 2 from above),
  - 1–2 basic nCr use (e.g., probability of choosing 2 girls from 3 girls and 2 boys).

### 4. Review (10–15 min)

- Write shortcut patterns:
  - For two dice: list all pairs that sum to 7, 8, etc., once for reference.
- Note any confusion regarding:
  - Overlap (e.g., card is both king and heart),
  - Whether to add or multiply probabilities (here mostly direct counting).

---

## Day 6 – Combined P&C + Probability Practice (Slightly Higher Level)

### 1. Concepts (15–20 min)

- Recap:
  - Counting methods (nCr) often used inside probability:
    - P = (favorable combinations) / (total combinations).
- Typical combined questions (but keep them simple):
  - E.g., selecting people from a group, selecting balls from an urn.

### 2. Guided Practice (30–40 min)

Target: **12–15 mixed questions (intermediate)**.

Problem types:

1. P&C integrated probability:
   - “From 5 boys and 3 girls, 3 students are selected at random. Probability that at least one girl is selected?”
     - Total = 8C3.  
     - Favourable = total – (all boys) = 8C3 – 5C3.
   - “From a group of 4 red and 4 blue balls, 2 are drawn. Probability that both are red?”

2. More dice/coin variations:
   - “Two dice thrown. Probability that the product is even.”
   - “Three coins tossed. Probability that not all are heads.”

3. Small arrangement-probability twist:
   - “If a letter is chosen at random from the word ‘BANANA’, what is probability that it is A?”
     - Favourable = 3, total = 6.

Reinforces:
- Using combinations to count favorable and total.
- Comfortable with “at least one” via complement.

### 3. Error-focused Drill (10–15 min)

- Pick 4 questions from this session (preferably 2 counting+prob and 2 dice/coins).
- Solve them again slowly.
- For each, write:
  - “Total outcomes = …”  
  - “Favorable outcomes = …”  
  - Check whether you used nCr correctly.

### 4. Quick Review (5–10 min)

- Jot down:
  - “At least one” → often easier as 1 – P(none).
  - “Probability with selection from group” → mostly combination-based.

---

## Day 7 – Week 6 Mini Mock + Consolidation

### 1. Timed Mini Mock (35–40 min)

Create/choose a mixed test of **20–25 questions**:

- P&C: 10–12 Q
  - 3–4 basic permutations/combinations.
  - 3–4 word/digit arrangement with or without simple constraints.
  - 2–3 repetition/position-based problems.

- Probability: 10–13 Q
  - 3–4 simple bag/selection/balls questions.
  - 3–4 coins/dice.
  - 2–3 basic card or “choose a number from 1 to N” type.

Sit for 35–40 minutes:
- First pass: solve easy direct ones (no heavy constraints).
- Second pass: attempt the moderate ones.
- Skip anything that seems like a contest-level combinatorics puzzle; you don’t need them for most placements.

### 2. Mock Review (30–40 min)

For each wrong/guessed/skipped question:

- Diagnose:
  1. Misidentified type (permutation vs combination?).
  2. Wrong counting (double counting or missing cases).
  3. Misunderstood probability setup (wrong total outcomes).
  4. Calculation slip (factorial/combination arithmetic).

- For (1):
  - Re-read the question and identify keywords: “arrange”, “form a committee”, “in a row”, “select”.
- For (2):
  - Try a smaller similar example and count manually to verify your formula.
- For (3):
  - Explicitly write sample space: how many total ways? how many favourable?
- For (4):
  - Rewrite factorials or use nCr symmetries (nCr = nC(n–r)) to simplify.

### 3. Week 6 Summary Sheet (15–20 min)

On a single sheet, write:

- P&C:
  - nPr, nCr formulas and relationship.
  - Word/digit arrangement patterns (repetition, position-based).
  - Mini-checklist: “Is order important?” → yes: permutation; no: combination.

- Probability:
  - P(E) = favourable / total, and complement rule.
  - Coin/dice total outcomes and a few standard ones (like sum=7 on 2 dice).
  - Template: When selection from group: use combinations for counting.

Keep this sheet with your previous weeks’ summaries for quick revision before full mocks.

---

If you tell me which specific companies/roles you’re targeting, I can suggest which of these P&C/Probability patterns are most important for those exact exams and how many extra mocks or topic-wise tests to add.
