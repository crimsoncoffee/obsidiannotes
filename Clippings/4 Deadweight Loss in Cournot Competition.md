---
title: "Deadweight Loss in Cournot Competition - Grok"
source: "https://grok.com/chat/89062b80-8b51-45ed-b102-4fbc5cae9a84"
author:
published:
created: 2025-04-03
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
how to calculate deadweight loss when firms compete in quantities

To calculate the **deadweight loss (DWL)** when firms compete in quantities, we are typically dealing with a **Cournot competition model**. In this model, firms simultaneously choose the quantity of a homogeneous product to produce, and the market price is determined by the total quantity supplied. Deadweight loss represents the loss of economic efficiency compared to a perfectly competitive market, where price equals marginal cost. Below, I’ll guide you through the steps to compute it, assuming a **linear demand curve** and **constant marginal costs**, which is a common setup for such problems.

---

### Step 1: Define the Market Setup

Consider a market with:

- **n firms** competing by setting quantities.
- **Inverse demand function**: $P(Q) = a - bQ$  , where:
	- $P$  is the market price,
	- $Q = q_1 + q_2 + \cdots + q_n$  is the total quantity produced by all firms,
	- $a > 0$  is the demand intercept (maximum price when $Q = 0$  ),
	- $b > 0$  is the slope of the demand curve.
- **Cost function**: Each firm has the same constant marginal cost $c$  , with no fixed costs, so $C(q_i) = c q_i$  for firm $i$  , where $0 < c < a$  .

Our goal is to find the DWL by comparing the Cournot equilibrium to the perfectly competitive outcome.

---

### Step 2: Cournot Equilibrium

In Cournot competition, each firm maximizes its profit, taking the quantities of other firms as given. The profit for firm $i$  is:

$$
\pi_i = P(Q) q_i - C(q_i) = (a - bQ) q_i - c q_i
$$

Since $Q = q_i + Q_{-i}$  , where $Q_{-i} = \sum_{j \neq i} q_j$  is the total output of all other firms, we can write:

$$
\pi_i = [a - b (q_i + Q_{-i})] q_i - c q_i
$$

To find the equilibrium, take the derivative of $\pi_i$  with respect to $q_i$  (treating $Q_{-i}$  as fixed) and set it to zero:

$$
\frac{d\pi_i}{dq_i} = a - b Q_{-i} - 2b q_i - c = 0
$$

Solve for $q_i$  :

$$
2b q_i = a - c - b Q_{-i}
$$
 
$$
q_i = \frac{a - c - b Q_{-i}}{2b}
$$

Since all firms are identical, in equilibrium, $q_i = q$  for all $i$  . Thus, $Q = n q$  and $Q_{-i} = (n - 1) q$  . Substitute into the equation:

$$
q = \frac{a - c - b (n - 1) q}{2b}
$$

Multiply through by $2b$  :

$$
2b q = a - c - b (n - 1) q
$$

Rearrange all terms involving $q$  :

$$
2b q + b (n - 1) q = a - c
$$
 
$$
b q [2 + (n - 1)] = a - c
$$
 
$$
b q (n + 1) = a - c
$$
 
$$
q = \frac{a - c}{b (n + 1)}
$$
- **Total quantity**: $Q = n q = \frac{n (a - c)}{b (n + 1)}$
- **Market price**: $P = a - b Q = a - b \cdot \frac{n (a - c)}{b (n + 1)} = a - \frac{n (a - c)}{n + 1}$

Simplify the price:

$$
P = a - \frac{n (a - c)}{n + 1} = \frac{a (n + 1) - n (a - c)}{n + 1} = \frac{a n + a - n a + n c}{n + 1} = \frac{a + n c}{n + 1}
$$

So, in the Cournot equilibrium:

- **Quantity**: $Q = \frac{n (a - c)}{b (n + 1)}$
- **Price**: $P = \frac{a + n c}{n + 1}$

---

### Step 3: Perfectly Competitive Outcome

In a perfectly competitive market, firms produce where price equals marginal cost ( $P = c$  ):

$$
a - b Q = c
$$
 
$$
b Q = a - c
$$
 
$$
Q_{pc} = \frac{a - c}{b}
$$
- **Quantity**: $Q_{pc} = \frac{a - c}{b}$
- **Price**: $P_{pc} = c$

Notice that $Q_{pc} > Q$  (since $n/(n + 1) < 1$  ) and $P_{pc} < P$  (since $c < \frac{a + n c}{n + 1} < a$  ), indicating that Cournot competition results in less output and a higher price than perfect competition, leading to inefficiency.

---

### Step 4: Calculate Deadweight Loss

Deadweight loss is the welfare loss due to underproduction in Cournot compared to perfect competition. With linear demand and constant marginal cost, it’s the area of the triangle between the demand curve ( $P(Q)$  ) and the marginal cost ( $c$  ), from $Q$  (Cournot quantity) to $Q_{pc}$  (competitive quantity).

- **Base of the triangle**: $Q_{pc} - Q$
- **Height of the triangle**: $P - c$  (the price difference at $Q$  )

Compute these:

- $Q_{pc} - Q = \frac{a - c}{b} - \frac{n (a - c)}{b (n + 1)} = \frac{a - c}{b} \left[ 1 - \frac{n}{n + 1} \right] = \frac{a - c}{b} \cdot \frac{1}{n + 1} = \frac{a - c}{b (n + 1)}$
- $P - c = \frac{a + n c}{n + 1} - c = \frac{a + n c - c (n + 1)}{n + 1} = \frac{a + n c - c n - c}{n + 1} = \frac{a - c}{n + 1}$

Area of the triangle:

$$
DWL = \frac{1}{2} \cdot (P - c) \cdot (Q_{pc} - Q) = \frac{1}{2} \cdot \frac{a - c}{n + 1} \cdot \frac{a - c}{b (n + 1)}
$$
 
$$
= \frac{1}{2} \cdot \frac{(a - c)^2}{b (n + 1)^2}
$$

Alternatively, write it as:

$$
DWL = \frac{(a - c)^2}{2 b (n + 1)^2}
$$

---

### Step 5: Verify the Result

- **Monopoly case ( $n = 1$  )**:  
	$DWL = \frac{(a - c)^2}{2 b (1 + 1)^2} = \frac{(a - c)^2}{2 b \cdot 4} = \frac{(a - c)^2}{8 b}$  , which matches the standard monopoly DWL with linear demand.
- **As $n \to \infty$** :  
	$DWL \to 0$  , since $(n + 1)^2 \to \infty$  , reflecting that the market approaches perfect competition.

---

### Final Answer

The deadweight loss when $n$  firms compete in quantities under Cournot competition, with demand $P = a - bQ$  and marginal cost $c$  , is:

$$
\frac{(a - c)^2}{2 b (n + 1)^2}
$$

This formula quantifies the efficiency loss due to strategic quantity setting, decreasing as the number of firms increases.

total dwl

To determine the total deadweight loss (DWL) when firms compete in quantities, we consider a scenario of Cournot competition. In this market structure, multiple firms simultaneously choose their production quantities, and the market price is determined by the total quantity supplied. Deadweight loss arises because firms with market power produce less than the socially optimal quantity, leading to a loss of economic efficiency compared to perfect competition.

### Assumptions and Setup

We assume:

- **Linear demand**: The market demand curve is given by $P = a - bQ$  , where $P$  is the price, $Q$  is the total quantity, $a$  is the demand intercept (maximum willingness to pay), and $b$  is the slope parameter.
- **Constant marginal cost**: Each firm has the same marginal cost $c$  , where $c < a$  .
- **Number of firms**: There are $n$  identical firms competing in quantities.

### Step 1: Cournot Equilibrium

In Cournot competition, each firm maximizes its profit by choosing its quantity, taking the quantities of the other firms as given. For $n$  firms, let $q_i$  be the quantity produced by firm $i$  , and $Q = q_1 + q_2 + \cdots + q_n$  . Since the firms are identical, in equilibrium, they produce the same quantity, so $q_i = q$  for all $i$  , and $Q = n q$  .

The profit for firm $i$  is: $\pi_i = (P - c) q_i = [a - b (q_i + Q_{-i}) - c] q_i$  where $Q_{-i} = Q - q_i$  is the total quantity produced by all other firms.

To find the optimal $q_i$  , take the derivative with respect to $q_i$  and set it to zero: $\frac{d\pi_i}{dq_i} = a - b Q_{-i} - c - b q_i = 0$  Since $Q_{-i} = (n - 1) q$  in symmetric equilibrium: $a - b (n - 1) q - c - b q = 0$  $a - c - b [ (n - 1) q + q ] = 0$  $a - c - b n q = 0$  $q = \frac{a - c}{b (n + 1)}$

Thus, the total quantity in Cournot equilibrium is: $Q = n q = n \cdot \frac{a - c}{b (n + 1)} = \frac{n (a - c)}{b (n + 1)}$

The equilibrium price is: $P = a - b Q = a - b \cdot \frac{n (a - c)}{b (n + 1)} = a - \frac{n (a - c)}{n + 1}$  $P = \frac{a (n + 1) - n (a - c)}{n + 1} = \frac{a n + a - n a + n c}{n + 1} = \frac{a + n c}{n + 1}$

### Step 2: Perfectly Competitive Equilibrium

In perfect competition, firms produce where price equals marginal cost ( $P = c$  ). Using the demand curve: $c = a - b Q_{pc}$  $Q_{pc} = \frac{a - c}{b}$  Here, $Q_{pc}$  is the total quantity under perfect competition, and the price is $P_{pc} = c$  .

### Step 3: Deadweight Loss Calculation

Deadweight loss is the welfare loss due to the difference between the Cournot quantity and the competitive quantity. It’s the area of the triangle between the demand curve and the marginal cost curve from $Q$  (Cournot quantity) to $Q_{pc}$  (competitive quantity).

- **Base of the triangle**: The difference in quantities: $Q_{pc} - Q = \frac{a - c}{b} - \frac{n (a - c)}{b (n + 1)}$  $= \frac{a - c}{b} \left[ 1 - \frac{n}{n + 1} \right] = \frac{a - c}{b} \cdot \frac{1}{n + 1} = \frac{a - c}{b (n + 1)}$
- **Height of the triangle**: The difference between the Cournot price and the marginal cost: $P - c = \frac{a + n c}{n + 1} - c = \frac{a + n c - c (n + 1)}{n + 1} = \frac{a + n c - n c - c}{n + 1} = \frac{a - c}{n + 1}$
- **Area of the triangle** (DWL): $\text{DWL} = \frac{1}{2} \cdot (\text{base}) \cdot (\text{height})$  $= \frac{1}{2} \cdot \frac{a - c}{b (n + 1)} \cdot \frac{a - c}{n + 1}$  $= \frac{1}{2} \cdot \frac{(a - c)^2}{b (n + 1)^2}$

### Final Result

The total deadweight loss when $n$  firms compete in quantities under Cournot competition, with linear demand $P = a - b Q$  and constant marginal cost $c$  , is:

$\frac{(a - c)^2}{2 b (n + 1)^2}$

This formula shows that DWL decreases as the number of firms $n$  increases, approaching zero as $n$  becomes large, which aligns with the intuition that competition intensifies and the market approximates perfect competition.

Refer to the following content:image.png

To calculate the total deadweight loss in this market, we need to analyze a scenario where 10 firms compete in quantities, given a market demand function and their cost functions. The market demand is $p = 100 - q$  , where $p$  is the market price and $q$  is the aggregate quantity demanded. Each of the 10 firms has an identical cost function $c_i(q_i) = q_i$  , where $q_i$  is the quantity produced by firm $i$  (for $i = 1$  to 10), implying a constant marginal cost of 1 per unit. Since the firms compete in quantities, this suggests a Cournot competition model. Deadweight loss represents the loss of economic efficiency due to market power, where the quantity traded is less than in a perfectly competitive market. Let’s solve this step-by-step.

---

### Step 1: Cournot Equilibrium

In Cournot competition, each firm chooses its quantity $q_i$  to maximize profit, taking the quantities of the other firms as given. Since the 10 firms are identical, we assume a symmetric equilibrium where each firm produces the same quantity, $q_i = q$  . The total market quantity is then $q = Q = 10q$  , and the market price becomes:

$p = 100 - Q = 100 - 10q$

Each firm’s profit is revenue minus cost:

$\pi_i = p \cdot q_i - c_i(q_i) = (100 - Q) \cdot q_i - q_i$

Substitute $Q = q_i + Q_{-i}$  , where $Q_{-i} = \sum_{j \neq i} q_j$  is the total quantity produced by the other 9 firms. In symmetric equilibrium, $q_j = q$  for all $j$  , so $Q_{-i} = 9q$  . Thus:

$Q = q_i + 9q$

$p = 100 - (q_i + 9q)$

$\pi_i = [100 - (q_i + 9q)] q_i - q_i$

To find the equilibrium, maximize $\pi_i$  with respect to $q_i$  , treating $Q_{-i} = 9q$  as fixed (since firm $i$  takes others’ outputs as given). Compute the derivative:

$\frac{d\pi_i}{dq_i} = [100 - q_i - 9q] + q_i (-1) - 1 = 100 - q_i - 9q - q_i - 1 = 99 - 2q_i - 9q$

Set the first-order condition to zero:

$99 - 2q_i - 9q = 0$

$2q_i = 99 - 9q$

$q_i = \frac{99 - 9q}{2}$

In symmetric equilibrium, $q_i = q$  , so:

$q = \frac{99 - 9q}{2}$

Multiply through by 2:

$2q = 99 - 9q$

$11q = 99$

$q = \frac{99}{11} = 9$

Each firm produces $q = 9$  units. Total quantity is:

$Q = 10q = 10 \cdot 9 = 90$

Market price is:

$p = 100 - 90 = 10$

---

### Step 2: Perfectly Competitive Outcome

In perfect competition, price equals marginal cost. The marginal cost for each firm is:

$MC = \frac{d c_i(q_i)}{d q_i} = \frac{d (q_i)}{d q_i} = 1$

Set $p = MC$  :

$100 - q = 1$

$q = 99$

In perfect competition, the total quantity is 99 units, and the price is 1.

---

### Step 3: Deadweight Loss Calculation

Deadweight loss is the welfare loss due to underproduction in Cournot compared to perfect competition. It’s the area of the triangle between the demand curve ( $p = 100 - q$  ) and the marginal cost ( $MC = 1$  ) from the Cournot quantity ( $Q = 90$  ) to the competitive quantity ( $q = 99$  ).

- **Base**: Difference in quantities = $99 - 90 = 9$
- **Height**: Difference between the Cournot price and marginal cost = $p - MC = 10 - 1 = 9$

For a triangle:

$DWL = \frac{1}{2} \cdot \text{base} \cdot \text{height} = \frac{1}{2} \cdot 9 \cdot 9 = \frac{1}{2} \cdot 81 = 40.5$

---

### Step 4: Verification with General Formula

For Cournot with linear demand $p = a - b q$  , constant marginal cost $c$  , and $n$  firms, the deadweight loss is:

$DWL = \frac{(a - c)^2}{2 b (n + 1)^2}$

Here, $p = 100 - q$  , so $a = 100$  , $b = 1$  ; $c = 1$  ; $n = 10$  :

$DWL = \frac{(100 - 1)^2}{2 \cdot 1 \cdot (10 + 1)^2} = \frac{99^2}{2 \cdot 11^2} = \frac{9801}{2 \cdot 121} = \frac{9801}{242} = 40.5$

This matches our earlier result.

---

### Final Answer

The total deadweight loss is 40.5. https://grok.com/chat/89062b80-8b51-45ed-b102-4fbc5cae9a84