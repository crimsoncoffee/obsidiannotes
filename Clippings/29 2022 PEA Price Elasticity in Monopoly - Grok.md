---
title: "Price Elasticity in Monopoly - Grok"
source: "https://grok.com/chat/3fe9ccd4-2c4c-4c37-a50e-cb52c3cc15ff"
author:
published:
created: 2025-04-01
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
Refer to the following content:image.png

To determine the price elasticity of demand at the profit-maximizing price for the monopolist, we need to follow a structured approach using the given cost function $C = 3q^2 + 800$  and the inverse market demand function $p^* = 280 - 4q$  . Let’s solve this step by step.

### Step 1: Understand the Profit-Maximizing Condition

A monopolist maximizes profit where **marginal revenue (MR)** equals **marginal cost (MC)**. Our first task is to derive these functions and find the profit-maximizing output $q$  .

### Step 2: Calculate Marginal Cost (MC)

The total cost function is:

$$
C = 3q^2 + 800
$$

Marginal cost is the derivative of the total cost with respect to quantity $q$  :

$$
MC = \frac{dC}{dq} = \frac{d}{dq}(3q^2 + 800) = 6q
$$

So, $MC = 6q$  .

### Step 3: Calculate Marginal Revenue (MR)

The inverse demand function gives price as a function of quantity:

$$
p^* = 280 - 4q
$$

Total revenue (TR) is price times quantity:

$$
TR = p^* \times q = (280 - 4q)q = 280q - 4q^2
$$

Marginal revenue is the derivative of total revenue with respect to $q$  :

$$
MR = \frac{dTR}{dq} = \frac{d}{dq}(280q - 4q^2) = 280 - 8q
$$

So, $MR = 280 - 8q$  .

### Step 4: Find the Profit-Maximizing Quantity

Set $MR = MC$  to find the profit-maximizing output:

$$
280 - 8q = 6q
$$

Solve for $q$  :

$$
280 = 8q + 6q
$$
 
$$
280 = 14q
$$
 
$$
q = \frac{280}{14} = 20
$$

The profit-maximizing quantity is $q = 20$  .

### Step 5: Determine the Profit-Maximizing Price

Substitute $q = 20$  into the inverse demand function to find the price:

$$
p^* = 280 - 4(20) = 280 - 80 = 200
$$

So, the profit-maximizing price is $p^* = 200$  .

### Step 6: Calculate the Price Elasticity of Demand

Price elasticity of demand ( $\epsilon$  ) measures how responsive quantity demanded is to a change in price, defined as:

$$
\epsilon = \left( \frac{dq}{dp} \right) \times \frac{p}{q}
$$

The inverse demand function is $p = 280 - 4q$  . To use the elasticity formula, express quantity as a function of price:

$$
p = 280 - 4q
$$
 
$$
4q = 280 - p
$$
 
$$
q = \frac{280 - p}{4} = 70 - \frac{p}{4}
$$

This is the demand function $q = 70 - \frac{p}{4}$  . Now, compute the derivative:

$$
\frac{dq}{dp} = \frac{d}{dp} \left( 70 - \frac{p}{4} \right) = -\frac{1}{4}
$$

At the profit-maximizing point, $p = 200$  and $q = 20$  . Substitute these values:

$$
\epsilon = \left( -\frac{1}{4} \right) \times \frac{200}{20} = -\frac{1}{4} \times 10 = -2.5
$$

The price elasticity of demand is $\epsilon = -2.5$  .

### Step 7: Verify the Calculation

For a linear demand curve, the monopolist’s profit-maximizing price occurs where elasticity is elastic (i.e., $|\epsilon| > 1$  ), and we can cross-check using the Lerner index, which relates markup to elasticity:

$$
\frac{p - MC}{p} = -\frac{1}{\epsilon}
$$

Calculate $MC$  at $q = 20$  :

$$
MC = 6(20) = 120
$$
 
$$
\frac{p - MC}{p} = \frac{200 - 120}{200} = \frac{80}{200} = 0.4
$$
 
$$
-\frac{1}{\epsilon} = 0.4
$$
 
$$
\epsilon = -\frac{1}{0.4} = -2.5
$$

This matches our previous result, confirming the calculation.

### Final Answer

The price elasticity of demand at the profit-maximizing price is **\-2.5**, corresponding to option (C) from the multiple-choice options provided:

- (A) -4.5
- (B) -3.5
- (C) -2.5
- (D) -1.5

EXPLAIN ME in Detail related concepts to the monopolist at intermediate advance level prepare me for all the concepts that come in questions of ISI MSQE

To address your query, I’ll explain the concepts related to a monopolist at an intermediate to advanced level, tailored to prepare you for questions like those in the ISI MSQE entrance exam. This will cover profit maximization, cost functions, demand functions, marginal revenue, marginal cost, and price elasticity of demand—key topics that often appear in such exams. I’ll use the example from the thinking trace ( $C = 3q^2 + 800$  , $p^* = 280 - 4q$  , and finding elasticity at the profit-maximizing price) to illustrate these concepts practically.

---

### 1\. Understanding a Monopolist

A **monopolist** is a single seller in a market with no close substitutes for its product. Unlike a perfectly competitive firm (which takes price as given), a monopolist has **market power**, meaning it can influence the price by adjusting its output. The monopolist faces the entire market demand curve, which is typically downward-sloping, implying that to sell more, it must lower the price.

#### Key Objective: Profit Maximization

The monopolist maximizes profit where **marginal revenue (MR)** equals **marginal cost (MC)**. Profit ( $\pi$  ) is defined as:

$$
\pi = TR - TC
$$
- **Total Revenue (TR)** = Price ( $p$  ) × Quantity ( $q$  )
- **Total Cost (TC)** = Given by the cost function

To maximize profit, take the derivative of $\pi$  with respect to $q$  and set it to zero:

$$
\frac{d\pi}{dq} = \frac{dTR}{dq} - \frac{dTC}{dq} = MR - MC = 0
$$

Thus, $MR = MC$  .

---

### 2\. Cost Function and Marginal Cost

The cost function represents the total cost of producing $q$  units. In the example, it’s given as:

$$
C = 3q^2 + 800
$$
- $3q^2$  : Variable cost (increases with output)
- $800$  : Fixed cost (constant regardless of output)

**Marginal Cost (MC)** is the additional cost of producing one more unit, calculated as the derivative of the cost function with respect to $q$  :

$$
MC = \frac{dC}{dq} = \frac{d}{dq}(3q^2 + 800) = 6q
$$

So, $MC = 6q$  . This is a linear function, meaning the cost of producing each additional unit increases with output.

---

### 3\. Demand Function and Total Revenue

The **inverse market demand function** gives price as a function of quantity:

$$
p^* = 280 - 4q
$$
- $280$  : Intercept (price when $q = 0$  )
- $-4$  : Slope (price decreases by 4 for each additional unit sold)

To express quantity demanded as a function of price (standard demand form), invert it:

$$
p = 280 - 4q
$$
 
$$
4q = 280 - p
$$
 
$$
q = \frac{280 - p}{4} = 70 - \frac{p}{4}
$$

**Total Revenue (TR)** is:

$$
TR = p \times q = (280 - 4q)q = 280q - 4q^2
$$

---

### 4\. Marginal Revenue

For a monopolist, **marginal revenue** is not equal to price because increasing output lowers the price on all units sold (due to the downward-sloping demand curve). MR is the derivative of TR with respect to $q$  :

$$
MR = \frac{dTR}{dq} = \frac{d}{dq}(280q - 4q^2) = 280 - 8q
$$

Notice that the slope of MR ( $-8$ ) is twice as steep as the demand curve’s slope ( $-4$ ). This is a property of linear demand curves: $MR = a - 2bq$  , where $p = a - bq$  .

---

### 5\. Profit-Maximizing Output and Price

Set $MR = MC$  to find the profit-maximizing quantity:

$$
280 - 8q = 6q
$$
 
$$
280 = 14q
$$
 
$$
q = \frac{280}{14} = 20
$$

Substitute $q = 20$  into the demand function to find the price:

$$
p^* = 280 - 4(20) = 280 - 80 = 200
$$

So, the monopolist produces 20 units and charges $200 per unit.

---

### 6\. Price Elasticity of Demand

**Price elasticity of demand ( $\epsilon$  )** measures how responsive quantity demanded is to a change in price:

$$
\epsilon = \frac{dq}{dp} \cdot \frac{p}{q}
$$
- It’s negative for a downward-sloping demand curve (price up, quantity down).
- Conventionally, we discuss its absolute value, but in formal calculations (and often in exam options), the sign is included.

From the demand function $q = 70 - \frac{p}{4}$  :

$$
\frac{dq}{dp} = -\frac{1}{4}
$$

At $p = 200$  , $q = 20$  :

$$
\epsilon = \left(-\frac{1}{4}\right) \cdot \frac{200}{20} = -\frac{1}{4} \cdot 10 = -2.5
$$

#### Interpretation

- $|\epsilon| = 2.5 > 1$  : Demand is **elastic** (quantity is relatively responsive to price changes).
- A monopolist always operates where $|\epsilon| > 1$  , because if $|\epsilon| < 1$  (inelastic), increasing price would increase revenue without losing much quantity, and profit could rise further.

---

### 7\. Verification with the Lerner Index

The **Lerner Index** measures market power:

$$
\frac{p - MC}{p} = -\frac{1}{\epsilon}
$$

Calculate MC at $q = 20$  :

$$
MC = 6(20) = 120
$$
 
$$
\frac{p - MC}{p} = \frac{200 - 120}{200} = \frac{80}{200} = 0.4
$$
 
$$
-\frac{1}{\epsilon} = 0.4
$$
 
$$
\epsilon = -\frac{1}{0.4} = -2.5
$$

This confirms our elasticity calculation.

---

### 8\. Additional Concepts for ISI MSQE Preparation

Here are other concepts you might encounter:

#### a. Types of Costs

- **Average Cost (AC)**: $AC = \frac{C}{q} = \frac{3q^2 + 800}{q} = 3q + \frac{800}{q}$
- **Average Variable Cost (AVC)**: $AVC = \frac{3q^2}{q} = 3q$
- **Average Fixed Cost (AFC)**: $AFC = \frac{800}{q}$

#### b. Profit Calculation

$$
\pi = TR - TC = (200 \cdot 20) - (3(20)^2 + 800) = 4000 - (1200 + 800) = 4000 - 2000 = 2000
$$

#### c. Elasticity and Revenue

- When $|\epsilon| > 1$  : Price decrease increases TR.
- When $|\epsilon| < 1$  : Price increase increases TR.
- At $|\epsilon| = 1$  : TR is maximized (not where monopolist operates).

#### d. Linear Demand Properties

For $p = a - bq$  :

- MR curve: $MR = a - 2bq$
- Elasticity varies: At $q = 0$  , $p = a$  , $\epsilon \to -\infty$  ; at $p = 0$  , $q = \frac{a}{b}$  , $\epsilon = 0$  .
- Midpoint: $q = \frac{a}{2b}$  , $p = \frac{a}{2}$  , $\epsilon = -1$  .

#### e. Welfare Analysis

- **Consumer Surplus**: Area above price, below demand curve, up to quantity sold.
- **Deadweight Loss**: Loss of efficiency due to monopoly pricing (compared to perfect competition where $p = MC$  ).

---

### 9\. Exam Tips

- **Derivations**: Be comfortable deriving MR, MC, and elasticity.
- **Formulas**: Memorize elasticity ( $\epsilon = \frac{dq}{dp} \cdot \frac{p}{q}$  ) and Lerner Index.
- **Graphs**: Sketch demand, MR, and MC curves to visualize.
- **Check Work**: Use multiple methods (e.g., direct calculation and Lerner Index) to verify.

---

### Conclusion

For the given example, the price elasticity of demand at the profit-maximizing price ( $p = 200$  , $q = 20$  ) is $-2.5$ , indicating elastic demand, consistent with monopoly behavior. Mastering these concepts—cost, revenue, profit maximization, and elasticity—will prepare you for ISI MSQE questions on monopolies and beyond. Practice with variations (e.g., non-linear demand, different cost structures) to build confidence!

welfare analysis question show me one

Here is a welfare analysis question involving a monopolist, complete with a detailed solution. This problem will help you understand how to compute consumer surplus, producer surplus, total welfare, and deadweight loss in both monopoly and socially optimal scenarios.

---

### Welfare Analysis Question

Consider a monopolist with the following cost and demand structures:

- **Total Cost Function**: $C = 3q^2 + 800$
- **Inverse Market Demand Function**: $p = 280 - 4q$

**Part A**: Find the profit-maximizing quantity and price for the monopolist.  
**Part B**: Calculate the consumer surplus, producer surplus, and total welfare at the monopoly equilibrium.  
**Part C**: Determine the socially optimal quantity and price (where marginal cost equals demand).  
**Part D**: Calculate the consumer surplus, producer surplus, and total welfare at the socially optimal point.  
**Part E**: Compute the deadweight loss due to the monopoly.

---

### Solution

#### Part A: Profit-Maximizing Quantity and Price

To find the monopolist’s profit-maximizing output, set marginal revenue (MR) equal to marginal cost (MC).

- **Marginal Cost (MC)**:
	$$
	C = 3q^2 + 800 \quad \Rightarrow \quad MC = \frac{dC}{dq} = 6q
	$$
- **Marginal Revenue (MR)**:  
	The inverse demand is $p = 280 - 4q$  . Total revenue (TR) is:
	$$
	TR = p \cdot q = (280 - 4q)q = 280q - 4q^2
	$$
	 
	$$
	MR = \frac{dTR}{dq} = 280 - 8q
	$$
- **Equate MR and MC**:
	$$
	280 - 8q = 6q
	$$
	 
	$$
	280 = 14q \quad \Rightarrow \quad q = 20
	$$
- **Price**:
	$$
	p = 280 - 4(20) = 280 - 80 = 200
	$$

**Result**: The monopolist produces $q_m = 20$  units at a price of $p_m = 200$  .

---

#### Part B: Welfare at Monopoly Equilibrium

- **Consumer Surplus (CS)**:  
	CS is the area above the price and below the demand curve up to $q = 20$  .
	- Demand intercept (when $q = 0$  ): $p = 280$  .
	- At $q = 20$  , $p = 200$  .
	- CS = Area of triangle = $\frac{1}{2} \times \text{base} \times \text{height}$  :
	$$
	CS = \frac{1}{2} \times 20 \times (280 - 200) = \frac{1}{2} \times 20 \times 80 = 800
	$$
- **Producer Surplus (PS)**:  
	PS is total revenue minus variable cost (fixed costs don’t affect surplus).
	- TR = $p \cdot q = 200 \times 20 = 4000$
	- Variable Cost = $3q^2 = 3(20)^2 = 3 \cdot 400 = 1200$
	- PS = $TR - VC = 4000 - 1200 = 2800$
- **Total Welfare (TW)**:
	$$
	TW = CS + PS = 800 + 2800 = 3600
	$$

**Result**: At monopoly equilibrium:

- CS = 800
- PS = 2800
- TW = 3600

---

#### Part C: Socially Optimal Quantity and Price

The socially optimal point occurs where price equals marginal cost ( $p = MC$  ), mimicking perfect competition.

- Set $p = MC$  :
	$$
	280 - 4q = 6q
	$$
	 
	$$
	280 = 10q \quad \Rightarrow \quad q = 28
	$$
- **Price**:
	$$
	p = 280 - 4(28) = 280 - 112 = 168
	$$

**Result**: Socially optimal quantity is $q_s = 28$  units at a price of $p_s = 168$  .

---

#### Part D: Welfare at Socially Optimal Point

- **Consumer Surplus (CS)**:
	- At $q = 28$  , $p = 168$  , demand intercept is 280.
	- CS = $\frac{1}{2} \times 28 \times (280 - 168) = \frac{1}{2} \times 28 \times 112 = 1568$
- **Producer Surplus (PS)**:  
	PS is the area above the MC curve and below the price $p = 168$  from $q = 0$  to $q = 28$  .
	- $MC = 6q$  , so PS = $\int_0^{28} (p - MC) \, dq = \int_0^{28} (168 - 6q) \, dq$
	- Compute:
	$$
	\left[ 168q - 3q^2 \right]_0^{28} = (168 \cdot 28 - 3 \cdot 28^2) - 0 = 4704 - 2352 = 2352
	$$
- **Total Welfare (TW)**:
	$$
	TW = CS + PS = 1568 + 2352 = 3920
	$$

Alternatively, TW is the area under the demand curve minus the area under the MC curve:

- $\int_0^{28} (280 - 4q) \, dq = \left[ 280q - 2q^2 \right]_0^{28} = 7840 - 1568 = 6272$
- $\int_0^{28} 6q \, dq = \left[ 3q^2 \right]_0^{28} = 2352$
- TW = $6272 - 2352 = 3920$  , which matches.

**Result**: At socially optimal equilibrium:

- CS = 1568
- PS = 2352
- TW = 3920

---

#### Part E: Deadweight Loss (DWL)

DWL is the loss in total welfare due to monopoly pricing compared to the socially optimal outcome.

- TW at monopoly = 3600
- TW at social optimum = 3920
- DWL = $3920 - 3600 = 320$

Alternatively, compute the area of the triangle between the demand and MC curves from $q = 20$  to $q = 28$  :

- At $q = 20$  , $p = 200$  , $MC = 6(20) = 120$
- At $q = 28$  , $p = 168$  , $MC = 168$
- DWL = $\int_{20}^{28} (280 - 4q - 6q) \, dq = \int_{20}^{28} (280 - 10q) \, dq$
- Compute:
	$$
	\left[ 280q - 5q^2 \right]_{20}^{28} = (7840 - 3920) - (5600 - 2000) = 3920 - 3600 = 320
	$$

**Result**: DWL = 320

---

### Summary

- **Monopoly Equilibrium**: $q_m = 20$  , $p_m = 200$ 
	- CS = 800
	- PS = 2800
	- TW = 3600
- **Socially Optimal Equilibrium**: $q_s = 28$  , $p_s = 168$ 
	- CS = 1568
	- PS = 2352
	- TW = 3920
- **Deadweight Loss**: 320

This problem demonstrates how monopoly pricing reduces total welfare compared to the socially optimal outcome, with the difference manifesting as deadweight loss. It’s a great example for practicing welfare analysis concepts! https://grok.com/chat/3fe9ccd4-2c4c-4c37-a50e-cb52c3cc15ff