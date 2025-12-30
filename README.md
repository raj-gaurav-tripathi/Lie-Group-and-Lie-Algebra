# Lie Groups and Lie Algebras in Physics

This repository contains a set of **self-contained lecture-style notes** introducing **Lie groups and Lie algebras** from a **physicist’s perspective**, with a strong emphasis on **symmetries, generators, and representations** used in quantum mechanics and relativistic physics.

The document is written to bridge the gap between abstract group theory and its concrete use in **particle physics, quantum mechanics, and field theory**.

---

## Contents Overview

The notes develop the subject progressively:

### i). Physical Motivation

* Classification of particles by **mass, charge, and spin**
* Scalars, vectors, and spinors as different representations
* How physical quantities transform under rotations and boosts

### ii). Group Theory Essentials

* Definition of a group (closure, identity, inverse, associativity)
* Rotation matrices as a concrete example
* Difference between discrete groups and **Lie (continuous) groups**

### iii). Lie Groups and Generators

* The rotation group **SO(3)** as a prototype Lie group
* Matrix exponentials and continuous transformations
* Generators obtained via derivatives at the identity

### iv). Matrix Exponentials (Worked in Detail)

* Taylor-series definition of the matrix exponential
* Explicit computation of rotation matrices from generators
* Why exponentiation naturally produces group elements

### v). Lie Algebras

* Why matrix multiplication alone is insufficient
* The **Lie bracket (commutator)** as the fundamental operation
* The Lie algebra **so(3)** and its commutation relations

### vi). Lie Algebras as Tangent Spaces and Structure Constants

* Geometric interpretation: Lie algebra as the tangent space at identity
* Closure under addition, scalar multiplication, and commutators
* Definition and physical meaning
* Levi-Civita symbol and the structure constants of **so(3)**

### vii). Lorentz Group

* The proper orthochronous Lorentz group **SO⁺(1,3)**
* Rotations and boosts as generators
* Embedding of **so(3)** inside **so(1,3)**

### viii). Representations

* Spin-1 vs spin-1/2 representations
* Why multiple representations exist for the same Lie algebra
* Physical meaning of different representations

### ix). Mathematical vs Physics Conventions

* Hermitian vs anti-Hermitian generators
* Why physicists insert factors of ( i )
* Translation between math and physics notation

---


## 📂 Repository Structure

```
.
├── main.tex        # Main LaTeX source
├── Lie_Group_and_Lie_Algebra_1.pdf      # Compiled document
└── README.md       # This file
```

---

##  Compilation

To compile locally:

```bash
pdflatex main.tex
```

(Compile twice if the table of contents does not appear correctly.)

---

##  Philosophy of These Notes

* Generators come **before** abstract axioms
* Calculations are shown explicitly
* Geometry and algebra are tied to **physical transformations**
* The Lie algebra is treated as the *real object of interest* in physics

> *“Lie groups tell you what transformations exist.
> Lie algebras tell you how physics actually moves.”*

---

##  Status

This is a **living document** and may be expanded in the future to include:

* SU(2), SU(3), and gauge groups
* Connection to Noether’s theorem
* Applications in quantum field theory

---

##  Author

**Raj Gaurav Tripathi**
Department of Physics, 
IISER Kolkata

---------------------------------------------------------------------------------
