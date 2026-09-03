# Regional Quantitative Problem-Solving Circle

### 12-Week Olympiad Mathematics Curriculum

**Program Director & Lead Architect:** Mohamed Jad Srifi

**Term:** Fall 2025 – Spring 2026

**Audience:** Secondary students preparing for national and international contests (MathMaroc Olympiad track, AIME, and AMC 12)

---

## Overview

The **Regional Quantitative Problem-Solving Circle** is a 12-week intensive mathematics seminar designed to develop the structural and proof-based reasoning required for advanced mathematical competitions.

The curriculum focuses on **discrete mathematics, combinatorics, probability, graph theory, and mathematical modeling**, with an emphasis on moving beyond routine algebraic manipulation toward rigorous problem-solving strategies.

This repository contains the program's pedagogical materials, including weekly handouts, LaTeX source files, compiled problem sets, and formal solution keys.

The curriculum is designed to bridge the gap between conventional secondary-school mathematics and the **structural reasoning expected in olympiad mathematics, university-level mathematics, and theoretical computer science**.

---

## Course Objectives

### Structural Proof Techniques

Students develop the ability to recognize and exploit mathematical structure through techniques including:

* Extremal Principle
* Invariants
* Monovariants
* Exchange Arguments
* Proof by contradiction
* Constructive arguments
* Strategic case analysis

The objective is to replace brute-force manipulation with deliberate structural reasoning.

### Probabilistic Modeling

The probability component develops tools for analyzing complicated stochastic systems, including:

* Indicator random variables
* Linearity of Expectation
* Conditional probability
* Expected value
* Probabilistic counting
* Random processes
* Markov chains

Particular emphasis is placed on understanding how **linearity of expectation can simplify dependent systems without requiring independence**.

### Graph Theory and Discrete Structures

Students learn to represent discrete relationships using graphs and exploit their structural properties.

Topics include:

* Degree-sum invariants
* Graph connectivity
* Bipartite graphs
* Matchings
* Eulerian paths and circuits
* Graph traversal
* Structural graph arguments

---

## Curriculum Structure

The 12-week curriculum is organized around progressively more sophisticated methods of mathematical reasoning.

| Week   | Focus                                                    |
| ------ | -------------------------------------------------------- |
| Week 1 | Extremal Principle                                       |
| Week 3 | Linearity of Expectation                                 |
| Week 7 | Graph Invariants                                         |
| —      | Additional topics covered throughout the 12-week program |

See [`syllabus.md`](syllabus.md) for the complete curriculum and weekly schedule.

---

## Repository Structure

```text
regional-quant-circle/
│
├── README.md
├── syllabus.md
├── LICENSE
│
├── handouts/
│   ├── Week1_Extremal_Principle.pdf
│   ├── Week3_Linearity_of_Expectation.pdf
│   └── Week7_Graph_Invariants.pdf
│
├── problem-sets/
│   │
│   ├── tex-sources/
│   │   ├── pset1_invariants.tex
│   │   ├── pset2_probability.tex
│   │   └── pset6_markov_chains.tex
│   │
│   └── compiled-pdfs/
│       ├── pset1_invariants.pdf
│       ├── pset2_probability.pdf
│       └── pset6_markov_chains.pdf
│
└── solution-keys/
    │
    ├── tex-sources/
    │   ├── sol1_invariants.tex
    │   └── sol2_probability.tex
    │
    └── compiled-pdfs/
        ├── sol1_invariants.pdf
        └── sol2_probability.pdf
```

### `handouts/`

Supplementary lecture and chalk-talk material covering the mathematical techniques introduced throughout the curriculum.

Examples include:

* **Extremal Principle**
* **Linearity of Expectation**
* **Graph Invariants**

### `problem-sets/`

Contains the competition problem sets used in the program.

The directory is divided into:

* `tex-sources/` — editable LaTeX source files
* `compiled-pdfs/` — publication-ready PDF versions

Current problem sets include topics such as:

* Invariants
* Probability
* Markov Chains

### `solution-keys/`

Contains rigorous solutions corresponding to selected problem sets.

As with the problem sets, the directory separates:

* `tex-sources/` — LaTeX source
* `compiled-pdfs/` — compiled solution documents

Solutions emphasize **proof structure and transferable techniques**, rather than simply presenting final answers.

---

## Pedagogical Methodology

The seminars were conducted using a **Socratic flipped-classroom methodology**.

Students encounter problems before receiving complete explanations of the underlying technique. This forces them to develop conjectures, test approaches, identify structural patterns, and defend their reasoning.

The intended learning process is:

```text
Problem
   ↓
Independent Attempt
   ↓
Exploration
   ↓
Collaborative Discussion
   ↓
Peer Defense
   ↓
Formal Proof
   ↓
Generalization
```

### Collaborative Struggle

The problem sets intentionally provide limited immediate scaffolding.

Students are expected to:

1. Attempt the problem independently.
2. Form and test conjectures.
3. Identify relevant invariants or structures.
4. Develop competing approaches.
5. Defend their reasoning.
6. Critique alternative solutions.
7. Formalize the final argument.
8. Extract the general technique.

The purpose is to develop **mathematical maturity**, not merely improve speed at routine exercises.

---

## Curriculum Philosophy

The central philosophy of the program is:

> **Do not teach students what to calculate. Teach them what to notice.**

Many difficult olympiad problems become tractable once the correct structure is identified.

A complicated counting problem may reduce to **linearity of expectation**.

A process that appears to require exhaustive simulation may be governed by a **monovariant or invariant**.

An optimization problem may become accessible through the **Extremal Principle**.

A problem involving pairwise relationships may reveal its structure when represented as a **graph**.

The curriculum therefore prioritizes:

* Structural recognition
* Proof construction
* Abstraction
* Mathematical modeling
* Generalization
* Rigorous communication

over repetitive computational practice.

---

## Intended Outcomes

By completing the curriculum, students should be able to:

* Approach unfamiliar olympiad problems systematically.
* Recognize useful invariants and extremal structures.
* Construct rigorous mathematical proofs.
* Apply indicator variables and linearity of expectation.
* Model discrete systems using graph theory.
* Analyze Eulerian and bipartite structures.
* Reason about basic Markov-chain models.
* Defend mathematical arguments under peer scrutiny.
* Generalize techniques beyond individual problems.
* Communicate solutions in a precise mathematical form.

---

## Target Competitions

The curriculum is designed to develop skills relevant to competitions including:

* **AIME**
* **USAMO**
* **MathMaroc**
* **HMMT**

The emphasis, however, is on developing general mathematical problem-solving ability rather than training exclusively for any single competition.

---

## Academic Scope

**Olympiad Mathematics · Combinatorics · Discrete Mathematics · Probability · Graph Theory · Mathematical Proof · Algorithmic Thinking**

The program serves as a bridge between advanced secondary mathematics and the proof-oriented reasoning encountered in **pure mathematics, theoretical computer science, and quantitative disciplines**.
