# Random Variables

## Table of Contents

- [Random Variables](#random-variables)
  - [Table of Contents](#table-of-contents)
  - [Random Variables](#random-variables-1)
      - [Example](#example)
  - [Discrete Random Variables](#discrete-random-variables)
    - [Discrete Density Function](#discrete-density-function)
    - [Discrete Distribution Function](#discrete-distribution-function)
  - [Expected Value](#expected-value)
  
## Random Variables
 
When we are studying a random experiment, we are interested in a peculiarity of the outcomes. For example when we launch two dice, we are interested in sum of the number that comes out rather than the values.

These quantities, or better called real-valued functions defined on the sample space, are called **random variables**. 

#### Example

Suppose our experiment consists of tossing 3 balanced coins. If we denote by Y the number of heads we obtain, then Y is a random variable taking the values 0,1,2,3 with the following probabilities:

$$P(Y=0) = P(\lbrace(C,C,C)\rbrace) = \frac{1}{8}$$

$$P(Y=1) = P(\lbrace(C,C,T),(C,T,C),(T,C,C)\rbrace) = \frac{3}{8}$$

$$P(Y=2) = P(\lbrace(C,T,T),(T,C,T),(T,T,C)\rbrace) = \frac{3}{8}$$

$$P(Y=3) = P(\lbrace(T,T,T)\rbrace) = \frac{1}{8}$$

Since Y has to take one of the values 0,1,2,3, we have:

$$1 = P(\bigcup_{i=0}^{3}\lbrace Y = i \rbrace ) = \sum_{i=0}^{3} P\lbrace Y = i \rbrace$$

## Discrete Random Variables

A random variable that can take on an infinite number of values is called discrete. For a discrete random variable, the descrete probability function $p(a)$ of $X$ is defined as:

$$p(a) = P\lbrace X = a \rbrace$$

### Discrete Density Function

The discrete density $p(a)$ is positive for no more than a numerable infinity of values of $a$. Thus, if $X$ assumes the values $x_1,x_2,...$, then

$$p(x_i) \geq 0 \qquad i = 1,2,...$$

$$p(x) = 0 \qquad otherwise$$

Since $X$ must assume at least one of the values $x_i$, we have that:

$$\sum_{i=1}^{\infty} p(x_i) = 1$$

Could be useful to rappresent the probability function of a discrete random variable in a table. For example:

| $x_i$ | $p(x_i)$ |
|-------|----------|
| 0     | $\frac{1}{4}$      |
| 1     | $\frac{1}{2}$      |
| 2     | $\frac{1}{4}$      |

### Discrete Distribution Function

The discrete distribution function $F$ can be expressed in function of $p(a)$ as follows:

$$F(a) = \sum_{x \leq a} p(x)$$

For example, if $X$ has the discrete density given by:

$$p(1) = \frac{1}{4} \quad p(2) = \frac{1}{2} \quad p(3) = \frac{1}{8} \quad p(4) = \frac{1}{8}$$

Then the distribution function is:

$$
F(a) =
\begin{cases}
    0 \qquad a < 1 \\
    \frac{1}{4} \qquad 1 \leq a < 2 \\
    \frac{3}{4} \qquad 2 \leq a < 3 \\
    \frac{7}{8} \qquad 3 \leq a < 4 \\
    1 \qquad 4 \leq a
\end{cases}
$$

Note that the steps of the distribution function are equal to the values of the probability function.

## Expected Value

One of the most important concept of the probability theory is the expected value of a random variable. If $X$ is a random variable with discrete density $p(x)$, then the expected value of $X$, written as $E[X]$, is defined as:

$$E[X] = \sum_{x:p(x)>0} x \cdot p(x)$$

The expected value of $X$ is the weighted average of the values that $X$ can assume, weighted with the probability that $X$ will assume it.

For example, if the density of $X$ is given by:

$$p(0) = \frac{1}{2} = p(1)$$

Then:

$$E[X] = 0 \cdot \frac{1}{2} + 1 \cdot \frac{1}{2} = \frac{1}{2}$$

Now let's consider a random variable $X$ with that assumes the values $x_1,x_2,...$ with probabilities $p(x_1),p(x_2),...$ and let's think that $X$ represents the earnings in a single game. This means that, with probability $p(x_i)$, we will win $x_i$ money unity, $i_1,i_2,...$.
The expected earnings in a single game will be represented in the following way:

$$\sum_{i=1}^{n} x_i \cdot p(x_i) = E[X]$$

#### Example

Calculate $E[X]$ when X represents the outcome of the roll of a balanced die.

**Solution**

Being $p(1)=p(2)=p(3)=p(4)=p(5)=p(6)=\frac{1}{6}$ we have:

$$E[X] = 1 \cdot \frac{1}{6} + 2 \cdot \frac{1}{6} + 3 \cdot \frac{1}{6} + 4 \cdot \frac{1}{6} + 5 \cdot \frac{1}{6} + 6 \cdot \frac{1}{6} = \frac{21}{6} = \frac{7}{2} = 3.5$$

## Expected Value of a Function of a Random Variable

Imagine we have a discrete random variable $X$ with it's descrete density and we want to calculate the expected value of some function of $X$, for example $g(X)$. How can we do that? 

1. We determine the discrete density of $g(X)$ given the discrete density of $X$.
2. We calculate the expected value of $g(X)$ using the discrete density of $g(X)$.

#### Example

Given $X$ a random variable that assumes the values $-1,0,1$ with probabilities:

$$P\lbrace X = -1 \rbrace = 0.2 \quad P\lbrace X = 0 \rbrace = 0.5 \quad P\lbrace X = 1 \rbrace = 0.3$$

Calculate $E[X^2]$.

**Solution**

Let $Y = X^2$. Then the values of $Y$ is given by:

$$P\lbrace Y = 1 \rbrace = P\lbrace X = -1 \rbrace + P\lbrace X = 1 \rbrace = 0.5$$

$$P\lbrace Y = 0 \rbrace = P\lbrace X = 0 \rbrace = 0.5$$

Then:

$$E[X^2] = E[Y] = 1(0.5) + 0(0.5) = 0.5$$

Note that:

$$0.5 = E[X^2] \neq (E[X])^2 = 0.01$$