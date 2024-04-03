# Exam 3

## Exercise 1

An urn contains 6 balls, 2 blue, 2 red and 2 green. Anton draws 2 balls with reinserting. If none of the balls drawn is blue then Anton will toss 2 times a fair coin, else he will toss two times a coin with probability $\frac{2}{3}$ of heads and probability $\frac{1}{3}$ of tails. In both cases the tosses are independent. Let define for $i \in \lbrace 1, 2 \rbrace$ the following events:

- $B_i = \lbrace \text{the i-th ball drawn is blue} \rbrace$,
- $G_i = \lbrace \text{the i-th ball drawn is green} \rbrace$,
- $R_i = \lbrace \text{the i-th ball drawn is red} \rbrace$,
- $D = \lbrace \text{none of the balls drawn is blue} \rbrace$,
- $C_1 = \lbrace \text{the first coin tossed shows head} \rbrace$,

1. Check which of the following relations are true:
   1. $D = B^{c}_1 \cup B^{c}_2$,
   2. $D = B^{c}_1 \cap B^{c}_2$,
   3. $D = (V_1 \cup V_2) \cup (R_1 \cup R_2)$,
   4. $D = (V_1 \cap V_2) \cap (R_1 \cap R_2)$,
   5. $D = (V_1 \cup R_1) \cap (V_2 \cup R_2)$.
2. Determine $\mathbb{P}(D)$ and $\mathbb{P}(D^c)$,
3. Determine $\mathbb{P}(C_i|D)$ and $\mathbb{P}(C_i|D^c)$ for each $i \in \lbrace 1, 2 \rbrace$,
4. Determine $\mathbb{P}(C_i)$ for each $i \in \lbrace 1, 2 \rbrace$,
5. Check if the events $C_1$ and $C_2$ are independent presenting the necessary calculations,
6. Let $X$ be a random variable that assume the value 1 if at elast one of the balls drawn is blue and -1 otherwise. Determine the expectancy $\mathbb{E}(X)$ and the variance $Var(3X)$.

## Exercise 2

In a shop there are 100 boxes of light bulbs for sale, each box contains 10 bulbs, in which 3 are defective and 7 are not. Indipedently for each box the shopkeeper chooses 3 random bulbs: the 3 bulbs selected are all dinstincts and each tern of bulbs is equally likely to be chosen. If at least one of those bulbs is defective the box is considered defective and removed from the shelf, otherwise it is considered non-defective and kept on the shelf.

- Let define the event $C_i = \lbrace \text{the i-th box is removed from the shelf} \rbrace$ for each $i \in \lbrace 1, ..., 100 \rbrace$,
- Let define the random variable $X$, that represents the number of boxes removed from the shelf.

1. Determine $\mathbb{P}(C_1)$,
2. Determine $\mathbb{P}(C_1 \cap C^{c}_2)$,
3. Specify what type of distribution is $X$ and determine $\mathbb{P}(X > 0)$,
4. Determine $\mathbb{E}(X)$.

## Exercise 3

Two team A and B play against each other infinite times. Every match ends with a win of one of the two teams or with a draw, the results are indipendent. The probability that team A wins is $\frac{1}{4}$, the probability that team B wins is $\frac{1}{2}$.

- Let $X$ be the random variable that represents the number of mathces played until the first win of the team A,
- Let $Z_i$ be a random variable that values 1 if the i-th match that ends with a tie and 0 otherwise.
- Let $S_n$ the number of ties between the $n \in \mathbb{N}$ matches played.

1. Specify what type of random variable is $X$ and determine its discrete density,
2. Determine the discrete density of $Z_i$ and its expected value, $\mathbb{E}(Z_i)$,
3. Specify the relationship between the random variable $S_n$ and the random variables $Z_1, Z_2, Z_3, ...$,
4. Determine $\lim_{n \to \infty}\mathbb{P}(S_n \geq \frac{1}{8}n)$ applying the law of large numbers, specifying the value of the variable $\epsilon$ with which it was applied.
