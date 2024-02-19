# Conditional Probability and Independence

## Table of Contents

- [Conditional Probability and Independence](#conditional-probability-and-independence)
  - [Table of Contents](#table-of-contents)
  - [Conditional Probability](#conditional-probability)
      - [Example](#example)
  - [Product Rule](#product-rule)
  - [Total Probability Formula](#total-probability-formula)
      - [Example](#example-1)
  - [Bayes Formula](#bayes-formula)
  - [Odd Ratio](#odd-ratio)
      - [Example](#example-2)
  - [Indipendent Events](#indipendent-events)

## Conditional Probability

Let's suppose we have 2 dice and all the 36 possible outcomes are equally likely. We know that the first dice is a 3. What's the possibility that the sum of the two dice is 8?

The probability of getting a 3 on the first dice is $\frac{1}{6}$ and the possible are:

$$\lbrace(3,1),(3,2),(3,3),(3,4),(3,5),(3,6)\rbrace$$

Then the possible outcomes that give us a sum of 8 are:

$$\lbrace(3,5)\rbrace$$

So the probability is $\frac{1}{6}$.

Let's mark the with $E$ and $F$ the events of getting a 3 on the first dice and the sum of the two dice being 8, respectively. The conditional probability of $E$ given $F$ is:

$$P(E|F)$$

The generic formula for conditional probability is given by the frequency definition of the positive outcomes of $F$ under the condition of $E$ that happens only if $EF$ happens.

$$P(E|F) = \frac{P(EF)}{P(F)} = \frac{P(E \cap F)}{P(F)}$$

#### Example

Mark is 80% convinced that the house keys he has lost are in one of the two pockets of the jacket hanging on the coat hanger, and 40% convinced that they are in the right pocket and 40% convinced that they are in the left pocket. If, after rummaging in the left pocket, Mark does not find the keys there, what is the conditional probability that they are in the other pocket?

**Solution**

Let's mark the events as follows:

- $R$: The keys are in the right pocket;
- $L$: The keys are in the left pocket.

We are looking for the probability of $P(D|S^c)$ that we obtain by the following method:

$$P(D|S^c) = \frac{P(D \cap S^c)}{P(S^c)} = \frac{P(D)}{1 - P(S)} = \frac{2}{3}$$

## Product Rule

The product rule is a consequence of the definition of conditional probability that gives us a way to express the joint probability of two events in terms of the conditional probability of one event given the other.

The product rule is given by:

If $P(E_1 ... E_{n-1}) > 0$, then:

$$P(E_1,E_2,E_3 ... E_n) = P(E_1)P(E_2|E_1) ... P(E_n|E_1 ... E_{n-1})$$

[Proof](proof)

## Total Probability Formula

Given two events $E$ and $F$ with $0 < P(F) < 1$. We can write $E$ as:

$$E = (EF) \cup (EF^c)$$

If an elementary event is in $E$, then it is in $EF$ or $EF^c$. So we can write:

$$P(E) = P(EF) + P(EF^c)$$

$$P(E) = P(E|F)P(F) + P(E|F^c)P(F^c)$$

$$P(E) = P(E|F)P(F) + P(E|F^c)[1 - P(F)]$$

#### Example

An insurance company divides people into two classes: those who are accident prone and those who are not. Insurance statistics show that people who are accident prone have a 0.4 probability of having an accident in a year, while this probability drops to 0.2 for other people. Assuming that 30% of the population is accident prone, what is the probability that a new policyholder will have an accident within one year of purchasing the policy?

**Solution**

We obtain the probability by conditioning first on whether the customer considered is accident prone or not. Let A1 be the event "the insured has an accident within one year of purchasing the policy" and let A be the event "the insured is accident prone". The probability $P(A_1)$ sought then holds:

$$P(A_1) = P(A_1|A)P(A) + P(A_1|A^c)P(A^c) = 0.4 \times 0.3 + 0.2 \times 0.7 = 0.26$$

## Bayes Formula

The Bayes Formula is a consequence of the Total Probability Formula and the Product Rule. It gives us a way to express the conditional probability of one event given another in terms of the conditional probability of the other event given the first.

The Bayes Formula is given by:

$$P(F|E) = \frac{P(E|F)P(F)}{P(E)}$$

[Proof](proof)

## Odd Ratio

The modified probability of an event when we introduce a new proof can be compactly represented in function of the *"Odd Ratio"* of the hypotesis. 

The Odd Ratio of an event $E$ are given by:

$$\frac{P(E)}{P(E^c)} = \frac{P(E)}{1 - P(E)}$$

In other terms, the Odd Ratio expresses how much more probable that the event E occurs related to the fact that the event won't occur.

#### Example

If we say that $P(E) = \frac{2}{3}$, then $P(A) = 2P(A^c)$.
The Odd Ratio of $E$ is equal to 2.

If we say that the Odd Ratio is equal to $\alpha$, you commonly say that the possibilities are "$\alpha$ to 1" in favour to the hypotesis.

## Indipendent Events