---
id: eip0i0tfv6a26roi0g03rq0
title: '133312'
desc: ''
updated: 1649362584129
created: 1649352796990
---

# Discrete Mathematics

## Proposition

A proposition is a declarative statement that can either be true or false, but not both. An example of a proposition would be something like "Albany is the Capital of NY".

## Conjunction

Let $p$ and $q$ be a proposition. The conjunction of $p$ and $q$ is the proposition $p \land q$. It's synonymous to the _and_ conditional in programming. 


Conjunction statements are true when both $p$ and $q$ is true. It is false otherwise.

It's symbol is $\land$.

## Disjunction

Let $p$ and $q$ be a proposition. The disjunction of $p$ and $q$ is the proposition $p \lor q$. It's synonymous with the inclusive __or__ conditional that is used in programming.

Disjunction statements are true when either $p$ or $q$ are true. It's false if both $p$ and $q$ are false. In this way it can be noted that a disjunction has the opposite features of a conjunction.

It's symbol is $\lor$.

## Exclusive Or

An _exclusive or_ operator works as a disjunction, except it is true only one of $p$ or $q$ have a true value. If they both have the same value, then the proposition is false.

The symbol for an exclusive or is $\oplus$. An example is $p⊕ q$.

## Negation

Let $p$ be a proposition. A negation is __not__ _p_ (with symbols it's $\lnot p$). Indicates that if a statement is true, the negation of the statement is false.

It's symbol is $\lnot$

## Conditional Statement

The conditional statement is the proposition "if $p$, then $q$". It's also known as an **implication**. It's important to note that even if $p$ is false, the proposition can still be true since p only _implies_ the statement $q$. Only when $q$ is false while $p$ is true can a conditional statement be false.

$p$ is known as a _hypothesis_  (or _antecedent_ or _premise_) and $q$ is called the _conclusion_ (or _consequence_).

It's synonymous with the _"if then"_ structures in programming.

It's symbol is $\implies$. An example of the notation being used is $p\implies q$.

## What is the Converse of $p\implies q$?

$q\implies p$

## What is the contrapositive of $p\implies q$?

$\lnot q\implies \lnot p$

## What is the inverse of $p\implies q$?

$\lnot p\implies \lnot q$

## Which of the converse, contrapositive and inverse are equivalent to the initial conditional statement?

The **contrapositive**


## Biconditionals

A biconditional statement is the proposition "$p$ if and only if $q$". $p$ and $q$ must have the same values for a biconditional statement to be true. Also know as **bi-implications*.

The symbol for biconditional is $\iff$. An example would be $p \iff q$.

**Note**: a the biconditional $p \iff q$ has the exact same truth value as $(p\implies q)\land (q\implies p)$. This naturally makes sense. As a sentence, this would become "p is true if q is true and q is true if p is true". When simplified it would become "p is true if and only if q is true".


## Connectives

Logical operators that are used to form new propositions from two or more existing propositions.

## List of Connectives

- Conjunctions
- Disjunctions
- Exclusive or
- Conditionals
- Biconditionals

### Example of a Truth Table

| $p$ | $q$ | $¬q$ | $p ∨ ¬q$ | $p ∧ q$ | $(p ∨ ¬q) → (p ∧ q)$ |
| :-: | :-: | :--: | :------: | :-----: | :------------------: |
|  T  |  T  |  F   |    T     |    T    |          T           |
|  T  |  F  |  T   |    T     |    F    |          F           |
|  F  |  T  |  F   |    F     |    F    |          T           |
|  F  |  F  |  T   |    T     |    F    |          F           |
