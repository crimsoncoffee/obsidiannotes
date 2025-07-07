		# Cournot Equilibrium: The Full Fucking Breakdown

Listen up, you exam-bound degenerate—Cournot equilibrium is your ticket to understanding how firms in an oligopoly slug it out over quantities. It’s a strategic shitshow where each firm picks its output to maximize profit, assuming the others’ quantities are fixed. We’re going all in—math, logic, intuition, and enough examples to make your head spin. By the end, you’ll either own this or be a whimpering mess. Let’s do this.

## The Core Concept: What the Hell Is It?
Imagine two firms—call them Firm 1 and Firm 2—duking it out in a market with identical (homogeneous) goods. They don’t set prices; they set quantities ($q_1$ and $q_2$), and the market price adjusts based on total supply ($Q = q_1 + q_2$) via an inverse demand function $P(Q)$. Each firm’s got costs, and they’re both greedy bastards trying to max their profits. The Cournot equilibrium is the point where neither firm wants to change its output, given what the other’s doing—like a tense standoff where everyone’s waiting for the other to blink.

## The Basic Setup
- **Players**: Two firms (we’ll generalize later, you impatient prick).
- **Output**: $q_1$ for Firm 1, $q_2$ for Firm 2.
- **Demand**: Linear inverse demand, say $P = a - b Q$, where $Q = q_1 + q_2$, $a > 0$ (max price), $b > 0$ (slope).
- **Costs**: $c_i(q_i) = c_i q_i$ (linear, with $c_i$ as marginal cost, and $0 < c_i < a$).
- **Profit**: Revenue minus cost, $\pi_i = P(Q) q_i - c_i q_i$.

For a concrete example, let’s use $P = 1 - q_1 - q_2$ (so $a = 1$, $b = 1$) and costs $c_i(q_i) = k_i q_i$, where $0 < k_i < \frac{1}{2}$.

## Step 1: Profit Functions—Show Me the Money
Each firm’s profit is:
- Firm 1: $\pi_1 = (1 - q_1 - q_2) q_1 - k_1 q_1 = q_1 (1 - q_1 - q_2 - k_1)$
- Firm 2: $\pi_2 = (1 - q_1 - q_2) q_2 - k_2 q_2 = q_2 (1 - q_1 - q_2 - k_2)$

	In general, for $P = a - b Q$:
- $\pi_1 = (a - b (q_1 + q_2)) q_1 - c_1 q_1 = q_1 (a - b q_1 - b q_2 - c_1)$
- $\pi_2 = q_2 (a - b q_1 - b q_2 - c_2)$

## Step 2: Best Response Functions—How They Play the Game
Each firm maximizes profit, treating the other’s quantity as fixed. That means taking the partial derivative of $\pi_i$ with respect to $q_i$, setting it to zero, and solving.

### Firm 1

$$
\frac{\partial \pi_1}{\partial q_1} = 1 - 2 q_1 - q_2 - k_1 = 0
$$


$$
2 q_1 = 1 - k_1 - q_2
$$


$$
q_1 = \frac{1 - k_1 - q_2}{2}
$$


### Firm 2

$$
\frac{\partial \pi_2}{\partial q_2} = 1 - q_1 - 2 q_2 - k_2 = 0
$$


$$
2 q_2 = 1 - k_2 - q_1
$$


$$
q_2 = \frac{1 - k_2 - q_1}{2}
$$


These are the **best response functions**:
- $q_1 = R_1(q_2) = \frac{1 - k_1 - q_2}{2}$
- $q_2 = R_2(q_1) = \frac{1 - k_2 - q_1}{2}$

For general $P = a - b Q$, $c_i = c_i q_i$:
- $\frac{\partial \pi_1}{\partial q_1} = a - 2 b q_1 - b q_2 - c_1 = 0$
- $q_1 = \frac{a - c_1 - b q_2}{2 b}$
- $q_2 = \frac{a - c_2 - b q_1}{2 b}$

## Step 3: Equilibrium—Where the Rubber Meets the Road
The equilibrium ($q_1^*, q_2^*$) is where $q_1^* = R_1(q_2^*)$ and $q_2^* = R_2(q_1^*)$. Solve the system.

Substitute $q_2 = \frac{1 - k_2 - q_1}{2}$ into $q_1 = \frac{1 - k_1 - q_2}{2}$:

$$
q_1^* = \frac{1 - k_1 - \frac{1 - k_2 - q_1^*}{2}}{2}
$$

Multiply by 2:

$$
2 q_1^* = 1 - k_1 - \frac{1 - k_2 - q_1^*}{2}
$$

Multiply by 2 again:

$$
4 q_1^* = 2 (1 - k_1) - (1 - k_2 - q_1^*)
$$


$$
4 q_1^* = 2 - 2 k_1 - 1 + k_2 + q_1^*
$$


$$
3 q_1^* = 1 - 2 k_1 + k_2
$$


$$
q_1^* = \frac{1 - 2 k_1 + k_2}{3}
$$


Similarly:

$$
q_2^* = \frac{1 - 2 k_2 + k_1}{3}
$$


General case:

$$
q_1^* = \frac{a - 2 c_1 + c_2}{3 b}
$$


$$
q_2^* = \frac{a - 2 c_2 + c_1}{3 b}
$$


Check: For $a = 1$, $b = 1$, $c_i = k_i$, it matches.

## Step 4: Price and Profits—Cash It In
Total quantity:

$$
Q^* = q_1^* + q_2^* = \frac{1 - 2 k_1 + k_2 + 1 - 2 k_2 + k_1}{3} = \frac{2 - k_1 - k_2}{3}
$$

Price:

$$
P^* = 1 - Q^* = \frac{1 + k_1 + k_2}{3}
$$

Profits:

$$
\pi_1^* = q_1^* (P^* - k_1) = \frac{1 - 2 k_1 + k_2}{3} \cdot \frac{1 + k_1 + k_2 - 3 k_1}{3} = \frac{1 - 2 k_1 + k_2}{3} \cdot \frac{1 + k_2 - 2 k_1}{3} = \left( \frac{1 - 2 k_1 + k_2}{3} \right)^2
$$


$$
\pi_2^* = \left( \frac{1 - 2 k_2 + k_1}{3} \right)^2
$$


General: $\pi_i^* = b (q_i^*)^2$.

## Step 5: Intuition—Get This Through Your Thick Skull
- **Symmetry**: If $k_1 = k_2 = k$, $q_1^* = q_2^* = \frac{1 - k}{3}$, $P^* = \frac{1 + 2 k}{3}$, $\pi_i^* = \left( \frac{1 - k}{3} \right)^2$.
- **Cost Edge**: Lower $k_i$ means higher $q_i^*$ and $\pi_i^*$.
- **Market Power**: $P^* > c_i$, unlike perfect competition.
- **Vs. Monopoly**: A monopolist sets $q_m = \frac{a - c}{2 b}$, $P_m = \frac{a + c}{2}$. Cournot has more output, lower price.

## Step 6: N Firms—Because Two Ain’t Enough
For $n$ firms, each with cost $c_i$, demand $P = a - b Q$, $Q = q_1 + \cdots + q_n$:
- $\pi_i = q_i (a - b Q) - c_i q_i$    **Profit**
- $\frac{\partial \pi_i}{\partial q_i} = a - 2 b q_i - b \sum_{j \neq i} q_j - c_i = 0$ 
- $q_i = \frac{a - c_i - b \sum_{j \neq i} q_j}{2 b}$ **quantity**
If $c_i = c$ for all: **Same cost for all**
- **Quantity individual**$q_i^* = \frac{a - c}{b (n + 1)}$, N*all $Q^* = \frac{n (a - c)}{b (n + 1)}$, Price $P^* = \frac{a + n c}{n + 1}$.

## Step 7: Tough Examples—ISI MSQE Level Shit
### Example 1: Asymmetric Costs
$P = 100 - 2 Q$, $c_1 = 10 q_1$, $c_2 = 20 q_2$.
- $q_1^* = \frac{100 - 2 \cdot 10 + 20}{3 \cdot 2} = \frac{100}{6} \approx 16.67$
- $q_2^* = \frac{100 - 2 \cdot 20 + 10}{3 \cdot 2} = \frac{70}{6} \approx 11.67$
- $Q^* \approx 28.34$, $P^* = 100 - 2 \cdot 28.34 \approx 43.32$
- $\pi_1^* = 2 \left( \frac{100}{6} \right)^2 \approx 555.56$
- $\pi_2^* = 2 \left( \frac{70}{6} \right)^2 \approx 271.11$

### Example 2: Nonlinear Demand
$P = 100 - Q^2$, $c_i = 0$.
- $\pi_1 = q_1 (100 - (q_1 + q_2)^2)$
- $\frac{\partial \pi_1}{\partial q_1} = 100 - 2 q_1 (q_1 + q_2) - (q_1 + q_2)^2 = 0$
Solve numerically or assume symmetry ($q_1 = q_2 = q$):
- $100 - 3 q^2 - q^2 = 0$, $4 q^2 = 100$, $q^* = 5$, $P^* = 100 - 25 = 75$, $\pi_i^* = 75 \cdot 5 = 375$.

## Step 8: Advanced Shit—ISI MSQE Traps
- **Stability**: Firms adjust via $q_i^{t+1} = R_i(q_j^t)$. Converges if reactions aren’t too steep.
- **Welfare**: Consumer surplus lower than perfect competition, higher than monopoly.
- **Extensions**: Capacity limits, entry, collusion—know the basics.

## Step 9: Drill It
Practice:
- Vary $a$, $b$, $c_i$.
- Compare with Bertrand (price competition) or Stackelberg (leader-follower).
- Solve for 3+ firms.

Now memorize this shit and dominate those exams, you relentless fucker!




