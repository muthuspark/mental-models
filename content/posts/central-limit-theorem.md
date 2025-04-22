---
title: "Central limit theorem"
tags: ['numeracy and interpretation']
showTags: true
description: "When independent random variables are added together, their sum tends toward a normal distribution, even if the original variables are not normally distributed."
---


The world is a chaotic place, full of unpredictable events. But beneath the surface of randomness lies a powerful force: the **Central Limit Theorem**. This isn’t just a statistical concept; it's a fundamental mental model that helps us understand how patterns emerge from chaos. If you understand this, you'll be one step ahead in navigating everything from investing to understanding customer behavior.

### 1. What is Central Limit Theorem?

Simply put, the **Central Limit Theorem** (CLT) states: *When independent random variables are added together, their sum (or average) tends toward a normal distribution (the bell curve), even if the original variables are not normally distributed.*

Think of it like this: imagine you have a bunch of coins, each slightly biased – some are more likely to land on heads, some on tails. If you flip just one coin, the outcome is unpredictable and skewed. But if you flip all the coins together and average the results (the percentage of heads), the average result will tend toward 50% (a normal distribution) as you flip more and more coins, regardless of the individual biases.

**Where does it come from?** The CLT is a cornerstone of probability theory and statistics, with roots tracing back to the 18th century. Mathematicians like Abraham de Moivre and Pierre-Simon Laplace laid the groundwork, initially focusing on the normal approximation to the binomial distribution. Over time, its generality and importance were recognized across numerous scientific disciplines, from physics to economics to psychology. It isn't tied to one specific discipline; its power lies in its broad applicability to any scenario involving the aggregation of independent random variables.

### 2. How It Works: Unpacking the Magic

The **Central Limit Theorem** seems almost magical, but its magic comes from a few key components:

*   **Random Variables:** These are variables whose values are numerical outcomes of a random phenomenon. Think of rolling a die (the variable) and getting a number between 1 and 6 (the outcome).
*   **Independence:** This means the variables don't influence each other. The outcome of one roll of the die doesn't affect the next. This is a crucial assumption!
*   **Sample Size:** The CLT works best when you have a sufficiently large sample of these random variables. The larger the sample, the closer the distribution of the sample means will be to a normal distribution.

**Analogy:** Imagine you're building a wall with bricks. Each brick is slightly different in size and shape (representing our non-normal random variables). If you only use a few bricks, your wall will be wonky. But if you use thousands of bricks, the errors in the individual bricks will average out, and your wall will be relatively straight and uniform – approaching a "normal" wall, if you will.

**Diagram:**
```
[Original Distributions (can be anything: uniform, skewed, bimodal)] --> [Taking many samples of size 'n' from each distribution] --> [Calculating the mean of each sample] --> [Distribution of Sample Means (tends to normal as 'n' increases)]
```

### 3. Examples of the Model in Action

Let's see the **Central Limit Theorem** in action:

*   **Business: Customer Spending:** Suppose you own an online store. Individual customer spending habits are all over the place – some buy a lot, some buy very little. The distribution of individual spending may be highly skewed. However, if you track the *average* spending per customer each month over a year, the distribution of those monthly averages will likely resemble a normal distribution. This is because each monthly average is essentially the sum of many individual, independent spending decisions. This allows you to forecast future revenue with greater confidence.

*   **Investing: Stock Market Returns:** Daily or even weekly stock market returns are often noisy and unpredictable, not following a clear pattern. However, if you calculate the *average* monthly return over several years, the distribution of these averages will tend toward a normal distribution. This allows investors to use statistical tools, built on the assumption of normality, to assess risk and make investment decisions. Note: while the CLT can help, it doesn't eliminate the risks of investing, especially in situations with low sample sizes or non-independent variables!

*   **Personal Life: Sleep Patterns:** Let's say your daily sleep duration is quite variable due to factors like stress, late nights, and early mornings. The distribution of your sleep time might be irregular. However, if you calculate your *average* sleep duration over a year, the distribution of these yearly averages across multiple years will start to approximate a normal distribution. This helps you see your overall sleep patterns over time, even with daily variations.

### 4. Common Misunderstandings or Pitfalls

The **Central Limit Theorem** is powerful, but understanding its limitations is just as important:

*   **Normality of Individual Variables:** A common misconception is that the original variables need to be normally distributed for the CLT to work. This is incorrect! The beauty of the CLT is that it applies *even if* the underlying variables are not normal.
*   **Independence Assumption:** The CLT relies heavily on the assumption that the random variables are independent. If the variables are correlated (e.g., stock prices tend to move together), the theorem may not hold.
*   **Sample Size Matters:** The CLT works best with large sample sizes. How "large" depends on the shape of the original distribution. If the original distribution is very skewed, you'll need a larger sample size for the sample means to converge to a normal distribution. There is no magic number for the perfect sample size.

### 5. How to Apply It in Daily Life

How can you use the **Central Limit Theorem** in your daily life?

*   **Think in Averages:** Focus on averages over time, rather than individual data points. Don’t get hung up on a single bad day at work or a single poor investment decision. Look at the overall trend.
*   **Consider Sample Size:** Be aware of the limitations of small sample sizes. A few data points are rarely enough to draw meaningful conclusions. Strive to collect more data before making decisions.
*   **Ask: Are the Variables Independent?** Before applying the CLT, think critically about whether the variables you're analyzing are truly independent. If there's a significant correlation, the CLT may not be applicable.
*   **Forecast with Caution:** Use the CLT to make predictions, but always remember that it's based on probabilities, not certainties. There will always be some degree of error in your predictions.

### 6. Related Mental Models

The **Central Limit Theorem** is strengthened by other mental models:

*   **Law of Large Numbers:** This states that as a sample size grows, its mean will get closer and closer to the average of the entire population. The CLT explains *how* this mean tends to be distributed (normally).
*   **Regression to the Mean:** Extreme events tend to be followed by events closer to the average. The CLT reinforces this idea because averages are more stable than individual events.
*   **Second-Order Thinking:** The **Central Limit Theorem** encourages second-order thinking. It tells us that the distribution of *averages* is different than the distribution of the *individual* events that comprise the average.

By understanding the **Central Limit Theorem**, you gain a powerful tool for navigating uncertainty and making informed decisions. You'll start to see patterns where others see only randomness, and you'll be better equipped to predict the future – or at least understand the odds.

