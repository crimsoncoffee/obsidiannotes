---
title: "Modular Exponentiation and Fermat's Theorem - Grok"
source: "https://grok.com/chat/3b155b1e-49d6-4cfa-acf4-08da173c88d6?referrer=website"
author:
published:
created: 2025-04-07
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
Refer to the following content:image.png

To determine the remainder when $3^{37}$ is divided by 79, we need to compute $3^{37} \mod 79$ . The number 79 is prime, and 3 is not divisible by 79, suggesting that number theory tools like Fermat's Little Theorem or modular exponentiation might simplify the calculation. The answer options are (A) 78, (B) 1, (C) 2, and (D) 35.

### Using Fermat's Little Theorem

Since 79 is a prime and 3 is coprime with 79, Fermat's Little Theorem states that:

$$
3^{79-1} \equiv 3^{78} \equiv 1 \mod 79
$$

This tells us that raising 3 to the power of 78 yields a remainder of 1 when divided by 79. However, we need $3^{37}$ , and 37 is less than 78, so we cannot directly reduce the exponent using this property alone. Instead, we can explore efficient computation methods or patterns to find $3^{37} \mod 79$ .

### Binary Exponentiation Method

Computing $3^{37} \mod 79$ directly by multiplying 3 by itself 37 times is impractical due to the large numbers involved. A more efficient approach is binary exponentiation, which uses the binary representation of the exponent to reduce the number of multiplications. First, express 37 in binary:

$$
37 = 32 + 4 + 1 = 2^5 + 2^2 + 2^0
$$

Thus:

$$
3^{37} = 3^{32 + 4 + 1} = 3^{32} \cdot 3^4 \cdot 3^1
$$

We compute the powers of 3 corresponding to powers of 2, reducing modulo 79 at each step:

- $3^1 = 3 \equiv 3 \mod 79$
- $3^2 = 3 \cdot 3 = 9 \equiv 9 \mod 79$
- $3^4 = (3^2)^2 = 9^2 = 81$ , and since $81 > 79$ , $81 - 79 = 2$ , so $3^4 \equiv 2 \mod 79$
- $3^8 = (3^4)^2 = 2^2 = 4 \equiv 4 \mod 79$
- $3^{16} = (3^8)^2 = 4^2 = 16 \equiv 16 \mod 79$
- $3^{32} = (3^{16})^2 = 16^2 = 256$ , and $256 \div 79 \approx 3.24$ , so $79 \cdot 3 = 237$ , $256 - 237 = 19$ , thus $3^{32} \equiv 19 \mod 79$

Now, combine these using the binary decomposition:

- $3^{32} \equiv 19 \mod 79$
- $3^4 \equiv 2 \mod 79$
- $3^1 \equiv 3 \mod 79$

Calculate:

$$
3^{37} = 3^{32} \cdot 3^4 \cdot 3^1 \equiv 19 \cdot 2 \cdot 3 \mod 79
$$
- First, $19 \cdot 2 = 38$
- Then, $38 \cdot 3 = 114$
- Reduce 114 modulo 79: $114 - 79 = 35$ , so $114 \equiv 35 \mod 79$

Thus, $3^{37} \equiv 35 \mod 79$ .

### Verification

To ensure accuracy, consider an alternative approach by checking the pattern or computing a few more steps. From $3^{37} \equiv 35$ :

- $3^{38} = 3^{37} \cdot 3 \equiv 35 \cdot 3 = 105 \equiv 105 - 79 = 26 \mod 79$
- $3^{39} = 3^{38} \cdot 3 \equiv 26 \cdot 3 = 78 \equiv 78 \mod 79$
- Since $79 - 1 = 78$ , $3^{39} \equiv -1 \mod 79$
- $3^{78} = (3^{39})^2 \equiv (-1)^2 = 1 \mod 79$ , consistent with Fermat's Little Theorem

This confirms the computation aligns with the theorem, reinforcing confidence in the result.

### Final Answer

The remainder when $3^{37}$ is divided by 79 is 35, corresponding to option (D).

**Answer: 35**

what could have been a master way to get to the result

To compute $3^{37} \mod 79$ efficiently and elegantly—a "master way"—we can leverage a combination of **Fermat's Little Theorem** and **binary exponentiation**, optimized for clarity and minimal computation. Since 79 is a prime number and 3 is not divisible by 79, Fermat's Little Theorem tells us that:

$3^{78} \equiv 1 \pmod{79}$

This property can simplify large exponents, but since the exponent 37 is less than 78, we need a method to compute $3^{37}$ directly. A highly efficient approach is binary exponentiation, which reduces the exponent into powers of 2 based on its binary representation, requiring only a few modular multiplications. Let’s explore this master strategy step-by-step.

---

### Step 1: Express the Exponent in Binary

Convert 37 to its binary form to break down the exponentiation:

$37_{10} = 100101_2$

This means:

$37 = 2^5 + 2^2 + 2^0 = 32 + 4 + 1$

Thus, we can write:

$3^{37} = 3^{32} \cdot 3^4 \cdot 3^1$

We’ll compute each term modulo 79 and multiply the results.

---

### Step 2: Compute Successive Powers of 3 Modulo 79

Using successive squaring, calculate the necessary powers of 3 efficiently:

- $3^1 \equiv 3 \pmod{79}$
- $3^2 = 9 \equiv 9 \pmod{79}$  (since 9 < 79)
- $3^4 = (3^2)^2 = 9^2 = 81 \equiv 81 - 79 = 2 \pmod{79}$
- $3^8 = (3^4)^2 = 2^2 = 4 \pmod{79}$
- $3^{16} = (3^8)^2 = 4^2 = 16 \pmod{79}$
- $3^{32} = (3^{16})^2 = 16^2 = 256 \equiv 256 - 79 \cdot 3 = 256 - 237 = 19 \pmod{79}$  
	(Check: $79 \cdot 3 = 237$  , $256 - 237 = 19$  , and 19 < 79)

So, we have:

- $3^{32} \equiv 19 \pmod{79}$
- $3^4 \equiv 2 \pmod{79}$
- $3^1 \equiv 3 \pmod{79}$

---

### Step 3: Multiply the Terms Modulo 79

Now compute:

$3^{37} = 3^{32} \cdot 3^4 \cdot 3^1 \equiv 19 \cdot 2 \cdot 3 \pmod{79}$

Perform the multiplication step-by-step:

1. $19 \cdot 2 = 38$  (since 38 < 79, no reduction needed yet)
2. $38 \cdot 3 = 114$
3. Reduce 114 modulo 79: $114 - 79 = 35$  , so $114 \equiv 35 \pmod{79}$

Thus:

$3^{37} \equiv 35 \pmod{79}$

---

### Step 4: Verification with Fermat’s Theorem

To ensure correctness, use Fermat’s Theorem as a cross-check. Since $3^{78} \equiv 1 \pmod{79}$  , and $78 = 39 + 39$  , we can explore $3^{39}$  :

$3^{78} = (3^{39})^2 \equiv 1 \pmod{79}$

So, $(3^{39})^2 \equiv 1$  , implying $3^{39} \equiv 1$  or $3^{39} \equiv -1 \pmod{79}$  . If $3^{39} \equiv -1$  , then:

$3^{39} = 3^{37} \cdot 3^2 = 3^{37} \cdot 9 \equiv -1 \pmod{79}$

$3^{37} \equiv -1 \cdot 9^{-1} \pmod{79}$

Find the modular inverse of 9 modulo 79 using the Extended Euclidean Algorithm:

- $79 = 8 \cdot 9 + 7$  (since $9 \cdot 8 = 72$  , $79 - 72 = 7$  )
- $9 = 1 \cdot 7 + 2$
- $7 = 3 \cdot 2 + 1$
- $2 = 2 \cdot 1 + 0$

Back-substitute:

- $1 = 7 - 3 \cdot 2$
- $2 = 9 - 1 \cdot 7 = 9 - 7$  , so $1 = 7 - 3 (9 - 7) = 7 - 3 \cdot 9 + 3 \cdot 7 = 4 \cdot 7 - 3 \cdot 9$
- $7 = 79 - 8 \cdot 9$  , so $1 = 4 (79 - 8 \cdot 9) - 3 \cdot 9 = 4 \cdot 79 - 32 \cdot 9 - 3 \cdot 9 = 4 \cdot 79 - 35 \cdot 9$

Thus, $1 \equiv -35 \cdot 9 \pmod{79}$  , and $-35 \equiv 79 - 35 = 44$  , so $9 \cdot 44 \equiv 1 \pmod{79}$  (check: $9 \cdot 44 = 396$  , $396 - 5 \cdot 79 = 396 - 395 = 1$  ).

Then:

$3^{37} \equiv -1 \cdot 44 = -44 \equiv 79 - 44 = 35 \pmod{79}$

This matches our result, confirming consistency.

---

### Why This is a "Master Way"

This approach is masterful because it:

- **Minimizes computations** using binary exponentiation (logarithmic steps: $\log_2 37 \approx 5$  multiplications).
- **Leverages number theory** (Fermat’s Theorem) for verification.
- **Avoids brute force**, making it scalable for larger exponents.
- **Ensures accuracy** with a secondary method, balancing efficiency and reliability.

Thus, the remainder of $3^{37}$  divided by 79 is 35. https://grok.com/chat/3b155b1e-49d6-4cfa-acf4-08da173c88d6?referrer=website