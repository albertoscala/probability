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
