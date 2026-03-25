System Definition

An SMIA system is defined by the tuple:

M – Meaning Space
A structured, canonical semantic representation of decision-relevant context.

R – Rule Set
Declarative, versioned, and prioritized normative rules.

A – Action Space
The explicitly modeled set of all possible executable actions.

C(R, M) – Constraint Function
A deterministic function restricting actions based on rules and meaning.

D – Decision Space
The governed closure of the action space under constraints.

Formally:

D = {a ∈ A | a ⊨ C(R, M)}