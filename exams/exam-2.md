# Exam 2

## Exercise 1

An urn contains 9 balls, 3 blue and 6 red. Anton draws 2 balls without replacement. If the two balls are blue and red, then he will toss two fair coins, else he will launch two coins wiht both $\frac{2}{3}$ probability of heads and $\frac{1}{3}$ probability of tails. In both cases the launches are indipendent. Let define the following events:

- $B_1 = \lbrace \text{the two balls drawn are one blue and one red} \rbrace$
- $B_2 = \lbrace \text{the two balls drawn are not one blue and one red} \rbrace$
- $D_1 = \lbrace \text{the first ball drawn is blue} \rbrace$
- $D_2 = \lbrace \text{the second ball drawn is blue} \rbrace$
- $C_1 = \lbrace \text{the first coin tossed shows head} \rbrace$
- $C_2 = \lbrace \text{the second coin tossed shows head} \rbrace$

1. Check which of the following relations are true:
   1. $B_1 = D^{c}_1 \cap D_2$
   2. $B_1 = D^{c}_1 \cup D_2$
   3. $B_1 = (D_1 \cap D^{c}_2) \cup (D^{c}_1 \cap D_2)$
   4. $B_1 = (D_1 \cup D^{c}_2) \cap (D^{c}_1 \cup D_2)$
2. Determine $\mathbb{P}(B_1)$ and $\mathbb{P}(B_2)$.
3. Determine $\mathbb{P}(C_1|B_1)$ and $\mathbb{P}(C_2|B_1)$.
4. Determine $\mathbb{P}(C_1)$ and $\mathbb{P}(C_2)$.
5. Check if the events $C_1$ and $C_2$ are independent with a proof.
6. Let $X$ the random variable that is 1 if the first coin shows head and 2 otherwise. Determine the expectation of $X$.

## Exercise 2

A shop keeper buys 10 boxes of milk to resell them. The boxes are enumerated with integer values from 1 to 10. The milk spoils after a time (expressed in days) that is matched to an exponential distribution with parameter $\lambda = \frac{1}{15}$. The time of spoilage of each box is independent from the others. Let dfine the random variables $X, T_i$ as follows:

- $T_i$ is the time of spoilage of the box $i$, where $i \in \lbrace 1, ..., 10 \rbrace$,
- $X$ is the total number of boxes that spoil after 10 days.

1. Determine $\mathbb{P}(T_i < 10)$,
2. Determine $\mathbb{P}(X \geq 2)$,
3. Determine $\mathbb{E}(X)$.

## Exercise 3

A generous millionaire has a large $n$ of friends that require a 10.000 euros loan, with the promise to return the money at the end of the year. The millionaire estimates that every friend will return the money with probability $p = 0.7$ and that the sum won't be returned with probability $1 - p = 0.7$, independently from the other friends. Let $S_n$ the random variable that represents the sum of the money that the millionaire will receive at the end of the year, and let $Z_i$ the sum of the money that the millionaire will receive from the friend $i$, where $i \in \lbrace 1, ..., n \rbrace$, at the end of the year.

1. Determine the set of values that the random variable $Z_i$ can assume, its discrete density function and its mean $\mu = \mathbb{E}(Z_i)$, for each $i = 1,...,n$.
2. Express the random variable $S_n$ as a function of the random variables $Z_1, Z_2, ..., Z_n$.
3. Determine $\lim_{n \to \infty}\mathbb{P}(S_n < 6500n)$ applying the Law of Large Numbers, specifying the value of $\epsilon$ with which it was applied.
