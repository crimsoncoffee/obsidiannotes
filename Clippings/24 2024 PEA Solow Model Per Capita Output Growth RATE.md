---
title: "Solow Model: Per Capita Output Growth - Grok"
source: "https://grok.com/chat/2ae810ee-3a18-4a03-a58a-fc7323878238"
author:
published:
created: 2025-04-07
description: "Grok is a free AI assistant designed by xAI to maximize truth and objectivity. Grok offers real-time search, image generation, trend analysis, and more."
tags:
  - "clippings"
---
Refer to the following content:image.png

To determine the current growth rate of per capita output in the given Solow economy, we proceed as follows:

### Step 1: Understand the Model

We are given a Solow economy with the production function in intensive form:

$y = k^{\frac{1}{2}}$

where:

- $y$  is per capita output,
- $k$  is the capital-labor ratio.

Additional conditions:

- There is no capital depreciation ( $\delta = 0$  ),
- The labor force grows at a rate $n > 0$  ,
- The steady-state capital-labor ratio is $k^* = 50$  ,
- The current capital-labor ratio is $k = 2$  .

Our goal is to find the current growth rate of per capita output, $g_y = \frac{\dot{y}}{y}$  .

### Step 2: Relate the Growth Rates

Since $y = k^{\frac{1}{2}}$  , we need to express the growth rate of $y$  in terms of the growth rate of $k$  . Using the production function:

$y = k^{\frac{1}{2}}$

Taking the natural logarithm:

$\ln y = \frac{1}{2} \ln k$

Differentiating with respect to time:

$\frac{\dot{y}}{y} = \frac{1}{2} \frac{\dot{k}}{k}$

Thus, the growth rate of per capita output is:

$g_y = \frac{\dot{y}}{y} = \frac{1}{2} g_k$

where $g_k = \frac{\dot{k}}{k}$  is the growth rate of the capital-labor ratio. We need to compute $g_k$  at the current $k = 2$  .

### Step 3: Capital Accumulation Equation

In the Solow model, the evolution of the capital-labor ratio is governed by:

$\dot{k} = s y - (n + \delta) k$

Since there is no depreciation ( $\delta = 0$  ):

$\dot{k} = s y - n k$

Substitute the production function $y = k^{\frac{1}{2}}$  :

$\dot{k} = s k^{\frac{1}{2}} - n k$

The growth rate of $k$  is:

$g_k = \frac{\dot{k}}{k} = s \frac{k^{\frac{1}{2}}}{k} - n = s k^{-\frac{1}{2}} - n$

We need the savings rate $s$  and the current value of $k$  to find $g_k$  .

### Step 4: Determine the Savings Rate Using Steady State

In the steady state, $\dot{k} = 0$  , and $k = k^* = 50$  . Thus:

$s y^* = n k^*$

Since $y^* = (k^*)^{\frac{1}{2}}$  :

$y^* = 50^{\frac{1}{2}} = \sqrt{50}$

So:

$s \sqrt{50} = n \cdot 50$

Solve for $s$  :

$s = \frac{n \cdot 50}{\sqrt{50}} = n \cdot \frac{50}{50^{\frac{1}{2}}} = n \cdot 50^{1 - \frac{1}{2}} = n \cdot 50^{\frac{1}{2}} = n \sqrt{50}$

### Step 5: Compute the Growth Rate of k k at Current k=2 k = 2

Now substitute $s = n \sqrt{50}$  and $k = 2$  into the expression for $g_k$  :

$g_k = s k^{-\frac{1}{2}} - n$

$k^{-\frac{1}{2}} = 2^{-\frac{1}{2}} = \frac{1}{\sqrt{2}}$

$s k^{-\frac{1}{2}} = (n \sqrt{50}) \cdot \frac{1}{\sqrt{2}} = n \frac{\sqrt{50}}{\sqrt{2}} = n \sqrt{\frac{50}{2}} = n \sqrt{25} = 5n$

Thus:

$g_k = 5n - n = 4n$

### Step 6: Compute the Growth Rate of y y

Using the relationship derived earlier:

$g_y = \frac{1}{2} g_k = \frac{1}{2} \cdot 4n = 2n$

So, the current growth rate of per capita output at $k = 2$  is $2n$  .

### Step 7: Verify the Calculation

Let’s compute $\dot{k}$  directly to confirm:

$\dot{k} = s k^{\frac{1}{2}} - n k$

$k^{\frac{1}{2}} = 2^{\frac{1}{2}} = \sqrt{2}$

$s k^{\frac{1}{2}} = (n \sqrt{50}) \cdot \sqrt{2} = n \sqrt{50 \cdot 2} = n \sqrt{100} = 10n$

$n k = n \cdot 2 = 2n$

$\dot{k} = 10n - 2n = 8n$

$g_k = \frac{\dot{k}}{k} = \frac{8n}{2} = 4n$

This matches our previous result. Then:

$g_y = \frac{1}{2} \cdot 4n = 2n$

The calculations are consistent.

### Step 8: Compare with Options

The options provided are:

- (A) $24n$
- (B) $\frac{25}{n}$
- (C) 0.3
- (D) None of the previous options

Our result, $g_y = 2n$  , does not match:

- $24n$  (option A),
- $\frac{25}{n}$  (option B), which has different units and dependency on $n$  ,
- 0.3 (option C), a constant, whereas $2n$  depends on $n$  .

Since $2n$  is not listed among options (A), (B), or (C), the correct choice is:

**D. None of the previous options**

could we have don without using the logarithms

Yes, we can derive the growth rate of per capita output without using logarithms. Here’s a clear and complete explanation of how to do it:

### Starting Point: The Production Function

Suppose we have a production function that relates per capita output $y$  to the capital-labor ratio $k$  :

$y = k^{\frac{1}{2}}$

This means that per capita output is the square root of the capital-labor ratio.

### Goal: Find the Growth Rate of Per Capita Output

The growth rate of per capita output, denoted $g_y$  , is defined as the rate of change of $y$  over time, relative to its current value:

$g_y = \frac{\dot{y}}{y}$

where $\dot{y} = \frac{dy}{dt}$  is the time derivative of $y$  .

### Step 1: Compute the Time Derivative of y y

Since $y = k^{\frac{1}{2}}$  , and $k$  changes over time, we use the chain rule to find $\dot{y}$  :

$\dot{y} = \frac{d}{dt} \left( k^{\frac{1}{2}} \right) = \frac{1}{2} k^{-\frac{1}{2}} \dot{k}$

Here, $\dot{k} = \frac{dk}{dt}$  is the time derivative of the capital-labor ratio.

### Step 2: Express the Growth Rate gy g\_y

Substitute $\dot{y}$  into the growth rate formula:

$g_y = \frac{\dot{y}}{y} = \frac{ \frac{1}{2} k^{-\frac{1}{2}} \dot{k} }{ k^{\frac{1}{2}} }$

Simplify the expression by handling the exponents:

$g_y = \frac{1}{2} \cdot \frac{\dot{k}}{ k^{-\frac{1}{2}} \cdot k^{\frac{1}{2}} } = \frac{1}{2} \cdot \frac{\dot{k}}{ k^{-\frac{1}{2} + \frac{1}{2}} } = \frac{1}{2} \cdot \frac{\dot{k}}{k^0} = \frac{1}{2} \cdot \frac{\dot{k}}{k}$

Since $\frac{\dot{k}}{k}$  is the growth rate of the capital-labor ratio, denoted $g_k$  , we have:

$g_y = \frac{1}{2} g_k$

This shows that the growth rate of per capita output is half the growth rate of the capital-labor ratio, derived without logarithms.

### Step 3: Relate gk g\_k to the Economic Model

To find $g_y$  in a specific context (like the Solow growth model), we need $g_k$  . The evolution of $k$  is given by the capital accumulation equation. Assuming no depreciation ( $\delta = 0$  ), it is:

$\dot{k} = s y - n k$

where:

- $s$  is the savings rate,
- $n$  is the population growth rate,
- $y = k^{\frac{1}{2}}$  is the per capita output.

Substitute $y$  :

$\dot{k} = s k^{\frac{1}{2}} - n k$

Then, the growth rate of $k$  is:

$g_k = \frac{\dot{k}}{k} = \frac{s k^{\frac{1}{2}} - n k}{k} = s k^{\frac{1}{2} - 1} - n = s k^{-\frac{1}{2}} - n$

### Example: Compute gy g\_y at a Specific Point

Suppose we want $g_y$  when $k = 2$  , and we know from the steady state ( $\dot{k} = 0$  at $k^* = 50$  ) that:

$s (50)^{\frac{1}{2}} = n \cdot 50$

$s \sqrt{50} = 50 n$

$s = \frac{50 n}{\sqrt{50}} = n \sqrt{50}$

Now, at $k = 2$  :

$\dot{k} = (n \sqrt{50}) \cdot 2^{\frac{1}{2}} - n \cdot 2$

$= n \sqrt{50} \cdot \sqrt{2} - 2n = n \sqrt{100} - 2n = 10n - 2n = 8n$

$g_k = \frac{\dot{k}}{k} = \frac{8n}{2} = 4n$

$g_y = \frac{1}{2} g_k = \frac{1}{2} \cdot 4n = 2n$

### Conclusion

The growth rate of per capita output at $k = 2$  is $2n$  , calculated using differentiation and algebra, without logarithms. This method relies on the chain rule and the definitions of growth rates, proving that logarithms are not necessary.

at first i did not know how the growth rate would come as here there was nothing to do with time. How could I have intuitively come to take those derivatives to get the growth rate

I understand that at first glance, it might seem unclear why we’re taking derivatives or how time fits into finding the growth rate, especially if it feels like time isn’t explicitly involved. Let me walk you through how you can intuitively approach this to see why derivatives come up and how they lead to the growth rate of per capita output, $y$  , when $y = k^{1/2}$  .

### Step 1: Recognize That Growth Implies Change Over Time

The term "growth rate" naturally suggests something is changing, and in economics, especially in models like the Solow growth model, that change happens over time. Even if time isn’t explicitly written in the production function $y = k^{1/2}$  , it’s implied because $k$  (capital per worker) evolves as the economy progresses. So, $y$  (output per worker) depends on $k$  , and since $k$  changes over time, $y$  must also change over time. The growth rate of $y$  is defined as $\frac{\dot{y}}{y}$  , where $\dot{y} = \frac{dy}{dt}$  , the rate of change of $y$  with respect to time. This is our target: how fast $y$  is growing relative to its current value.

### Step 2: Connect y y to k k and Introduce Time

Since $y = k^{1/2}$  is a function of $k$  , and $k$  itself depends on time (i.e., $k = k(t)$  ), $y$  indirectly depends on time through $k$  . To find how $y$  changes over time, we need to compute $\dot{y}$  , the time derivative of $y$  . This is where intuition can guide us: because $y$  is tied to $k$  , any change in $k$  over time will cause $y$  to change. The tool to link these changes is the **chain rule** from calculus, which applies when you have a composite function like $y(k(t))$  .

Using the chain rule:

- If $y = f(k)$  and $k = k(t)$  , then $\dot{y} = \frac{dy}{dt} = \frac{dy}{dk} \cdot \frac{dk}{dt} = f'(k) \cdot \dot{k}$  .
- Here, $f(k) = k^{1/2}$  , so the derivative with respect to $k$  is:
	$$
	f'(k) = \frac{d}{dk} (k^{1/2}) = \frac{1}{2} k^{-1/2}
	$$
- Thus, $\dot{y} = \frac{1}{2} k^{-1/2} \cdot \dot{k}$  , where $\dot{k} = \frac{dk}{dt}$  is the rate of change of $k$  over time.

This makes sense intuitively: the change in $y$  over time depends on how sensitive $y$  is to $k$  (captured by $\frac{dy}{dk}$  ) and how fast $k$  itself is changing (captured by $\dot{k}$  ).

### Step 3: Form the Growth Rate

The growth rate is the relative change, $\frac{\dot{y}}{y}$  , so substitute what we have:

- $\dot{y} = \frac{1}{2} k^{-1/2} \cdot \dot{k}$
- $y = k^{1/2}$

Thus:

$$
\frac{\dot{y}}{y} = \frac{\frac{1}{2} k^{-1/2} \cdot \dot{k}}{k^{1/2}}
$$

Simplify the expression:

- $\frac{k^{-1/2}}{k^{1/2}} = k^{-1/2 - 1/2} = k^{-1} = \frac{1}{k}$
- So, $\frac{\dot{y}}{y} = \frac{1}{2} \cdot \frac{\dot{k}}{k}$

This is a key result! The growth rate of $y$  is half the growth rate of $k$  . Intuitively, this happens because $y$  is the square root of $k$  , and the square root grows more slowly than a linear function. A 1% increase in $k$  doesn’t lead to a 1% increase in $y$  ; it’s scaled down by the exponent $\frac{1}{2}$  .

### Step 4: Why Derivatives? An Intuitive Nudge

You might wonder, "Why did I need derivatives here?" Think of it this way:

- **Growth is about rates of change.** In everyday terms, if you’re tracking how fast your savings grow, you’d look at the change over time relative to what you have. That’s $\frac{\dot{y}}{y}$  .
- **Time is hidden in the dynamics.** Even though $y = k^{1/2}$  doesn’t mention time, the question about growth rate implies we’re in a dynamic system (like an economy) where variables evolve. Derivatives capture that evolution.
- **Proportional changes connect variables.** Since $y$  depends on $k$  , we use the derivative $\frac{dy}{dk}$  to measure how a change in $k$  affects $y$  , then adjust for time with $\dot{k}$  .

For power functions like $y = k^\alpha$  , there’s a handy pattern: the growth rate of $y$  is always $\alpha$  times the growth rate of $k$  . Here, $\alpha = \frac{1}{2}$  , so $\frac{\dot{y}}{y} = \frac{1}{2} \cdot \frac{\dot{k}}{k}$  . This is a shortcut you can lean on once you’re comfortable with the idea.

### Step 5: Making It Concrete (Optional Context)

To go further, $\frac{\dot{k}}{k}$  comes from the model’s dynamics (e.g., in the Solow model, $\dot{k} = s y - n k$  , where $s$  is the savings rate and $n$  is population growth). But the core intuition—using derivatives—doesn’t need that yet. You start by seeing $y$  as a function of $k$  , expecting $k$  to change over time, and then use calculus to track how those changes ripple through to $y$  .

### Putting It Together

Here’s how you could have intuitively arrived at this:

1. **Spot the dependency:** $y$  depends on $k$  , so if $k$  grows, $y$  must grow too.
2. **Think dynamically:** Growth rates mean change over time, even if time isn’t in the equation explicitly.
3. **Reach for the chain rule:** Since $y$  changes through $k$  , and $k$  changes with time, connect them with $\frac{dy}{dt} = \frac{dy}{dk} \cdot \frac{dk}{dt}$  .
4. **Relate proportionally:** Divide by $y$  to get the growth rate, and simplify using the function’s form.
5. **Trust the pattern:** For $y = k^{1/2}$  , the $\frac{1}{2}$  exponent hints that $y$  ’s growth is half of $k$  ’s.

So, the derivatives come naturally once you see growth as a process unfolding over time, with $k$  driving $y$  , and calculus giving you the tools to measure it precisely. https://grok.com/chat/2ae810ee-3a18-4a03-a58a-fc7323878238