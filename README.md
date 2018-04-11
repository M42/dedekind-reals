# Positive reals in Agda

Standalone positive Dedekind reals in Agda, as a completion of the
dyadic rationals, using higher-inductive types (Dan Licata's trick) to
define propositional truncation.

This is work in progress and it is just meant as an exercise. It uses
`--type-in-type` (in a way that can break soundness) to avoid the type
of the real numbers residing in a higher universe; and many crucial proofs are
incomplete.  In any case, compiling `Reals.agda` creates
an executable that successfully computes digits of the binary
representation of `sqrt(2)`.
