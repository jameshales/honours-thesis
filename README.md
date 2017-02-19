Refinement Quantifiers for Logics of Belief and Knowledge
=========================================================

[Download (PDF)](https://github.com/jameshales/honours-thesis/releases/tag/final)

This thesis was presented to the School of Computer Science and Software
Engineering for the degree of Bachelor of Computer and Mathematical Sciences
(First Class Honours) from the University of Western Australia in Decemer 2011.

Abstract
--------

Modal logics are extensions of propositional logic, with which one can qualify
the truth of statements with operators known as modalities. Epistemic logic is a
variant of modal logic, commonly known as the logic of knowledge. Modalities in
epistemic logic qualify statements by saying that a particular agent knows a
statement to be true. Thus epistemic logic can be used to reason about the
knowledge of a collection of agents. Doxastic logic is a similar logic, used to
reason about beliefs rather than knowledge.

Informative updates are events that provide agents in modal settings with
additional information. The effect of an informative update may be to give new
knowledge or beliefs to the agents in the system. Informative updates in an
epistemic setting can be modelled by the refinements of a Kripke model in modal
logic.

Refinement quantifiers are introduced to variants of modal logic to produce
refinement quantified modal logics. The refinement quantifiers are operators
that quantify over the refinements of a Kripke model, and as these refinements
model informative updates, this quantification can be said to be equivalent to
quantifying over the informative updates that are possible in a Kripke model.
Recent work by van Ditmarsch, French and Pinchinat~\cite{french2010future} has
presented an axiomatisation and decidability results for the single-agent
refinement quantified modal logic. We extend these results to apply to the
single-agent doxastic and epistemic logics, and to the multi-agent modal and
doxastic logics, by providing sound and complete axiomatisations, and
decidability and expressivity results for each of these logics.

Building
--------

Requirements:

- TeX Live 2015 or later
- LaTeXmk
- GNU Make

Simply run `make`.

License
-------

This thesis is distributed under the [Creative Commons Attribution Share Alike
4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.
