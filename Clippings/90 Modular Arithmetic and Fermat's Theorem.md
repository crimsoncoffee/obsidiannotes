---
title: "Modular Arithmetic and Fermat's Theorem - Grok"
source: "https://grok.com/chat/1c1ab303-80d7-4161-9c00-d19875970829?referrer=website"
author:
published:
created: 2025-04-07
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
Refer to the following content:image.png

To find the remainder when $3^{12} + 5^{12}$ is divided by 13, we need to compute $(3^{12} + 5^{12}) \mod 13$ . Since 13 is a prime number, modular arithmetic techniques, particularly Fermat's Little Theorem, can simplify our calculations. Let’s proceed step by step.

### Step 1: Apply Fermat's Little Theorem

Fermat's Little Theorem states that if $p$ is a prime and $a$ is an integer not divisible by $p$ , then:

$$
a^{p-1} \equiv 1 \pmod{p}.
$$

Here, $p = 13$ , so $p - 1 = 12$ . Since neither 3 nor 5 is divisible by 13, we can apply the theorem:

- For $a = 3$ , $3^{12} \equiv 1 \pmod{13}$ ,
- For $a = 5$ , $5^{12} \equiv 1 \pmod{13}$ .

Thus, the expression becomes:

$$
3^{12} + 5^{12} \equiv 1 + 1 \equiv 2 \pmod{13}.
$$

This suggests the remainder is 2, but let’s verify this result to ensure accuracy.

### Step 2: Verify Using the Order of Elements

The order of an element $a$ modulo $p$ is the smallest positive integer $k$ such that $a^k \equiv 1 \pmod{p}$ . If the exponent is a multiple of the order, the result is 1 modulo $p$ . Let’s find the orders of 3 and 5 modulo 13.

#### Order of 3 modulo 13:

- $3^1 = 3 \equiv 3 \pmod{13}$ ,
- $3^2 = 9 \equiv 9 \pmod{13}$ ,
- $3^3 = 27 = 2 \cdot 13 + 1 = 26 + 1 \equiv 1 \pmod{13}$ .

Since $3^3 \equiv 1 \pmod{13}$ , the order of 3 is 3. Now, $12 = 3 \cdot 4$ , so:

$$
3^{12} = (3^3)^4 \equiv 1^4 \equiv 1 \pmod{13}.
$$

#### Order of 5 modulo 13:

- $5^1 = 5 \equiv 5 \pmod{13}$ ,
- $5^2 = 25 = 1 \cdot 13 + 12 = 13 + 12 \equiv 12 \pmod{13}$ , and $12 = 13 - 1 \equiv -1 \pmod{13}$ ,
- $5^3 = 5 \cdot 12 = 60 = 4 \cdot 13 + 8 = 52 + 8 \equiv 8 \pmod{13}$ ,
- $5^4 = 5 \cdot 8 = 40 = 3 \cdot 13 + 1 = 39 + 1 \equiv 1 \pmod{13}$ .

Since $5^4 \equiv 1 \pmod{13}$ , the order of 5 is 4. Now, $12 = 4 \cdot 3$ , so:

$$
5^{12} = (5^4)^3 \equiv 1^3 \equiv 1 \pmod{13}.
$$

Both calculations confirm:

- $3^{12} \equiv 1 \pmod{13}$ ,
- $5^{12} \equiv 1 \pmod{13}$ .

### Step 3: Compute the Sum

$$
3^{12} + 5^{12} \equiv 1 + 1 = 2 \pmod{13}.
$$

The remainder is 2, which is less than 13, so it’s a valid residue.

### Step 4: Cross-Check with Successive Powers (Optional)

To build confidence, let’s compute $3^{12} \mod 13$ using successive squaring:

- $3^1 \equiv 3 \pmod{13}$ ,
- $3^2 \equiv 9 \pmod{13}$ ,
- $3^4 = 9^2 = 81 = 6 \cdot 13 + 3 = 78 + 3 \equiv 3 \pmod{13}$ ,
- $3^8 = 3^4 \cdot 3^4 \equiv 3 \cdot 3 = 9 \pmod{13}$ ,
- $3^{12} = 3^8 \cdot 3^4 \equiv 9 \cdot 3 = 27 = 2 \cdot 13 + 1 \equiv 1 \pmod{13}$ .

For 5:

- $5^1 \equiv 5 \pmod{13}$ ,
- $5^2 \equiv 12 \pmod{13}$ ,
- $5^4 = 12^2 = 144 = 11 \cdot 13 + 1 = 143 + 1 \equiv 1 \pmod{13}$ ,
- $5^8 = 5^4 \cdot 5^4 \equiv 1 \cdot 1 \equiv 1 \pmod{13}$ ,
- $5^{12} = 5^8 \cdot 5^4 \equiv 1 \cdot 1 \equiv 1 \pmod{13}$ .

Again, $3^{12} + 5^{12} \equiv 1 + 1 \equiv 2 \pmod{13}$ .

### Step 5: Match with Options

The options are:

- (A) 1,
- (B) 2,
- (C) 3,
- (D) 4.

Our result, 2, corresponds to option (B).

### Final Answer

The remainder when $3^{12} + 5^{12}$ is divided by 13 is 2. https://grok.com/chat/1c1ab303-80d7-4161-9c00-d19875970829?referrer=website