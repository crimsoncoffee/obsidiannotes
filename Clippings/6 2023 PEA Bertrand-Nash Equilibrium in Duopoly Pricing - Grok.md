---
title: "Bertrand-Nash Equilibrium in Duopoly Pricing - Grok"
source: "https://grok.com/chat/660f47b9-22d9-4aa2-9c10-30e58498b39b"
author:
published:
created: 2025-04-03
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
Refer to the following content:image.png

To determine the Bertrand-Nash equilibrium prices for the two firms in this market, we need to analyze the given demand function, cost structure, and demand allocation rules, considering the firms' strategic pricing decisions. Let's proceed step-by-step.

### Market Setup

The market demand function is:

$p = 100 - q$

where $p$  is the market price and $q = q_1 + q_2$  is the total quantity demanded, with $q_1$  and $q_2$  being the outputs of firm 1 and firm 2, respectively. Inverting this, the total quantity demanded as a function of price is:

$q = 100 - p$

Each firm has a cost function:

$$
\begin{cases} 
0 & \text{if } q_i \leq 10 \\
\infty & \text{if } q_i > 10 
\end{cases}
$$

for $i = 1, 2$  . This implies a capacity constraint: each firm can produce up to 10 units at zero cost but cannot produce more than 10 units.

The firms compete by simultaneously setting prices $p_1$  and $p_2$  . The demand for firm $i$  , denoted $D_i(p_1, p_2)$  , depends on the relative prices:

- If $p_i < p_j$  (where $j \neq i$  ), then $D_i(p_1, p_2) = 100 - p_i$
- If $p_i = p_j$  , then $D_i(p_1, p_2) = \frac{100 - p_i}{2}$
- If $p_i > p_j$  , then $D_i(p_1, p_2) = 0$

However, due to the capacity constraint, the actual quantity sold by firm $i$  is limited to:

$q_i = \min(D_i(p_1, p_2), 10)$

Profit for firm $i$  is then:

$\pi_i = p_i \cdot q_i = p_i \cdot \min(D_i(p_1, p_2), 10)$

since the cost is zero up to 10 units. In a Bertrand-Nash equilibrium, each firm chooses its price to maximize profit, given the other firm's price, and neither has an incentive to deviate unilaterally.

### Analyzing the Equilibrium

In standard Bertrand competition with homogeneous goods and no capacity constraints, firms undercut each other until price equals marginal cost (here, zero), resulting in $p_1 = p_2 = 0$  . However, the capacity constraint of 10 units per firm alters this outcome, as each firm cannot supply the entire market demand alone (e.g., at $p = 0$  , $q = 100$  , but each firm's capacity is only 10).

Let's consider a symmetric equilibrium where both firms set the same price, $p_1 = p_2 = p$  , and examine the options provided: (a) (0, 0), (b) (80, 80), (c) (20, 20), and (d) (90, 90).

#### Case: p1=p2=p p\_1 = p\_2 = p

- **Demand per firm**: $D_i(p, p) = \frac{100 - p}{2}$
- **Quantity sold**: $q_i = \min\left( \frac{100 - p}{2}, 10 \right)$
- **Profit**: $\pi_i = p \cdot \min\left( \frac{100 - p}{2}, 10 \right)$

Determine the threshold where capacity binds: $\frac{100 - p}{2} = 10$  $100 - p = 20$  $p = 80$

- If $p < 80$  , then $\frac{100 - p}{2} > 10$  , so each firm sells 10 units, and profit is $\pi_i = p \cdot 10$  .
- If $p = 80$  , then $\frac{100 - 80}{2} = 10$  , so each sells 10 units, and profit is $\pi_i = 80 \cdot 10 = 800$  .
- If $p > 80$  , then $\frac{100 - p}{2} < 10$  , so each sells $\frac{100 - p}{2}$  , and profit is $\pi_i = p \cdot \frac{100 - p}{2}$  .

#### Option (b): (p1,p2)=(80,80) (p\_1, p\_2) = (80, 80)

- Each firm sells: $\frac{100 - 80}{2} = 10$  units (exactly at capacity).
- Profit: $80 \cdot 10 = 800$  .
- **Deviation check**:
	- **Undercut**: If firm 1 sets $p_1 = 79 < 80$  , then $D_1 = 100 - 79 = 21 > 10$  , so it sells 10 units, profit = $79 \cdot 10 = 790 < 800$  . No incentive to undercut.
	- **Raise price**: If firm 1 sets $p_1 = 81 > 80$  , then $D_1 = 0$  (since $p_1 > p_2$  ), profit = 0 < 800. No incentive to raise price.
- Conclusion: Neither firm deviates; $(80, 80)$  is an equilibrium.

#### Option (c): (p1,p2)=(20,20) (p\_1, p\_2) = (20, 20)

- Demand per firm: $\frac{100 - 20}{2} = 40 > 10$  , so each sells 10 units.
- Profit: $20 \cdot 10 = 200$  .
- **Deviation check**:
	- **Undercut**: If firm 1 sets $p_1 = 19 < 20$  , then $D_1 = 100 - 19 = 81 > 10$  , sells 10 units, profit = $19 \cdot 10 = 190 < 200$  . No incentive to undercut.
	- **Raise price**: If firm 1 sets $p_1 = 21 > 20$  , then $D_1 = 0$  , profit = 0 < 200. No incentive to raise price.
- Conclusion: This is also an equilibrium, but profit (200) is lower than at (80, 80).

#### Option (a): (p1,p2)=(0,0) (p\_1, p\_2) = (0, 0)

- Demand per firm: $\frac{100 - 0}{2} = 50 > 10$  , so each sells 10 units.
- Profit: $0 \cdot 10 = 0$  .
- **Deviation check**:
	- If firm 1 sets $p_1 = 1 > 0$  , then $D_1 = 0$  , profit = 0 (no gain). Undercutting below 0 is not feasible (assuming non-negative prices). However, profit is minimal, and higher prices like 80 yield more profit without capacity fully satisfying demand at $p = 0$  (total supply = 20 < 100).
- Conclusion: Possible equilibrium, but not profit-maximizing.

#### Option (d): (p1,p2)=(90,90) (p\_1, p\_2) = (90, 90)

- Demand per firm: $\frac{100 - 90}{2} = 5 < 10$  , so each sells 5 units.
- Profit: $90 \cdot 5 = 450$  .
- **Deviation check**:
	- If firm 1 sets $p_1 = 89 < 90$  , then $D_1 = 100 - 89 = 11 > 10$  , sells 10 units, profit = $89 \cdot 10 = 890 > 450$  . Incentive to undercut exists.
- Conclusion: Not an equilibrium.

### Residual Demand Consideration

If $p_1 < p_2$  and $100 - p_1 > 10$  , firm 1 sells 10 units, and firm 2 gets $D_2 = 0$  per the demand rule, implying no residual demand goes to firm 2. This simplifies the analysis, as unsatisfied demand is lost rather than served by the higher-priced firm.

### Equilibrium Selection

For $p \leq 80$  , symmetric prices $(p, p)$  can be equilibria, as undercutting reduces profit (e.g., at $p = 20$  , deviating to 19 yields less), and raising price yields zero demand. Profit is $10p$  , maximized at $p = 80$  (profit = 800). At $p = 80$  , total supply (20) equals demand (100 - 80 = 20), clearing the market efficiently. Higher prices like $p = 90$  are unstable due to undercutting incentives.

### Final Answer

The Bertrand-Nash equilibrium, maximizing profit while stable, is:

**(b) (80, 80)**

How to approach these sort of questions in ISI MSQE context and what are the essential things to remember to ace

To approach questions related to microeconomic concepts like Bertrand competition with capacity constraints in the ISI MSQE exam context, and to ace them, you need a structured strategy and a firm grasp of key principles. The ISI MSQE is renowned for its rigorous testing of game theory, industrial organization, and market structures, so here’s how you can tackle such questions effectively, along with the essential things to remember.

### How to Approach These Questions

1. **Identify the Market Structure**  
	Start by recognizing the type of competition in the problem. For instance, in a Bertrand competition model, firms set prices simultaneously, and typically, the firm with the lower price captures the entire market. However, capacity constraints introduce a twist—each firm’s supply is limited, which alters the standard outcome where prices equal marginal cost. Understanding this framework is your first step.
2. **Break Down Demand and Costs**  
	Analyze the demand function (e.g., linear demand like $Q = a - bP$  ) and cost structure (e.g., zero costs up to capacity). This helps you determine how much each firm can supply and how pricing affects demand allocation. With capacity constraints, firms aim to maximize sales up to their limit, but their pricing must account for the competitor’s strategy.
3. **Look for Symmetric Equilibrium**  
	In many Bertrand models with symmetric firms (same capacities, costs), a natural starting point is to check if both firms setting the same price forms an equilibrium. Calculate the resulting demand and supply at this price, ensuring it aligns with capacity constraints, and verify if neither firm benefits from deviating.
4. **Profit Maximization and Incentives**  
	For each firm, compute profits ( $\text{Profit} = Price \times Quantity$  ) based on their price and the demand they capture, capped by their capacity. Test whether a firm can increase profits by slightly raising or lowering its price. In Bertrand competition, undercutting is tempting, but capacity limits may make it unprofitable if the price drop doesn’t increase market share beyond capacity.
5. **Market Clearing Price**  
	Find a price where total supply (sum of capacities) equals total demand, if possible. This is often a candidate for equilibrium in capacity-constrained models, as it balances the market without excess supply or demand.
6. **Handle Undercutting and Residual Demand**  
	If one firm sets a lower price, it typically captures the market up to its capacity, leaving no demand for the higher-priced firm (unless the problem specifies otherwise). Check if undercutting leads to a stable outcome or triggers a price war, considering capacity limits.
7. **Evaluate Options Systematically**  
	For multiple-choice questions, test each price option. Plug it into the demand function, allocate quantities based on capacities, and check if firms have no incentive to deviate. Eliminate options where a firm could profitably adjust its price.
8. **Graphical or Intuitive Checks**  
	Sketching the demand curve or profit functions can clarify how prices affect quantities and profits, especially when capacities constrain supply. This visual aid can confirm your analytical findings.

### Essential Things to Remember to Ace These Questions

- **Master Game Theory Fundamentals**  
	Understand Nash equilibrium (where no firm can improve profits by unilaterally changing its price) and best response functions (a firm’s optimal price given the competitor’s price). These concepts are the backbone of ISI MSQE microeconomics problems.
- **Practice Variations**  
	Solve problems with twists like capacity constraints, differentiated products, or asymmetric costs. The ISI MSQE often tests your ability to adapt standard models to unique scenarios.
- **Focus on Stability**  
	Ensure the equilibrium you identify is stable—small price changes shouldn’t unravel it. For example, if undercutting leads to a cycle of price reductions, it’s not a Nash equilibrium.
- **Capacity Utilization**  
	Pay attention to whether firms operate at full capacity in equilibrium. In Bertrand models with constraints, prices may settle above marginal cost if demand exceeds total capacity, unlike the standard zero-profit outcome.
- **Time Management**  
	These questions can be complex and time-intensive. Practice solving them quickly by identifying key steps (e.g., equilibrium conditions, profit checks) to stay within exam limits.
- **Learn from Past Papers**  
	Review previous ISI MSQE exams to grasp the question style, difficulty, and common themes. Familiarity with their approach boosts confidence and efficiency.
- **Profit Comparison**  
	If multiple equilibria exist, the one yielding higher profits or efficiently clearing the market is often preferred. Check which aligns with the problem’s context.

### Putting It Together

For a question like Bertrand competition with capacity constraints, you’d:

1. Define the model (price-setting, capacity limits).
2. Use the demand function and capacities to find a candidate equilibrium price.
3. Test if firms sell at capacity and have no incentive to deviate.
4. Compare with options or derive the price analytically, ensuring it’s stable and profit-maximizing.

By combining this structured approach with a deep understanding of game theory and market dynamics, and by practicing diligently, you’ll be well-equipped to excel in the ISI MSQE’s microeconomics section.

specific to above topic and all the related questions

Below is a detailed explanation of how to approach questions related to **Bertrand competition with capacity constraints**, tailored specifically for the **ISI MSQE (Indian Statistical Institute Master of Science in Quantitative Economics) exam** context. I'll also highlight the essential things to remember to excel in these types of questions. This response assumes a microeconomics focus, as Bertrand competition is a key topic in the exam's game theory and industrial organization sections.

---

## Understanding Bertrand Competition with Capacity Constraints

In the standard **Bertrand competition model**, firms compete by setting prices simultaneously, and the firm with the lowest price captures the entire market demand, assuming it can supply it. Prices are typically driven down to marginal cost due to intense price competition. However, when **capacity constraints** are introduced, each firm can only produce up to a fixed quantity (say, $k$  units), regardless of the price they set. This limitation fundamentally alters the pricing strategy and equilibrium outcomes, making it a nuanced and exam-relevant twist.

### Key Setup

- **Market Demand**: Often given as a linear function, e.g., $Q = a - bP$  , where $Q$  is total quantity demanded, and $P$  is the market price. For simplicity, assume $Q = 100 - P$  .
- **Firms**: Typically, a duopoly with two identical firms, each with a capacity constraint $k$  .
- **Costs**: Marginal cost is usually zero up to capacity $k$  , and infinite beyond it, simplifying profit to $\text{Profit} = P \times Q$  where $Q \leq k$  .
- **Demand Allocation**:
	- If $P_1 < P_2$  , Firm 1 (lower price) serves demand up to $k$  , and Firm 2 serves any residual demand.
	- If $P_1 = P_2$  , they split the demand equally, each supplying up to $\min\left(\frac{Q}{2}, k\right)$  .

The objective is to find the **Bertrand-Nash equilibrium**, where each firm sets a price that maximizes its profit given the other firm's price, and neither has an incentive to deviate unilaterally.

---

## Step-by-Step Approach to Solving These Questions

Here’s a structured method to tackle Bertrand competition questions with capacity constraints in the ISI MSQE exam:

### 1\. Identify the Market Structure

- Confirm that the problem involves Bertrand competition with capacity constraints. This means firms set prices, but their supply is capped, distinguishing it from Cournot (quantity competition) or standard Bertrand models.

### 2\. Analyze Demand and Costs

- **Demand Function**: Understand how price determines total demand. For $Q = 100 - P$  , demand decreases as price increases.
- **Cost Structure**: With zero marginal cost up to $k$  , profit depends solely on price and quantity sold, capped at capacity.

### 3\. Assume Symmetric Equilibrium

- Since firms are often identical, start with $P_1 = P_2 = P$  .
- At equal prices, demand is split: each firm faces $\frac{100 - P}{2}$  , but can only supply up to $k$  .
- Quantity sold per firm = $\min\left(\frac{100 - P}{2}, k\right)$  .

### 4\. Find the Capacity-Binding Price

- Determine the price where split demand equals capacity:
	$$
	\frac{100 - P}{2} = k
	$$
	 
	$$
	100 - P = 2k \quad \Rightarrow \quad P = 100 - 2k
	$$
- At $P = 100 - 2k$  :
	- Total demand = $100 - (100 - 2k) = 2k$  .
	- Each firm supplies $k$  , so total supply = $2k$  , matching demand exactly (market clears).

### 5\. Verify Nash Equilibrium

- **At $P_1 = P_2 = 100 - 2k$** :
	- Profit per firm = $P \times k = (100 - 2k) \times k$  .
- **Check Deviations**:
	- **Undercut**: If Firm 1 sets $P_1' < 100 - 2k$  , it captures the entire demand at $P_1'$  , i.e., $100 - P_1' > 2k$  , but can only supply $k$  . Profit = $P_1' \times k$  . Since $P_1' < 100 - 2k$  , profit $P_1' \times k < (100 - 2k) \times k$  , so undercutting reduces profit.
	- **Raise Price**: If Firm 1 sets $P_1'' > 100 - 2k$  , Firm 2 (at $100 - 2k$  ) captures demand up to $k$  . Residual demand at $P_1''$  may be zero if $2k \geq 100 - P_1''$  , or Firm 1 serves less, but typically, it gets zero demand in Bertrand settings when priced higher. Profit = 0, which is worse than $(100 - 2k) \times k$  .
- No incentive to deviate, so $P_1 = P_2 = 100 - 2k$  is an equilibrium.

### 6\. Explore Other Equilibria

- For $P < 100 - 2k$  , each firm still sells $k$  (since $\frac{100 - P}{2} > k$  ), but profits are lower. However, no firm undercuts further (reduces profit) or raises price (loses demand), suggesting a range of equilibria, with $100 - 2k$  maximizing profits.
- If $2k \geq 100$  (large capacity), prices may drop to marginal cost (0), reverting to standard Bertrand.

### 7\. Handle Residual Demand and Market Clearing

- At $P = 100 - 2k$  , if $2k < 100$  (capacity less than maximum demand), the market clears efficiently. For larger $k$  , adjust based on problem specifics.

### 8\. Evaluate Options (for MCQs)

- In multiple-choice questions, test each price pair (e.g., (80,80), (20,20)) by calculating profits and checking deviation incentives, ensuring consistency with capacity and demand.

---

## Essential Things to Remember

To ace Bertrand competition questions with capacity constraints in the ISI MSQE exam, keep these points in mind:

- **Master Nash Equilibrium**: Ensure no firm benefits from unilateral price changes. This is the cornerstone of game-theoretic solutions.
- **Capacity Limits Drive Outcomes**: Prices stay above marginal cost because firms can’t supply the entire market, unlike standard Bertrand.
- **Symmetric Prices**: For identical firms, $P = 100 - 2k$  (adjusted for the demand function) is often the equilibrium where capacity binds.
- **Undercutting Trade-Off**: Undercutting increases demand but not supply beyond $k$  , often lowering profit due to a lower price.
- **Market Clearing**: The equilibrium price often balances total capacity and demand (e.g., $2k = 100 - P$  ).
- **Profit Precision**: Compute $P \times \min(\text{demand}, k)$  accurately, accounting for capacity constraints.
- **Time Efficiency**: Practice identifying the capacity-binding price quickly to save time in the exam.
- **Model Variations**: Be ready for asymmetric capacities, different costs, or demand functions—adapt the approach accordingly.
- **Stability Check**: Confirm the equilibrium holds under small price perturbations.
- **Past Papers**: Analyze previous ISI MSQE questions to gauge complexity and question styles.

---

## Summary

To tackle **Bertrand competition with capacity constraints** in the ISI MSQE exam:

1. Understand the model: price competition with supply limits.
2. Follow a systematic approach: define demand/costs, find symmetric prices, verify equilibrium.
3. Focus on key insights: capacity prevents price wars to zero, and equilibrium prices reflect market clearing.

By mastering this structured method and internalizing the essential points, you’ll confidently solve these questions and excel in the microeconomics section. Practice with sample problems (e.g., $Q = 100 - P$  , $k = 20$  ) to solidify your skills! https://grok.com/chat/660f47b9-22d9-4aa2-9c10-30e58498b39b