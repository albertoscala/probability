# Combination Math

## The principle foundamental of combination math

Let two experiments be performed. Suppose that the first experiment has $m$ possible outcomes, that for each of these the second experiment has $n$ possible outcomes. Then, if distinct sequences of outcomes of the two experiments produce distinct final outcomes, the two experiments have $mn$ possible outcomes in all.

### Example

A small community consists of 10 women, each of whom has three children. You want to elect one of these mothers and her child as mother and child of the year; how many choices are there?

**Solution**

One can see the mother's choice as the outcome of the first experiment and the subsequent choice of one of her children as the outcome of the second experiment; by the fundamental principle there are $10 * 3 = 30$ possible choices.

## Permutations

A permutation of a set of distinct objects is an arrangement of these objects in a definite order. The number of permutations of $n$ distinct objects is $n! = n(n-1)(n-2)...(3)(2)(1)$.

### Example

In how many ways can 9 people be arranged in a single file?

**Solution**

The first person can be any of the 9, the second any of the remaining 8, and so on. By the fundamental principle, there are $9! = 362880$ possible arrangements.

## Combinations

A combination of $n$ distinct objects taken $r$ at a time is an unordered selection of $r$ objects from the set of $n$ objects.

### Example

For example, how many 3-letter sets can be formed with the 5 letters A, B, C, D and E?

**Solution**

The first letter can be any of the 5, the second any of the remaining 4, and the third any of the remaining 3. By the fundamental principle, there are $5 * 4 * 3 = 60$ possible 3-letter sets.

But in this case we are counting each set 6 times, since each set can be arranged in 3! = 6 different ways. So the number of 3-letter sets is $\frac{5 * 4 * 3}{3!} = 10$.

### Binomial Coefficients

The number of combinations of $n$ distinct objects taken $r$ at a time is denoted by $C(n, r)$ and is given by the formula:

$$C(n, r) = \frac{n!}{r!(n-r)!}$$

### Example

You want to form a committee of 3 people chosen from 20 people. How many committees are possible?

**Solution**

By the fundamental principle, there are $C(20, 3) = \frac{20!}{3!(20-3)!} = 1140$ possible committees.

Alternatively, we can use the fact that $C(n, r)$ is the same as saying $\frac{20 * 19 * 18}{3 * 2 * 1}$ that brings us to the same result of 1140.

## Multinoimial Coefficients

The number of ways of dividing $n$ distinct objects into $r$ distinct groups of sizes $n_1, n_2, ..., n_r$ is given by the multinomial coefficient:




