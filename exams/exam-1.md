# Exam 1

## Exercise 1

An urn contains 12 balls, 3 blue balls and 9 red balls. Anton draws 2 balls from the urn without replacement. If the two balls are both blue he launches three dice, otherwise he launches two dice.
Define the following events:

- $B_1 = \lbrace \text{two blue balls are drawn} \rbrace$
- $B_2 = \lbrace \text{two blue balls are not drawn} \rbrace$
- $C = \lbrace \text{the sum of the two dice is equal to two} \rbrace$
- $D_1 = \lbrace \text{the first ball drawn is blue} \rbrace$
- $D_2 = \lbrace \text{the second ball drawn is blue} \rbrace$

1. Put in relation the event $B_1$ adn the couple of events $D_1$ and $D_2$.
2. Determine $\mathbb{P}(B_1)$ and $\mathbb{P}(B_2)$.
3. Determine $\mathbb{P}(C|B_1)$ and $\mathbb{P}(C|B_2)$.
4. Determine $\mathbb{P}(C)$ and $\mathbb{P}(B_1|C)$.
5. Be X the number of dice launched. Determine the set of values that the random variable X can assume, it's discrete density function and the expected value of X, $\mathbb{E}(X)$, and the expected value of $X^2$, $\mathbb{E}(X^2)$.

## Exercise 2

Consider a random walk $S_0, S_1, S_2, S_3, ...$, where $S_0 = 0$ for each $n \in \mathbb{N} \space S_n = \sum^{n}_{i=1} Z_i$, where the increments $Z_1, Z_2, ...$ are independent and identically distributed random variables with discrete density $p(1) = \frac{1}{2}, p(2) = \frac{1}{4}, p(-2) = \frac{1}{4}$.

1. Utilize the Central Limit Theorem to approximate the probability $\mathbb{P}(S_n \in [\frac{n}{2} + a\sqrt{n}, \frac{n}{2} + b\sqrt{n}])$ for the values of $n$ sufficiently large and for $a < b$.
2. Determine the numeric value of the previous probability for $a = -\frac{3}{2}, b = \frac{3}{2}$ using the Gaussian table.

## Exercise 3

In one library there are 10 enumerated shelves with integer values frp, 1 to 10. A messy student has $n$ books and inserts each book in a randomly picked shelf, with the same probability each shelf can contain any number of books. The choice of the shelf is independent for each book. Define the events $E^{i}_{k}$ and the random variables $Z_i$ and $X$ for $i \in \lbrace 1, 2, ..., 10 \rbrace$ and $k \in \lbrace 1, ..., n \rbrace$ as it follows:

- $E^{i}_{k} = \lbrace \text{the book} k \text{is \it{not} inserted in the shelf} i \rbrace$,
- $X$ is the random variable that represents the number of shelves that contain at least one of the $n$ books,
- $Z_i$ is the random variable that is 1 if in the shelf $i$ is inserted at least one of the $n$ books, 0 otherwise.

Let $X$ ne the random variable that represents the number of shelves that contain at least one of the $n$ books, be

1. Determine the probability $\mathbb{P}(E^{1}_{1} \cap E^{1}_{2} \cap E^{1}_{3} \cap ... \cap E^{1}_{n})$.
2. Express the random variable $X$ as a function of the random variables $Z_1, Z_2, ..., Z_{10}$.
3. Determine $\mathbb{E}(X)$.
