# A Finite Obstruction to Heisenberg Carrier Selection

This repository contains the source of the Cosmochrony companion paper
*A Finite Obstruction to Heisenberg Carrier Selection from Admissibility Constraints*.

Version 2.0.0 is a major corrective revision that supersedes the former positive
carrier-selection claim. The finite countermodel and the surviving conditional
representation theory are integrated in this paper.

## Main result

The paper tests the finite algebraic contract used to select the admissible carrier:

- a finite-dimensional complex carrier;
- a faithful irreducible unitary action of a finite group;
- a minimal generating pair exchanged by an involutive automorphism;
- a non-trivial commutator.

These properties do not imply that the commutator is central.
The countermodel is

\[
G=\mathfrak{S}_3,\qquad X=(12),\qquad Y=(23),
\]

acting on the two-dimensional zero-sum subspace of \(\mathbb{C}^3\).
The pair \(X,Y\) satisfies the full contract, while
\([X,Y]=(132)\notin Z(\mathfrak{S}_3)\).

The paper also proves that irreducibility does not force a central subgroup to
have prime order.
By Schur's lemma, a central subgroup acts through one character on an
irreducible complex representation, so it does not produce several non-zero
character eigenspaces.

## Epistemic boundary

The established result is an obstruction to carrier selection:

\[
\text{admissibility contract}
\not\Longrightarrow
\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z}).
\]

The result does not identify \(\mathfrak{S}_3\) as a physical carrier.
It leaves intact mathematics proved after a finite Heisenberg group, a
non-trivial central character, or an associated Weil module has been supplied.

Class-two nilpotence, a specified central extension, or a non-degenerate
symplectic commutator law would exclude the countermodel, but each is an
additional selection input until independently derived.

## Relation to positive constructions

The obstruction is compatible with established positive reconstruction routes.
A finite Abelian configuration group together with an irreducible transitive
system of imprimitivity yields a discrete Weyl system through Mackey covariance.
Alternatively, a supplied finite symplectic vector space defines its Heisenberg
central extension, after which Stone–von Neumann and symplectic functoriality
produce the Heisenberg and Weil representations.

The audited admissibility contract supplies neither covariant localisation nor
a non-degenerate symplectic form. These constructions therefore identify
additional sufficient inputs rather than repairing the failed implication.

## Representation terminology

Stone-von Neumann identifies the irreducible Heisenberg, or Schrödinger,
representation associated with a non-trivial central character.
The Weil representation is the distinct associated action of the symplectic
automorphism group on the same carrier.
The paper keeps these two representation-theoretic levels separate.

## Build

Requirements:

- a LaTeX installation with `pdflatex` and `bibtex`;
- the standard packages listed in the manuscript preamble.

Compile with:

```bash
./compile.sh
```

The generated PDF is written to:

```text
out/HeisenbergStructure.pdf
```

Generated build artefacts are not versioned.

## Repository structure

```text
.
├── CITATION.cff
├── README.md
├── compile.sh
├── tex/
│   ├── HeisenbergStructure.tex
│   └── cosmochrony-bibliography.bib
└── zenodo.json
```

## Citation

The citable record uses the Zenodo concept DOI:

<https://doi.org/10.5281/zenodo.19635395>

## License

CC BY 4.0.
