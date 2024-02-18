# Probability Axioms

## Table of Contents

- [Probability Axioms](#probability-axioms)
  - [Table of Contents](#table-of-contents)
  - [Sample space](#sample-space)
      - [Examples](#examples)
  - [Events](#events)
      - [Examples](#examples-1)
  - [Operations with events](#operations-with-events)
    - [Union](#union)
      - [Union properties](#union-properties)
        - [Commutative](#commutative)
        - [Associative](#associative)
        - [Distributive](#distributive)
    - [Intersection](#intersection)
    - [Complement](#complement)
  - [Probability Axioms](#probability-axioms-1)
    - [Axiom 1](#axiom-1)
    - [Axiom 2](#axiom-2)
    - [Axiom 3](#axiom-3)
  - [Some simple properties of probability](#some-simple-properties-of-probability)

## Sample space 

The set of all possible outcomes of an experiment is called the sample space and is denoted by $S$ or $\Omega$.

#### Examples

If the outcome of an experiment is to determine the sex of an infant, then:

$$S = \lbrace m, f\rbrace$$

where the outcome f will indicate that the infant is female and m that it is male.

---

If the experiment consists of successively tossing two coins, then the sample space is formed by the following four points:

$$S = \lbrace(T,T),(T,C),(C,T),(C,C)\rbrace$$

The outcome will be $(T,T)$ if both coins gave heads, $(T,C)$ if the first coin gave heads and the second tails, $(C,T)$ if the first coin gave tails and the second heads and $(C,C)$ if both gave tails.

---

If the experiment consists of throwing two dice, then the sample space consists of 36 elements

$$S = \lbrace(i,j):i,j = 1,2,3,4,5,6\rbrace$$

dove l’esito $(i,j)$ indica che il numero $i$ compare nel dado più a sinistra e $j$ nell’altro dado.

## Events

Each subset $E$ of the sample space is called an event. In other words an event is a collection of possible outcomes of an experiment.

#### Examples

On the first example, the event $E = \lbrace f\rbrace$ is the event that the infant is a girl.

---

On the second example, the event $E = \lbrace(T,T),(T,C)\rbrace$ is the event that the first coin gave heads.

---

On the third example, the event $E = \lbrace(i,j):i+j = 7\rbrace$ is the event that the sum of the numbers on the two dice is 7.

## Operations with events

### Union

Given two events $E$ and $F$, we can define the following operation $E \cup F$ as the event that either $E$ or $F$ occurs also known as the union/logical sum of $E$ and $F$.

#### Union properties

##### Commutative

$$E \cup F = F \cup E \qquad EF = FE$$

##### Associative

$$(E \cup F) \cup G = E \cup (F \cup G) \qquad (EF)G = E(FG)$$

##### Distributive

$$(E \cup F)G = EG \cup FG \qquad EF \cup G = (E \cup G)(F \cup G)$$

### Intersection

The operation $E \cap F$ is the event that both $E$ and $F$ occur also known as the intersection/logical product of $E$ and $F$.

### Complement

The operation $E^c$ is the event that $E$ does not occur also known as the complement of $E$. The complement of $E$ is the event that consists of all the outcomes in the sample space that are not in $E$.

## Probability Axioms

The probability of an event $E$, denoted by $P(E)$, is a number that satisfies the following axioms:

### Axiom 1

The probability of an event is a non-negative number. That is, respects the following condition.

$$ 0 \leq P(E) \leq 1$$

### Axiom 2

The probability of the sample space is 1.

$$P(S) = P(\Omega) = 1$$

### Axiom 3

For each sequence of mutually exclusive events $E_1, E_2, \ldots$ (i.e. $E_i \cap E_j = \emptyset$ for $i \neq j$), the probability of the union of these events is equal to the sum of the probabilities of the individual events.

$$P(\bigcup\limits_{i=1}^{\infty} E_{i}) = \sum_{i=1}^{\infty} P(E_{i})$$

---

We define $P(E)$ as the probability of the event $E$.

## Some simple properties of probability

Let's notice that $E$ and $E^c$ are always mutually exclusive and events. This means that $E \cap E^c = \emptyset$ and $E \cup E^c = S$. This implies that $P(E) + P(E^c) = P(S) = 1$.

So the first proposition says that the probability of the complement of an event is:

$$P(E^c) = 1 - P(E)$$

Moving on to the second probability property. It says that if $E$ and $F$ are two events, where $E \subset F$, then $P(E) \leq P(F)$.

$$If E \subset F\, then P(E) \leq P(F)$$