# Introduction

## Types in CS
- Many approaches to *formal methods* for helping ensure that a system behaves correctly e.g. modal logics, denotational semantics, or *lightweight formal methods* like *model checkers* and *run-time monitoring*.  But the most popular and best established are *type systems*.
> A type system is a tractable syntactic method for proving the absence of certain program behaviors by classifying phrases according to the kinds of values they compute
- Focus of this book is the practical use of type systems to programming languages.  More abstract focus concerns connections to logic and *Curry-Howard correspondences*.
- Bad behaviors that can be eliminated by type systems are often called *run-time type errors* and include checking if the operands for an operator are valid and enforcing modularity properties such as protecting user-defined abstractions.
## What Type Systems are Good For
- Detecting Errors
- Abstraction
- Documentation
- Language Safety
- Efficiency
## Type Systems and Language Design
- It's hard to retrofit a language with a type system.  Ideally, the design of the language and the type system must go hand-in-hand.
## Capsule History
- Highlights key points in logic, programming language, and type theory history
- 
