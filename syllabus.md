# Regional Quantitative Problem-Solving Circle: Course Syllabus

**Lead Architect & Seminar Director:** Mohamed Jad Srifi  
**Term:** 12-Week Intensive Seminar Sequence  
**Audience:** Secondary students preparing for national and international contests (MathMaroc Olympiad track, AIME, AMC 12)  
**Repository Tree:** Source LaTeX files and compiled PDFs are located in `/problem-sets/` and `/solution-keys/`

---

## Pedagogical Structure & Seminar Architecture

The seminar meets biweekly for 90 minutes. To develop mathematical maturity through active proof construction rather than passive lecture absorption, sessions follow a strict four-phase structure:

| Phase | Duration | Focus | Operational Mechanics |
| :--- | :---: | :--- | :--- |
| **I. Computational Warm-up** | 10 Mins | Baseline cognitive activation | 3 rapid AMC-12 / MathMaroc Junior caliber problems to calibrate speed and working memory. |
| **II. Invariant Formulation** | 20 Mins | Theoretical framework | Chalk-talk introducing the core mathematical invariant, logical notation, and operational boundaries. No arbitrary numbers. |
| **III. Collaborative Struggle** | 40 Mins | Active synthesis & proof design | Cohort splits into pods of three to resolve Olympiad-caliber problems. Interventions are strictly Socratic via counter-examples. |
| **IV. Peer Defense** | 20 Mins | Rigorous cross-examination | A designated student defends a proposed proof at the board against peer interrogation hunting for unproven lemmas or boundary flaws. |

---

## Academic Modules

### Module 1 (Weeks 1–2): Proof Techniques & Invariants
* **Core Concept:** Formalizing extremal arguments, the Well-Ordering Principle of non-negative integers, and monovariants. Moving from computational algebra to structural reasoning.
* **Core Invariant:** Every non-empty finite ordered set has a strict minimum and maximum element. Monovariants across finite state transitions must terminate at an extremal state.
* **Representative Problems:**
  1. *Distinct Distances Problem (Combinatorial Geometry):* Minimum distance pairs forcing mutual ball exchanges under deterministic nearest-neighbor rules.
  2. *Sylvester-Gallai Theorem (Extremal Area):* Minimizing perpendicular point-to-line distances to prove the existence of an ordinary line.
  3. *Harmonicity of an Infinite Grid:* Mean-value propagation and bounds on an infinite chessboard.
* **Assigned Deliverable:** `pset1_invariants.pdf`

---

### Module 2 (Weeks 3–4): Discrete Probability & Combinatorics
* **Core Concept:** Linearity of Expectation (LoE) for correlated systems and deconstructing discrete counting via indicator random variables:
  $$\mathbb{E}\left[\sum X_i\right] = \sum \mathbb{E}[X_i]$$
* **Core Invariant:** Expectation operators are strictly linear over sums of random variables, regardless of independence.
* **Representative Problems:**
  1. *HMMT Babies Circle Problem:* Symmetry and local marginal probability using binary indicator random variables.
  2. *Expected Fixed Points in Random Permutations:* Linearity over dependent cycle structures.
  3. *AIME Correlated Squares Problem:* Complementary counting and inclusion-exclusion over coordinate product spaces.
* **Assigned Deliverable:** `pset2_probability.pdf`

---

### Module 3 (Weeks 5–6): Number Theory & Diophantine Equations
* **Core Concept:** Modular arithmetic as closed algebraic rings, polynomial reduction via the Euclidean algorithm, and properties under prime moduli.
* **Core Invariant:** Greatest Common Divisors are strictly invariant under Euclidean division steps: $\gcd(a,b) = \gcd(a - kb, b)$.
* **Representative Problems:**
  1. *AIME 1986 Polynomial Divisibility:* Synthetic division isolating constant residual divisors $(n+10) \mid 900$.
  2. *Factorial Base Expansions:* Uniqueness bounds and recursive residue extraction.
  3. *Perfect Square Diophantines:* Completing the square to reduce polynomial relations to finite divisor systems.
* **Assigned Deliverable:** `pset3_number_theory.pdf`

---

### Module 4 (Weeks 7–8): Graph Theory Foundations
* **Core Concept:** Topological invariants, bipartite matchings, Eulerian traversals, and structural induction on acyclic trees.
* **Core Invariant:** The degree-sum equation $\sum_{v \in V} \deg(v) = 2|E|$ holds across all finite graphs; traversals strictly conserve transition parity.
* **Representative Problems:**
  1. *The Handshake Lemma:* Parity partitioning over odd-degree vertices.
  2. *Spanning Tree Uniqueness:* Cycle and cut properties under distinct edge-weight distributions.
  3. *Eulerian Circuits:* Necessary and sufficient conditions based on local incident edge balance.
* **Assigned Deliverable:** `pset4_graphs.pdf`

---

### Module 5 (Weeks 9–10): Algorithmic Formulation & Invariants
* **Core Concept:** Proving greedy optimality via formal Exchange Arguments and identifying optimal substructure in dynamic programming state transitions.
* **Core Invariant:** Adjacent transpositions preserve exterior partial sums; optimal substructure holds if local perturbations do not degrade the global evaluation metric.
* **Representative Problems:**
  1. *Interval Scheduling Maximization:* Greedy choice correctness via exchange replacements.
  2. *Lateness Minimization:* Inversion elimination through adjacent swaps.
  3. *Matrix Chain State Bounds:* Optimal subproblem decomposition.
* **Assigned Deliverable:** `pset5_algorithms.pdf`

---

### Module 6 (Weeks 11–12): Mathematical Modeling & Synthesis
* **Core Concept:** Projecting stochastic processes onto directed graphs, first-step analysis, and stationary distributions ($\pi = \pi P$) in finite Markov chains.
* **Core Invariant:** Memoryless property of Markov processes; convergence of irreducible, aperiodic transition systems.
* **Representative Problems:**
  1. *AIME Divisor State Machines:* Parity and prime-factor counting on switch networks.
  2. *Random Walk Expected Hitting Times:* Linear systems of recurrences under absorbing boundaries.
  3. *Synthesis Contest Examination:* 3-hour comprehensive problem set integrating invariants, expectation, and graphs.
* **Assigned Deliverable:** `pset6_markov_chains.pdf`

---

## Operational Benchmarks & Cohort Standards

To ensure serious academic discipline, all participating students were held to standard technical metrics:
* **LaTeX Typesetting:** Problem sets were required to be submitted in compiled `.pdf` format along with clean `.tex` sources.
* **Defense Standards:** Seminar proofs were evaluated not on computational answers, but on the explicit identification of base cases and invariant properties.
