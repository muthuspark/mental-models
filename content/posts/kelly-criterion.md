---
title: "Kelly criterion"
tags: ['numeracy and interpretation']
showTags: true
description: "A formula for determining optimal bet size when the odds are in your favor, balancing growth rate against risk of ruin."
---


The world is full of uncertainties, but sometimes, we encounter opportunities where the odds are tilted in our favor. The challenge then becomes: how much should we risk to maximize our gains without blowing everything up? Enter the **Kelly criterion**, a powerful mental model for determining optimal bet size, striking a balance between aggressive growth and the dreaded risk of ruin.

### 1. What is the Kelly Criterion?

The **Kelly criterion** is a formula that tells you the optimal percentage of your capital to allocate to a bet or investment when you have an edge. In essence, it's a mathematical guide to "how much to bet" when the odds are in your favor, maximizing your long-term growth while managing risk.

Imagine you have a coin that lands heads 60% of the time. If you bet 100% of your money on heads every time, you'll win a lot sometimes, but eventually, the tails will catch up and wipe you out. The Kelly criterion helps you find the sweet spot – the bet size that grows your capital fastest without risking it all.

The model originated from information theory, developed by John L. Kelly Jr. at Bell Labs in 1956. He was trying to solve a problem for long-distance telephone signal transmission, but its application quickly extended to gambling and investment. While seemingly mathematical, its core principles apply far beyond casinos and trading floors.

### 2. How It Works

The basic formula for the **Kelly criterion** is surprisingly simple:

**Kelly % = Edge / Odds**

Let's break down these components:

*   **Edge (b):** This is your "profitability" or the advantage you have. It's the probability of winning multiplied by the profit if you win, minus the probability of losing multiplied by the cost if you lose.
*   **Odds (a):** This represents the winnings you receive relative to the amount wagered. If you bet $1 to win $2, the odds are 2 to 1.

**Think of it like this:**

Imagine a farm. You have land (your capital). The Kelly criterion helps you decide how much seed (your bet size) to plant in a particular field (your investment opportunity).

*   **Edge:** How fertile is the soil? How likely is it to rain? How good is the seed? These factors determine your expected yield.
*   **Odds:** How much grain do you get back for each seed you plant? A high yield means a higher reward.

The Kelly criterion helps you determine the optimal amount of seed to plant to maximize your harvest over the long run, without over-planting and depleting your resources (risking ruin).

**A more complex formula is often used when the odds are more complicated:**

**f* = (bp - q) / b**

Where:

*   **f*:** The fraction of capital to be bet
*   **b:** The net odds received on the wager (e.g., a bet of $100 that pays $200 back has net odds of 1)
*   **p:** The probability of winning
*   **q:** The probability of losing (1 - p)

### 3. Examples of the Model in Action

Let's look at some examples of the **Kelly criterion** in action:

*   **Investing:** A stock market analyst believes a specific stock has a 60% chance of increasing in value by 20% over the next year. If the stock decreases, they expect a 10% loss. Using the formula `f* = (bp - q) / b`, where b is 0.2 (20% gain), p is 0.6, and q is 0.4, the Kelly percentage would be approximately 13.3%. This suggests allocating roughly 13.3% of your investment portfolio to this stock.

*   **Business Decisions:** A company is considering launching a new product. Market research suggests a 70% chance of success, leading to a 50% increase in annual revenue. However, failure would result in a 20% decrease in revenue. Using the Kelly Criterion, the company can estimate how much of their resources to allocate to this project. If using the simplified formula, the Edge = (0.7 * 0.5) - (0.3 * 0.2) = 0.29. If the odds are 1 to 1 (invest $X to gain $X), the Kelly % is 29%.

*   **Skill-based game (Poker):** Suppose you're playing poker and know you have a 70% chance of winning a pot that currently has $100 in it. Your opponent is considering a $50 bet. Should you call? Using the Kelly Criterion, if you call and win, you get the $50 bet + the original $100, and if you lose, you lose the $50. Calculating with the more complex formula, `f* = (bp - q) / b`, where b = (100/50) = 2, p=0.7 and q = 0.3, the optimal bet size becomes 20%.

### 4. Common Misunderstandings or Pitfalls

Applying the **Kelly criterion** isn't always straightforward, and some common pitfalls can lead to problems:

*   **Overestimating Your Edge:** The biggest mistake is believing you have a larger advantage than you actually do. Be brutally honest about your probabilities. Overconfidence can lead to ruin.
*   **Ignoring Transaction Costs:** The formula doesn't account for transaction costs like brokerage fees or taxes. These costs eat into your profits and reduce your edge.
*   **Volatility and Drawdowns:** Even with a positive edge, you'll experience periods of losses. The Kelly criterion can still lead to significant swings in your capital, which can be emotionally difficult. **Consider fractional Kelly.** Using a fraction of the Kelly-determined bet size (e.g., half-Kelly) can significantly reduce volatility.
*   **Not Suitable for All Situations:** The Kelly Criterion is best suited for situations with well-defined probabilities and outcomes. It may not be applicable to highly uncertain or unpredictable scenarios.
*   **Single Event vs. Repeated Bets:** The Kelly Criterion is designed for *repeated* bets. A single, high-stakes bet where failure is catastrophic isn't the right application.

### 5. How to Apply It in Daily Life

You don't need to be a professional gambler to benefit from the **Kelly criterion**. Here's how to integrate its principles into your daily decision-making:

*   **Assess Your Edge:** Before committing to anything (a project, an investment, a new skill), realistically evaluate your chances of success and the potential rewards. Are you truly better positioned than others, or are you just optimistic?
*   **Calculate the Potential Downside:** What's the worst-case scenario? How much could you lose? Can you afford it?
*   **Start Small and Iterate:** Don't bet the farm on your first attempt. Begin with a small allocation, track your results, and adjust your strategy as you learn more. Think of it as running experiments.
*   **Embrace "Fractional Kelly":** If the calculated percentage seems too aggressive, especially early on, reduce it. Half-Kelly or quarter-Kelly can help you manage risk and learn more conservatively.
*   **Question your assumptions:** Regularly review and reassess your edge. Are your initial assumptions still valid? Has the market changed? Staying flexible is crucial.

### 6. Related Mental Models

The **Kelly criterion** works well in conjunction with other mental models:

*   **Margin of Safety (Value Investing):** This encourages buying assets at a significant discount to their intrinsic value, creating a buffer against errors in your estimations, similar to the Kelly criterion's risk management.
*   **Expected Value:** The Kelly criterion builds upon the concept of expected value by determining not just *whether* a bet is profitable, but *how much* to bet.
*   **Compounding:** The Kelly criterion aims to maximize the rate of compounding over the long run. Understanding compounding helps appreciate the long-term benefits of optimal bet sizing.
*   **Risk/Reward Ratio:** Kelly criterion helps optimize risk/reward to achieve faster growth.

By understanding and applying the **Kelly criterion**, you can make more informed decisions, maximize your long-term growth, and avoid the pitfalls of overconfidence and excessive risk. It's not a magic formula for instant riches, but a powerful tool for navigating the uncertainties of life with greater clarity and precision.

