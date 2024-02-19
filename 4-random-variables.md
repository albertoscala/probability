# Random Variables

## Table of Contents

- [Random Variables](#random-variables)
  - [Table of Contents](#table-of-contents)
  - [Random Variables](#random-variables-1)
      - [Example](#example)
  - [Discrete Random Variables](#discrete-random-variables)
    - [Discrete Density Function](#discrete-density-function)
    - [Discrete Distribution Function](#discrete-distribution-function)
  
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
\begin{cases}
    0 \quad a < 1 \\
    \frac{1}{4} \quad 1 \leq a < 2 \\
    \frac{3}{4} \quad 2 \leq a < 3 \\
    \frac{7}{8} \quad 3 \leq a < 4 \\
    1 \quad 4 \leq a
\end{cases}
$$