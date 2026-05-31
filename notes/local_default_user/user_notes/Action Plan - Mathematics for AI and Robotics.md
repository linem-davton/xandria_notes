# Action Plan: Mathematics for AI & Robotics

**Started:** 2026-06-01 | **Currently reading:** Strang's Linear Algebra and Its Applications

---

## Phase 1 — Linear Algebra (Foundation)
*Core prerequisite for everything below.*

| # | Topic | Book (in library) | Status |
|---|-------|-------------------|--------|
| 1 | Matrices, elimination, vector spaces | Strang — Linear Algebra and Its Applications | **in progress (2%)** |
| 2 | Eigenvalues, eigenvectors, SVD | same book, chapters 5–6 | next |
| 3 | Linear transformations, orthogonality | same book, chapters 3–4 | next |
| 4 | Applications in ML & data | Brunton — Data Driven Science & Engineering | unread |
| 5 | Numerical linear algebra | Golub — Matrix Computations | unread (reference) |

**Goal:** Solid grasp of vector spaces, eigen-decomposition, SVD, least-squares.

---

## Phase 2 — Calculus & Analysis

| # | Topic | Book (in library) | Status |
|---|-------|-------------------|--------|
| 1 | Single & multivariable calculus | Tarasov — Calculus | in progress |
| 2 | Vector calculus, gradients, optimization | Kreyszig — Advanced Engineering Mathematics | unread |
| 3 | ODEs (dynamics, controls) | same book | unread |
| 4 | PDEs (robotics, physics sim) | same book | unread |
| 5 | Practical estimation skills | Mahajan — Street-Fighting Mathematics | in progress (7%) |

**Goal:** Comfortable with gradients, chain rule, ODEs for dynamics, optimization.

---

## Phase 3 — Probability & Statistics

| # | Topic | Book (in library) | Status |
|---|-------|-------------------|--------|
| 1 | Probability fundamentals, distributions | Riley — Mathematical Methods for Physics and Engineering | in progress (36%) |
| 2 | Bayes, MLE, MAP | same book (stats sections) | in progress |
| 3 | Information theory basics | Ashby — An Introduction to Cybernetics | in progress |
| 4 | Stochastic processes, RL foundations | Sutton & Barto papers in library | unread |

**Goal:** Bayesian reasoning, uncertainty, information theory for ML.

---

## Phase 4 — AI & Machine Learning Mathematics

| # | Topic | Book (in library) | Status |
|---|-------|-------------------|--------|
| 1 | ML fundamentals (Python) | Müller — Intro to ML with Python | **97% done!** |
| 2 | Optimization theory | Butenko — Numerical Methods and Optimization | unread |
| 3 | Neural network math | supplement with papers in library | — |
| 4 | Reinforcement learning theory | Silver / Sutton papers in library | unread |

**Goal:** Understand gradient descent, backprop, loss landscapes, RL value functions.

---

## Phase 5 — Robotics Mathematics

| # | Topic | Book (in library) | Status |
|---|-------|-------------------|--------|
| 1 | Kinematics & dynamics | Springer Handbook of Robotics | **in progress (40%)** |
| 2 | Control theory (state-space) | same handbook | in progress |
| 3 | Embedded & mobile robots | Bräunl — Embedded Robotics | in progress (4%) |
| 4 | Robot programming | Bräunl — Robot Adventures in Python and C | in progress |
| 5 | Mechanical foundations | Hibbeler — Engineering Mechanics: Dynamics | in progress (1%) |

---

## Recommended Reading Order

```
Phase 1 (Linear Algebra) ──────┐
                               ├──> Phase 4 (AI Math)
Phase 2 (Calculus) ────────────┘
                               │
Phase 3 (Probability/Stats) ───┘
                               ├──> Phase 5 (Robotics Math)
Phase 1 continued (Numerical) ─┘
```

**Start with Strang's Linear Algebra cover-to-cover**, then branch into Kreyszig for calculus/ODEs and Riley for probability. Once fluent in vectors/matrices/gradients, dive into Brunton's Data Driven Science for the ML math bridge, then tackle the Springer Handbook of Robotics for the robotics side.

---

## Weekly Commitment (suggested)

- **Mon/Wed/Fri:** Linear Algebra (working through Strang)
- **Tue/Thu:** Alternate between calculus (Kreyszig) and probability (Riley)
- **Weekend:** Robotics reading or ML practice (Müller book is almost done!)
