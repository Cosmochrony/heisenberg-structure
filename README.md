This repository contains the source of the **Heisenberg Structure Cosmochrony paper**  
[*Non-Factorisability and the Emergence of Heisenberg Structure  
from Admissibility Constraints*](out/HeisenbergStructure.pdf).

This work provides the **structural derivation of the admissible fibre**, upgrading a
previously stated identification into a full theorem.

It addresses the following foundational question:

> Given the admissibility axioms (A1–A3) and Born–Infeld parity,
> what algebraic structure is necessarily realised by the admissible fibre $F_n$?

## Quick Summary

The paper proves that the answer is unique and fully determined.

The admissible fibre is not an arbitrary structure.

It is **necessarily Heisenberg**.

More precisely:

- any finite, minimal, non-pre-resolved structure of observable directions
  must carry a non-trivial commutator
- this commutator is forced to be central
- the resulting algebra is necessarily the Heisenberg algebra
- the centre has prime order
- the fibre is canonically identified with the Weil representation
  \[
  F_n \simeq V_\rho
  \]

This turns the appearance of the Heisenberg group from an empirical observation
into a **structural theorem**.

## Context

The foundational paper establishes that:

- physical structure arises from admissible non-injective transitions
- admissibility is governed by Axioms A1–A4
- A3 forbids premature selection inside the admissible fibre
- non-injectivity implies genuine multiplicity of admissible directions

The spectral admissibility programme (O-series) further establishes:

- the parity fibre $\{c, q-c\}$ (O18)
- projection locking (O22)
- quaternionic minimality and three stable directions (O23)

However:

- the identification $F_n \simeq V_\rho$ was only stated, not proved
- the emergence of a non-abelian structure was not derived from first principles
- the Heisenberg group appeared as a model, not a necessity

This defines the scope of the present paper. :contentReference[oaicite:0]{index=0}

## Core Result

The paper establishes that:

> Under A1–A3 and Born–Infeld parity, the symmetry group of the admissible
> fibre is isomorphic to $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$ for a prime $q$,
> and the fibre itself is isomorphic to the Weil representation $V_\rho$.

Thus:

- the Heisenberg structure is not assumed
- it is **forced by admissibility**

## Main Structural Results

### 1. Admissible non-factorisability

*Result.* Axiom A3 implies that the admissible fibre cannot be factorised
into independent components.

Thus:

- no decomposition $F_n = F^{(1)} \oplus F^{(2)}$ is admissible
- admissible directions remain intrinsically coupled
- this forces the presence of a non-trivial commutator

This is the single non-trivial input of the paper.

### 2. Emergence of a non-trivial commutator

*Result.* Non-factorisability implies the existence of generators $X, Y$
such that:
\[
[X, Y] \neq 0.
\]

Thus:

- the admissible structure cannot be abelian
- observable directions do not commute under admissible composition

### 3. Centrality of the commutator

*Result.* Minimality and admissibility constraints force:
\[
[X, Y] = Z, \quad [X, Z] = [Y, Z] = 0.
\]

Thus:

- the commutator is central
- the algebra is a central extension of an abelian structure

### 4. Classification as Heisenberg algebra

*Result.* By classification of finite nilpotent Lie algebras of class 2:

- the only compatible structure is the Heisenberg algebra
- the centre must have prime order

Thus:

\[
\mathrm{Sym}(F_n) \simeq \mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})
\]

### 5. Identification with the Weil representation

*Result.* By Stone–von Neumann:

- there exists a unique irreducible representation of the Heisenberg group
  with fixed central character
- this representation is the Weil representation $V_\rho$

Thus:

\[
F_n \simeq V_\rho
\]

This completes the structural identification.

## Foundational Chain

The derivation is fully internal:

Admissibility axioms (A1–A3)  
$\to$ non-factorisability  
$\to$ non-trivial commutator  
$\to$ central extension  
$\to$ Heisenberg algebra  
$\to$ Weil representation

No external quantum structure is postulated.

## Mathematical Role of the Paper

This paper provides:

- a derivation of non-abelian structure from admissibility
- a proof that the Heisenberg group is unavoidable
- a canonical identification of the admissible fibre
- a bridge between axioms and representation theory

More precisely, it:

- turns a structural remark into a theorem
- removes arbitrariness in the choice of fibre structure
- grounds the appearance of canonical commutation relations

## Epistemic Structure

### Established input

- admissibility axioms A1–A3
- Born–Infeld parity
- non-injectivity as structural necessity
- minimality of admissible structure

### New results

- admissible non-factorisability lemma
- derivation of non-commutativity
- proof of central extension
- classification as Heisenberg algebra
- prime order of the centre
- identification $F_n \simeq V_\rho$

### Remaining open problems

- extension to the large-$q$ (continuum) limit
- relation to full Hilbert space structure
- embedding into higher admissible sectors
- explicit link with representation selection (O25–O27)

## Interpretation of the Result

The conceptual shift is:

- previous view: Heisenberg structure is a useful model
- present result: Heisenberg structure is **forced**

Thus:

- non-commutativity is not postulated
- canonical quantisation is not an input
- the uncertainty principle becomes structural

## Corollaries

### Uncertainty principle

The non-commutativity of generators implies:

- no simultaneous sharp resolution of conjugate directions
- uncertainty is a property of the proto-state, not measurement

### Canonical quantisation

The standard commutation relations arise as:

- the algebraic structure of admissible directions
- not as a rule imposed on observables

## Structural Role in the Programme

This paper provides the missing link between:

- admissibility axioms (foundation)
- spectral results (O-series)
- quantum structure (Q1 and beyond)

It establishes:

- the algebra underlying admissible fibres
- the necessity of non-abelian structure
- the representation-theoretic backbone of the framework

## What This Paper Adds

- formalisation of admissible non-factorisability
- derivation of non-commutativity
- proof of Heisenberg structure
- identification of the Weil representation
- structural origin of uncertainty relations
- removal of arbitrariness in fibre modelling

## Outcome

The admissible fibre is now:

- structurally determined
- non-abelian by necessity
- Heisenberg in symmetry
- Weil in representation

The quantum algebraic structure is:

- derived
- intrinsic
- unavoidable

## Residual Open Problems

### Large-$q$ limit

Understand how the discrete Heisenberg structure lifts to continuous phase space.

### Representation selection

Identify which irreducible sector is physically realised in the spectral pipeline.

### Higher structures

Determine whether higher-rank or non-Heisenberg extensions can arise under relaxed constraints.

### Integration with quantum sector

Complete the bridge toward full Hilbert space reconstruction.

## Status

The programme now establishes:

- axiomatic foundation of admissibility
- emergence of non-injectivity
- structural origin of irreversibility
- derivation of Heisenberg structure

The remaining steps concern:

- representation selection
- continuum limit
- full quantum reconstruction

## Repository Structure

```text
paper/
├── out/      # Compiled PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau: Non-Factorisability and the Emergence of Heisenberg Structure
from Admissibility Constraints
Zenodo, 2026.

# Acknowledgements

Portions of the conceptual synthesis, structural organisation, and editorial refinement
benefited from iterative interactions with large language models used as analytical assistants.

All theoretical results, computations, and interpretations remain the sole responsibility
of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- admissible non-factorisability
- Heisenberg emergence
- Weil representation structure
- algebraic classification
- large-$q$ behaviour

are welcome.

Please open an issue to discuss conceptual points, technical details, or possible
extensions.
