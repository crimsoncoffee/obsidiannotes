---
title: "Solving Steady-State Economics Problems - Grok"
source: "https://grok.com/chat/0f968356-b2fe-4207-b9a9-3f16c112b91c"
author:
published:
created: 2025-04-07
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
explain in detail so that i can approach later similiar questions (isi msqe) image.png image.png

Let’s dive into these two questions with a fresh perspective, as if we’re encountering them for the first time. We’ll approach them systematically, using the Socratic method to guide you through the reasoning process. My goal is to help you build a deep understanding of the concepts so you can tackle similar problems confidently in the future, such as those in the ISI MSQE entrance exam. Let’s start with question 22 and then move to question 23.

---

### Question 22: Finding the Capital-Labor Ratio in Steady State

We’re given a Solow economy with a production function $Y = K^{\frac{1}{3}} L^{\frac{2}{3}}$  , a depreciation rate $\delta = 0.05$  , and a savings rate $s = 0.2$  . There’s no population growth or technological change, so we can simplify our analysis. The question asks for the steady-state capital-labor ratio, with options (A) 6, (B) 8, (C) 2, and (D) 4.

Let’s begin by exploring the Solow model. What does the steady state mean in this context? Can you describe what happens to capital and output in the steady state?

---

*(Pause for reflection: The user might consider that in the steady state, the capital stock per worker does not change over time, meaning investment equals depreciation.)*

Good, in the Solow model, the steady state occurs when the capital stock per worker is constant. This happens when the investment in new capital exactly balances the depreciation of existing capital. Since there’s no population growth ( $n = 0$  ) or technological progress ( $g = 0$  ), the capital-labor ratio $k = \frac{K}{L}$  remains constant in the steady state.

Now, let’s define the variables. The production function is $Y = K^{\frac{1}{3}} L^{\frac{2}{3}}$  . To work in per-worker terms, what happens if we divide both sides by $L$  ? How can we express output per worker $y$  in terms of the capital-labor ratio $k$  ?

---

*(Pause: The user might divide through by $L$  to get $y = k^{\frac{1}{3}}$  .)*

Exactly! Dividing the production function by $L$  , we get:

$$
\frac{Y}{L} = \left( \frac{K}{L} \right)^{\frac{1}{3}} \left( \frac{L}{L} \right)^{\frac{2}{3}}
$$

This simplifies to:

$$
y = k^{\frac{1}{3}}
$$

where $y = \frac{Y}{L}$  and $k = \frac{K}{L}$  . So, output per worker depends on the capital-labor ratio.

Next, let’s think about the capital accumulation process. In the Solow model, the change in the capital stock over time is given by investment minus depreciation. The savings rate $s$  determines investment: a fraction $s$  of output is saved and invested. So, investment per worker is $s y$  . Depreciation per worker is $\delta k$  , since the capital stock per worker depreciates at rate $\delta$  .

In the steady state, the capital stock per worker doesn’t change, so the change in $k$  , denoted $\dot{k}$  , is zero. Without population growth or technological progress, the capital accumulation equation simplifies. Can you write down the condition for the steady state in terms of investment and depreciation?

---

*(Pause: The user might recall that $\dot{k} = s y - \delta k$  , and in steady state, $\dot{k} = 0$  .)*

That’s correct! The capital accumulation equation in per-worker terms is:

$$
\dot{k} = s y - \delta k
$$

In the steady state, $\dot{k} = 0$  , so:

$$
s y = \delta k
$$

This means that investment per worker equals depreciation per worker. Now, substitute the expression for $y$  . Since $y = k^{\frac{1}{3}}$  , the steady-state condition becomes:

$$
s k^{\frac{1}{3}} = \delta k
$$

Let’s solve this equation for $k$  . What can you do to isolate terms involving $k$  ? Notice that $k$  appears on both sides with different exponents.

---

*(Pause: The user might divide both sides by $k^{\frac{1}{3}}$  to simplify.)*

Good idea! Let’s divide both sides by $k^{\frac{1}{3}}$  :

$$
s = \delta k^{1 - \frac{1}{3}}
$$
 
$$
s = \delta k^{\frac{2}{3}}
$$

Now, solve for $k^{\frac{2}{3}}$  :

$$
k^{\frac{2}{3}} = \frac{s}{\delta}
$$

To find $k$  , raise both sides to the power of $\frac{3}{2}$  :

$$
k = \left( \frac{s}{\delta} \right)^{\frac{3}{2}}
$$

We have $s = 0.2$  and $\delta = 0.05$  . Let’s compute the ratio:

$$
\frac{s}{\delta} = \frac{0.2}{0.05} = 4
$$

So:

$$
k = 4^{\frac{3}{2}}
$$

What is $4^{\frac{3}{2}}$  ? Break it down: $4^{\frac{3}{2}} = (4^{\frac{1}{2}})^3$  , and $4^{\frac{1}{2}} = \sqrt{4} = 2$  . So:

$$
4^{\frac{3}{2}} = 2^3 = 8
$$

The steady-state capital-labor ratio $k$  is 8. Looking at the options, this matches (B) 8. But let’s double-check our understanding. Does this result make sense economically? If $s$  increases, would you expect $k$  to increase or decrease, and why?

---

*(Pause: The user might reason that a higher savings rate means more investment, leading to a higher steady-state capital stock.)*

Exactly! A higher savings rate increases investment, which should increase the steady-state capital-labor ratio, and our equation $k = \left( \frac{s}{\delta} \right)^{\frac{3}{2}}$  confirms that. Let’s move to question 23.

---

### Question 23: Maximizing Steady-State Per-Capita Consumption

Now, a social planner wants to maximize steady-state per-capita consumption in the same economy. We need to find the savings rate that achieves this, with options (A) $\frac{2}{3}$  , (B) $\frac{1}{2}$  , (C) $\frac{1}{3}$  , and (D) $\frac{1}{4}$  .

First, let’s define per-capita consumption in the steady state. Consumption per worker is output per worker minus investment per worker: $c = y - s y = (1 - s) y$  . In the steady state, we already know $y = k^{\frac{1}{3}}$  , and from question 22, we found that $k = \left( \frac{s}{\delta} \right)^{\frac{3}{2}}$  .

Substitute $k$  into $y$  :

$$
y = \left( \left( \frac{s}{\delta} \right)^{\frac{3}{2}} \right)^{\frac{1}{3}} = \left( \frac{s}{\delta} \right)^{\frac{1}{2}}
$$

So, consumption per worker is:

$$
c = (1 - s) y = (1 - s) \left( \frac{s}{\delta} \right)^{\frac{1}{2}}
$$

The planner wants to maximize $c$  with respect to $s$  . Let’s simplify by focusing on the key components. Notice that $\delta$  is a constant, so maximizing $c$  is equivalent to maximizing:

$$
c = (1 - s) s^{\frac{1}{2}} \delta^{-\frac{1}{2}}
$$

Since $\delta^{-\frac{1}{2}}$  is a constant, we can maximize the function:

$$
f(s) = (1 - s) s^{\frac{1}{2}}
$$

How would you find the savings rate $s$  that maximizes this function? What mathematical tool can we use?

---

*(Pause: The user might suggest taking the derivative and setting it to zero.)*

That’s a great approach! Let’s take the derivative of $f(s) = (1 - s) s^{\frac{1}{2}}$  with respect to $s$  . Use the product rule:

$$
f(s) = (1 - s) s^{\frac{1}{2}}
$$
 
$$
f'(s) = (1 - s)' s^{\frac{1}{2}} + (1 - s) (s^{\frac{1}{2}})'
$$
 
$$
= (-1) s^{\frac{1}{2}} + (1 - s) \cdot \frac{1}{2} s^{-\frac{1}{2}}
$$
 
$$
= -s^{\frac{1}{2}} + \frac{1 - s}{2 s^{\frac{1}{2}}}
$$

Set the derivative equal to zero to find the critical point:

$$
-s^{\frac{1}{2}} + \frac{1 - s}{2 s^{\frac{1}{2}}} = 0
$$
 
$$
\frac{1 - s}{2 s^{\frac{1}{2}}} = s^{\frac{1}{2}}
$$

Multiply through by $2 s^{\frac{1}{2}}$  :

$$
1 - s = 2 s
$$
 
$$
1 = 3 s
$$
 
$$
s = \frac{1}{3}
$$

This savings rate $s = \frac{1}{3}$  corresponds to option (C). But let’s explore why this makes sense. In the Solow model, the savings rate that maximizes steady-state consumption is often related to the exponent of capital in the production function. Here, the production function is $Y = K^{\alpha} L^{1 - \alpha}$  with $\alpha = \frac{1}{3}$  . What’s the significance of $\alpha$  in this context?

---

*(Pause: The user might recall the Golden Rule savings rate, where $s = \alpha$  .)*

Excellent! In the Solow model, the Golden Rule savings rate—the rate that maximizes steady-state consumption—is equal to the capital share of output, which is $\alpha$  . Here, $\alpha = \frac{1}{3}$  , so the optimal savings rate is indeed $\frac{1}{3}$  , confirming our result.

---

### General Approach for Similar Questions

To tackle similar problems in the future (e.g., for ISI MSQE):

1. **Understand the Model**: Identify whether it’s a Solow model, and note the production function, depreciation rate, and whether there’s population growth or technological progress.
2. **Steady-State Condition**: For the capital-labor ratio, use the steady-state condition $s y = (n + g + \delta) k$  . Without $n$  and $g$  , it simplifies to $s y = \delta k$  .
3. **Express Variables**: Convert the production function into per-worker terms ( $y = f(k)$  ) and solve for $k$  .
4. **Golden Rule for Consumption**: To maximize consumption, recognize that the optimal savings rate often equals the capital share $\alpha$  , or solve by maximizing $c = (1 - s) y$  with respect to $s$  .
5. **Check Your Work**: Verify your calculations and ensure the result aligns with economic intuition (e.g., higher savings increases $k$  , and the Golden Rule savings rate depends on the production function).

Does this approach feel clear? How would you apply it to a problem with population growth or a different production function?

do it again

Let’s dive into these two questions from scratch, solving them step-by-step as if we’re encountering them for the first time. We’ll assume they’re based on a Solow growth model, given the context of finding a steady-state capital-labor ratio and maximizing steady-state consumption. The goal is to provide a clear, complete solution that stands on its own, perfect for someone preparing for an exam like the ISI MSQE. Let’s get started!

---

### Question 22: Finding the Steady-State Capital-Labor Ratio

We’re tasked with finding the steady-state capital-labor ratio in a Solow economy. Suppose we’re given:

- Production function: $Y = K^{\frac{1}{3}} L^{\frac{2}{3}}$
- Depreciation rate: $\delta = 0.05$
- Savings rate: $s = 0.2$
- No population growth ( $n = 0$  ) or technological progress ( $g = 0$  )
- Options: (A) 6, (B) 8, (C) 2, (D) 4

#### Step 1: Understand the Steady State

In the Solow model, the steady state is where the capital stock per worker doesn’t change over time. Investment in new capital balances the depreciation of existing capital, keeping the capital-labor ratio $k = \frac{K}{L}$  constant. Since there’s no population growth or technological progress, this simplifies our analysis.

#### Step 2: Express Output in Per-Worker Terms

The production function is $Y = K^{\frac{1}{3}} L^{\frac{2}{3}}$  . To work in per-worker terms, divide both sides by $L$  :

$$
\frac{Y}{L} = \left( \frac{K}{L} \right)^{\frac{1}{3}} \left( \frac{L}{L} \right)^{\frac{2}{3}}
$$
 
$$
y = \left( \frac{K}{L} \right)^{\frac{1}{3}} = k^{\frac{1}{3}}
$$

Here, $y = \frac{Y}{L}$  is output per worker, and $k = \frac{K}{L}$  is the capital-labor ratio. So, $y = k^{\frac{1}{3}}$  .

#### Step 3: Set Up the Steady-State Condition

In the Solow model, the capital stock per worker evolves according to:

$$
\dot{k} = s y - \delta k
$$
- **Investment per worker**: $s y$  (since a fraction $s$  of output is saved and invested)
- **Depreciation per worker**: $\delta k$  (capital depreciates at rate $\delta$  )

In the steady state, $\dot{k} = 0$  (the capital-labor ratio is constant), so:

$$
s y = \delta k
$$

Substitute $y = k^{\frac{1}{3}}$  :

$$
s k^{\frac{1}{3}} = \delta k
$$

#### Step 4: Solve for k k

To find the steady-state $k$  , isolate terms. Divide both sides by $k^{\frac{1}{3}}$  :

$$
s = \delta k^{1 - \frac{1}{3}}
$$
 
$$
s = \delta k^{\frac{2}{3}}
$$

Solve for $k^{\frac{2}{3}}$  :

$$
k^{\frac{2}{3}} = \frac{s}{\delta}
$$

Raise both sides to the power of $\frac{3}{2}$  to solve for $k$  :

$$
k = \left( \frac{s}{\delta} \right)^{\frac{3}{2}}
$$

#### Step 5: Plug in Values

Given $s = 0.2$  and $\delta = 0.05$  :

$$
\frac{s}{\delta} = \frac{0.2}{0.05} = 4
$$
 
$$
k = 4^{\frac{3}{2}}
$$

Calculate $4^{\frac{3}{2}}$  :

- $4^{\frac{1}{2}} = \sqrt{4} = 2$
- $4^{\frac{3}{2}} = (4^{\frac{1}{2}})^3 = 2^3 = 8$

So, the steady-state capital-labor ratio is $k = 8$  .

#### Step 6: Verify

Among the options (A) 6, (B) 8, (C) 2, (D) 4, our result matches **(B) 8**. Economically, a higher savings rate increases investment, raising the steady-state $k$  , which aligns with our formula.

**Answer for Question 22: (B) 8**

---

### Question 23: Maximizing Steady-State Per-Capita Consumption

Now, a social planner wants to maximize steady-state per-capita consumption in the same economy. We need to find the optimal savings rate, with options: (A) $\frac{2}{3}$  , (B) $\frac{1}{2}$  , (C) $\frac{1}{3}$  , (D) $\frac{1}{4}$  .

#### Step 1: Define Consumption

Per-capita consumption is output per worker minus investment per worker:

- Total output per worker: $y$
- Investment per worker: $s y$
- Consumption per worker: $c = y - s y = (1 - s) y$

#### Step 2: Relate y y to k k

From Question 22, $y = k^{\frac{1}{3}}$  , and in the steady state:

$$
s k^{\frac{1}{3}} = \delta k
$$
 
$$
k^{\frac{2}{3}} = \frac{s}{\delta}
$$
 
$$
k = \left( \frac{s}{\delta} \right)^{\frac{3}{2}}
$$

So:

$$
y = k^{\frac{1}{3}} = \left( \left( \frac{s}{\delta} \right)^{\frac{3}{2}} \right)^{\frac{1}{3}} = \left( \frac{s}{\delta} \right)^{\frac{1}{2}}
$$

#### Step 3: Express Consumption

Substitute into the consumption equation:

$$
c = (1 - s) y = (1 - s) \left( \frac{s}{\delta} \right)^{\frac{1}{2}}
$$

Since $\delta = 0.05$  is constant, maximizing $c$  is equivalent to maximizing:

$$
f(s) = (1 - s) s^{\frac{1}{2}}
$$

(The term $\delta^{-\frac{1}{2}}$  is a positive constant and doesn’t affect the optimal $s$  .)

#### Step 4: Maximize f(s) f(s)

Take the derivative of $f(s) = (1 - s) s^{\frac{1}{2}}$  using the product rule:

- Let $u = (1 - s)$  , $v = s^{\frac{1}{2}}$
- $u' = -1$  , $v' = \frac{1}{2} s^{-\frac{1}{2}}$
$$
f'(s) = u' v + u v' = (-1) s^{\frac{1}{2}} + (1 - s) \cdot \frac{1}{2} s^{-\frac{1}{2}}
$$
 
$$
= -s^{\frac{1}{2}} + \frac{1 - s}{2 s^{\frac{1}{2}}}
$$

Set $f'(s) = 0$  :

$$
-s^{\frac{1}{2}} + \frac{1 - s}{2 s^{\frac{1}{2}}} = 0
$$
 
$$
\frac{1 - s}{2 s^{\frac{1}{2}}} = s^{\frac{1}{2}}
$$

Multiply by $2 s^{\frac{1}{2}}$  :

$$
1 - s = 2 s
$$
 
$$
1 = 3 s
$$
 
$$
s = \frac{1}{3}
$$

#### Step 5: Verify with the Golden Rule

In the Solow model, the savings rate that maximizes steady-state consumption (the Golden Rule) equals the capital share in the production function $Y = K^{\alpha} L^{1 - \alpha}$  . Here, $\alpha = \frac{1}{3}$  , so the optimal $s = \frac{1}{3}$  , which matches our result.

#### Step 6: Check Options

Options are (A) $\frac{2}{3}$  , (B) $\frac{1}{2}$  , (C) $\frac{1}{3}$  , (D) $\frac{1}{4}$  . Our calculated $s = \frac{1}{3}$  corresponds to **(C) $\frac{1}{3}$** .

**Answer for Question 23: (C) $\frac{1}{3}$**

---

### Final Answers

- **Question 22**: The steady-state capital-labor ratio is **(B) 8**.
- **Question 23**: The savings rate that maximizes steady-state consumption is **(C) $\frac{1}{3}$** .

These solutions are grounded in the Solow model’s core principles, making them a solid foundation for tackling similar problems! https://grok.com/chat/0f968356-b2fe-4207-b9a9-3f16c112b91c