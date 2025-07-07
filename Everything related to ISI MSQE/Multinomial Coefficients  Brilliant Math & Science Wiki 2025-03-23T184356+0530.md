---
title: "Multinomial Coefficients | Brilliant Math & Science Wiki"
source: "https://brilliant.org/wiki/multinomial-coefficients/"
author:
published:
created: 2025-03-23
description: "Multinomial coefficients are generalizations of binomial coefficients, with a similar combinatorial interpretation. They are the coefficients of terms in the expansion of a power of a multinomial, in the multinomial theorem. The multinomial coefficient, like the binomial coefficient, has several combinatorial interpretations. This example has a different solution using the multinomial theorem; see that wiki for details. The multinomial coefficients are the coefficients of the terms in the expansion of ..."
tags:
  - "clippings"
---
 
https://brilliant.org/wiki/multinomial-coefficients/
Multinomial coefficients are generalizations of [binomial coefficients](https://brilliant.org/wiki/properties-of-binomial-coefficients/ "binomial coefficients"), with a similar combinatorial interpretation. They are the coefficients of terms in the expansion of a power of a multinomial, in the [multinomial theorem](https://brilliant.org/wiki/multinomial-theorem/ "multinomial theorem").

The multinomial coefficient, like the binomial coefficient, has several combinatorial interpretations.

> Let $b_1,\ldots, b_k$ be nonnegative integers, and let $n = b_1+b_2+\cdots+b_k$. The multinomial coefficient $\binom{n}{b_1,b_2,\ldots,b_k}$ is:
> 
> (1) the number of ways to put $n$ interchangeable objects into $k$ boxes, so that box $i$ has $b_i$ objects in it, for $1\le i \le k$.
> 
> (2) the number of ways to choose $b_1$ interchangeable objects from $n$ objects, then to choose $b_2$ from what remains, then to choose $b_3$ from what remains,..., then to choose $b_{k-1}$ from what remains.
> 
> (3) the number of unique permutations of a word with $n$ letters and $k$ distinct letters, such that the $i$ th letter occurs $b_i$ times.
> 
> (4) the product 
> $$
> \binom{n}{b_1}\binom{n-b_1}{b_2}\binom{n-b_1-b_2}{b_3}\cdots\binom{b_{k-1}+b_k}{b_{k-1}}\binom{b_k}{b_k}.
> $$
> 
> (5) the quotient 
> $$
> \frac{n!}{b_1!b_2!\cdots b_k!}.
> $$

> (1) and (2) are clearly equivalent, and (2) and (4) are equivalent from the definition of the binomial coefficient. (4) and (5) are equivalent by simple algebra. There are a few ways to see that (3) is equivalent to the others. Arguing combinatorially, note that a permutation of a word as in (3) corresponds to choices of spots to put each of the repeated letters in; out of the spots $1, \ldots, n$, choose $b_1$ of those spots to put the first letter in, then $b_2$ spots out of the remaining $n-b_1$ to put the second letter in, and so on. So (3) is equivalent to (2).
> 
> (One can also count permutations directly, by taking $n!$ permutations and dividing by factors that account for duplicates: divide by a factor of $b_1!$ to account for the fact that permuting all of the first letters doesn't change the permutation, divide by $b_2!$ to do the same for the second letters, and so on, which gives the formula from (5).)

> How many unique permutations of the word ABRACADABRA are there?
> 
> ---
> 
> **Solution:** Using definition (3), this is the multinomial coefficient $\binom{11}{5,2,1,1,2} = 83{,}160.$

> For a fixed $n$ and $k$ , what is the sum of all the multinomial coefficients $\binom{n}{b_1,b_2,\ldots,b_k}$?
> 
> ---
> 
> Using definition (1), this is the number of ways to put $n$ objects into $k$ boxes (each specific multinomial coefficient gives a different breakdown of how many objects are in each box). Each object has $k$ choices for its destination, so the total number is $k \cdot k \cdot k \cdots \cdot k = k^n$ .

This example has a different solution using the [multinomial theorem](https://brilliant.org/wiki/multinomial-theorem/ "multinomial theorem"); see that wiki for details.

The multinomial coefficients are the coefficients of the terms in the expansion of $(x_1+x_2+\cdots+x_k)^n$; in particular, the coefficient of $x_1^{b_1} x_2^{b_2} \cdots x_k^{b_k}$ is $\binom{n}{b_1,b_2,\ldots,b_k}$. This is the [multinomial theorem](https://brilliant.org/wiki/multinomial-theorem/ "multinomial theorem").

**Cite as:** Multinomial Coefficients. *Brilliant.org*. Retrieved 18:39, March 23, 2025, from [https://brilliant.org/wiki/multinomial-coefficients/](https://brilliant.org/wiki/multinomial-coefficients/)