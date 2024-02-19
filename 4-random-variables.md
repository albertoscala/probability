# Random Variables

## Table of Contents

- [Random Variables](#random-variables)
  - [Table of Contents](#table-of-contents)
  - [Random Variables](#random-variables-1)
      - [Example](#example)
  - [Discrete Random Variables](#discrete-random-variables)
  
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

The discrete density $p(a)$ is positive for no more than a numerable infinity of values of $a$. Thus, if $X$ assumes the values $x_1,x_2,...$, then

$$p(x_i) \geq 0 \qquad i = 1,2,...$$

$$p(x) = 0 \qquad otherwise$$

Since $X$ must assume at least one of the values $x_i$, we have that:

$$\sum_{i=1}^{\infty} p(x_i) = 1$$

Could be useful to rappresent the probability function of a discrete random variable in a table. For example:

<center>

| $x_i$ | $p(x_i)$ |
|-------|----------|
| 0     | $\frac{1}{4}$      |
| 1     | $\frac{1}{2}$      |
| 2     | $\frac{1}{4}$      |

</center>