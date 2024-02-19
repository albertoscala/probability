# Random Variables

## Table of Contents

- [Random Variables](#random-variables)
  - [Table of Contents](#table-of-contents)
  - [Random Variables](#random-variables-1)
      - [Example](#example)
  
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

$$1 = P(\Cup_{i=0}^{3}\lbrace Y = i \rbrace ) = \sum_{i=0}^{3} P\lbrace Y = i \rbrace$$