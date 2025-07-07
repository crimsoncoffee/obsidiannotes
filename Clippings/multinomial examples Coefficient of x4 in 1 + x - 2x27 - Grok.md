---
title: "Coefficient of \x^4\ in \1 + x - 2x^2^7\ - Grok"
source: "https://grok.com/chat/1a148689-f083-4fab-a7a1-4446aa0ff4ae"
author:
published:
created: 2025-04-01
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
Refer to the following content:image.png

To find the coefficient of $x^4$  in the expansion of $(1 + x - 2x^2)^7$  , we use the multinomial theorem, which applies to expressions of the form $(a_1 + a_2 + \cdots + a_m)^n$  . Here, the expression is a trinomial with terms $1$  , $x$  , and $-2x^2$  , raised to the power 7. The multinomial theorem states that the expansion is:

$$
\sum_{k_1 + k_2 + k_3 = 7} \frac{7!}{k_1! k_2! k_3!} (1)^{k_1} (x)^{k_2} (-2x^2)^{k_3}
$$

where $k_1, k_2, k_3$  are non-negative integers satisfying $k_1 + k_2 + k_3 = 7$  , and the sum is over all such triples. Each term contributes an $x$  \-exponent from $(x)^{k_2}$  and $(-2x^2)^{k_3} = (-2)^{k_3} (x^2)^{k_3} = (-2)^{k_3} x^{2k_3}$  , so the total exponent of $x$  is:

$$
k_2 + 2k_3
$$

We need this to equal 4, since we’re seeking the coefficient of $x^4$  :

$$
k_2 + 2k_3 = 4
$$

The coefficient of each term is:

$$
\frac{7!}{k_1! k_2! k_3!} (1)^{k_1} (-2)^{k_3}
$$

since $(1)^{k_1} = 1$  , and we’ll sum the coefficients for all triples that satisfy both conditions.

### Step 1: Identify Valid Triples

Since $k_2 + 2k_3 = 4$  and $k_1 + k_2 + k_3 = 7$  , and all $k_i \geq 0$  , we determine possible values for $k_3$  . Because $2k_3 \leq 4$  (as $k_2 \geq 0$  ), we have $k_3 \leq 2$  . Thus, $k_3 = 0, 1, 2$  . We solve for each case:

- **Case 1: $k_3 = 0$**  
	$k_2 + 2(0) = 4 \implies k_2 = 4$  
	$k_1 + 4 + 0 = 7 \implies k_1 = 3$  
	Triple: $(k_1, k_2, k_3) = (3, 4, 0)$
- **Case 2: $k_3 = 1$**  
	$k_2 + 2(1) = 4 \implies k_2 + 2 = 4 \implies k_2 = 2$  
	$k_1 + 2 + 1 = 7 \implies k_1 = 4$  
	Triple: $(4, 2, 1)$
- **Case 3: $k_3 = 2$**  
	$k_2 + 2(2) = 4 \implies k_2 + 4 = 4 \implies k_2 = 0$  
	$k_1 + 0 + 2 = 7 \implies k_1 = 5$  
	Triple: $(5, 0, 2)$

If $k_3 = 3$  , then $2k_3 = 6 > 4$  , and $k_2 + 6 = 4$  is impossible since $k_2 \geq 0$  . Higher $k_3$  values make $2k_3$  even larger, so $k_3 \leq 2$  covers all cases.

### Step 2: Compute Coefficients

For each triple, calculate the coefficient $\frac{7!}{k_1! k_2! k_3!} (-2)^{k_3}$  , where $7! = 5040$  .

- **Triple $(3, 4, 0)$  :**  
	$k_1! = 3! = 6$  , $k_2! = 4! = 24$  , $k_3! = 0! = 1$  
	$\frac{7!}{3! 4! 0!} = \frac{5040}{6 \cdot 24 \cdot 1} = \frac{5040}{144} = 35$  
	$(-2)^0 = 1$  
	Coefficient: $35 \cdot 1 = 35$  
	Check: $x$  \-exponent = $4 + 2(0) = 4$  , correct.
- **Triple $(4, 2, 1)$  :**  
	$4! = 24$  , $2! = 2$  , $1! = 1$  
	$\frac{7!}{4! 2! 1!} = \frac{5040}{24 \cdot 2 \cdot 1} = \frac{5040}{48} = 105$  (since $48 \cdot 105 = 5040$  )  
	$(-2)^1 = -2$  
	Coefficient: $105 \cdot (-2) = -210$  
	Check: $2 + 2(1) = 2 + 2 = 4$  .
- **Triple $(5, 0, 2)$  :**  
	$5! = 120$  , $0! = 1$  , $2! = 2$  
	$\frac{7!}{5! 0! 2!} = \frac{5040}{120 \cdot 1 \cdot 2} = \frac{5040}{240} = 21$  (since $240 \cdot 21 = 5040$  )  
	$(-2)^2 = 4$  
	Coefficient: $21 \cdot 4 = 84$  
	Check: $0 + 2(2) = 4$  .

### Step 3: Sum the Coefficients

Total coefficient of $x^4$  :

$$
35 + (-210) + 84
$$

Compute step-by-step:  
$35 - 210 = -175$  
$-175 + 84 = -91$

### Verification

The triples exhaust all solutions to $k_2 + 2k_3 = 4$  and $k_1 + k_2 + k_3 = 7$  , and calculations align with the multinomial formula. The options are -81, -91, +81, +91, and -91 matches option (B).

Thus, the coefficient of $x^4$  is **\-91**. https://grok.com/chat/1a148689-f083-4fab-a7a1-4446aa0ff4ae