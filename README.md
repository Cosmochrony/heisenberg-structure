**Quaternionic Rigidity of Admissible Morphisms:  
Every Admissible Φ₍q,ρ₎ Necessarily Factors through su(2)**

## Quick Summary

This paper resolves a central open problem of the spectral admissibility programme:  
the existence and structure of admissible morphisms

Φ₍q,ρ₎ : V_q → V_ρ

linking Weil representation spaces (Heisenberg side) to representation spaces of 2I ⊂ SU(2).

**Main result (rigidity theorem):**  
Any morphism satisfying the three structural admissibility constraints is *forced* to factor through

su(2) ≃ Im ℍ

The quaternionic structure is therefore **not a modelling choice**, but the **unique fixed point**
compatible with:

- involution equivariance (χ → −χ)
- quadratic compatibility with σ_pair
- admissibility naturality (Π-structure only)

This upgrades O23 (dim = 3) into a **categorical universality statement**.

## Context

This paper sits at a critical point of the Cosmochrony programme:

- **O23**: establishes quaternionic minimality  
  → dimℝ(Im ℍ) = 3

- **O24**: establishes the chain  
  c_χ → δ_pair → β*

- **O26**: introduces the representation-theoretic dictionary  
  (σ_pair ↔ Hilbert–Schmidt norm) but assumes Φ₍q,ρ₎

👉 **This paper closes that gap**:  
Φ₍q,ρ₎ is not just assumed — it is **forced and uniquely determined**.

## Core Problem

Does there exist a morphism

Φ₍q,ρ₎ : V_q → V_ρ

such that:

1. **Z₂-equivariance**  
   c ↔ q − c

2. **Quadratic compatibility**  
   σ_pair(n) ∼ ‖Φ(v_c)‖² ‖Φ(v_{q−c})‖²

3. **Naturality**  
   depends only on admissibility structure (Π, BI, Q₈)

## Main Result

**Rigidity Theorem**

Any Φ₍q,ρ₎ satisfying (1)–(3):

- must factor through the admissible quotient  
  H_eff = Im Π ∩ Ntrl

- and this quotient is **uniquely identified** with

  su(2)

No alternative structure survives all constraints:

| Candidate structure | (a) | (b) | (c) | Verdict            |
|---------------------|-----|-----|-----|--------------------|
| ℝⁿ (abelian)        | ✗   | ✗   | ✓   | excluded           |
| ℂⁿ                  | ✓   | ✓   | ✗   | not canonical      |
| generic Hilbert     | ✓   | ✓   | ✗   | pipeline-dependent |
| ℍ / su(2)           | ✓   | ✓   | ✓   | **unique**         |

## Canonical Construction

The morphism is explicitly constructed as:

Φ₍q,ρ₎ = ρ ∘ ι ∘ π

and is:

- unique up to unitary equivalence
- fully determined by admissibility

## Interpretation

This result closes the structural chain:

emergence  
→ non-injectivity  
→ pair structure  
→ quadratic observable  
→ su(2)

Consequences:

- su(2) is **not postulated**, but **derived**
- the quaternionic sector is the **minimal admissible non-abelian structure**
- β* acquires a **representation-theoretic meaning**:

  → scaling exponent of norm growth in su(2)

## Key Implications

### 1. Uniqueness of the admissible target

There is no freedom in choosing the representation space:  
admissibility collapses all candidates to su(2).

### 2. Structural origin of SU(2)

SU(2) emerges as:

- the minimal non-commutative structure
- compatible with non-factorisability (A3)
- compatible with BI parity

### 3. Closure of the O-series chain

The previously empirical link

σ_pair → β*

is now:

- geometrically grounded
- representation-theoretically interpreted

## What This Paper Does NOT Do

- Does not compute Φ₍q,ρ₎ numerically
- Does not extend beyond the admissible sector
- Does not derive full quantum mechanics (done in Q1)

## Open Problem

The remaining task is:

→ explicit realisation of Φ₍q,ρ₎ in the spectral pipeline

i.e.:

- embedding construction
- numerical verification
- link with O26 effective dimension test

## Keywords

non-injective projection; admissible morphisms; quaternionic rigidity; su(2);  
Weil representation; spectral admissibility; pair observable;  
Born–Infeld constraint; emergence; representation theory

## Reference

See full paper: :contentReference[oaicite:0]{index=0}
