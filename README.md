# Positive reals in Agda

Standalone positive Dedekind reals in Agda, as a completion of the
dyadic rationals, using higher-inductive types (Dan Licata's trick) to
define propositional truncation.

This is work in progress and it is just meant as an exercise. I do not
plan to work on this for a while. We use `--type-in-type` (in a way
that could break soundness) to avoid the type of the real numbers
residing in a higher universe; and many proofs are incomplete.  We
postulate an identity between equivalent propositions and at the same
time we also accept uniqueness of identity proofs (not using `--without-K`).  In any case,
compiling `Reals.agda` creates an executable that successfully
computes the first digits of the binary representation of `sqrt(2)`.

### Links

You may be interested in

 * this formalization of the [Dedekind reals](https://github.com/andrejbauer/dedekind-reals) in Coq,
   by Andrej Bauer and others.




