---
title: "Simpson's paradox"
tags: ['numeracy and interpretation']
showTags: true
description: "A statistical phenomenon where a trend appears in separate groups of data but disappears or reverses when the groups are combined."
---


Have you ever heard something that sounds logical, but then crumbles under closer examination? That's often the work of our biases and assumptions. Today, we're diving into a fascinating mental model called **Simpson's Paradox**, a statistical trickster that can lead you to completely the wrong conclusions if you're not careful.

**1. What is Simpson's Paradox?**

**Simpson's Paradox** is a statistical phenomenon where a trend appears in *separate* groups of data, but that trend disappears – or even reverses – when you *combine* those groups. Essentially, what looks true on the surface for individual segments might not be true for the whole population.

The name comes from Edward H. Simpson, who first described this phenomenon in a technical paper in 1951. While Simpson formalized it, related statistical discrepancies were noted earlier in different contexts. It pops up primarily in fields that deal with large datasets and statistical analysis like economics, healthcare, and social sciences.

**2. How It Works**

Imagine two baseball teams, the Sluggers and the Homers. Let's say over the first half of the season:

*   **The Sluggers** improve their batting average from .240 to .260.
*   **The Homers** *also* improve their batting average, from .280 to .300.

Logically, you might conclude that both teams got better at hitting, right? Makes sense!

But what if we break down the data by month? It turns out the Sluggers played mostly against weak pitchers in the second half of the season and the Homers played against strong ones.

Here's the paradox:

| Team      | Pitchers Faced      | First Half Batting Avg. | Second Half Batting Avg. |
|-----------|-----------------------|-------------------------|-------------------------|
| Sluggers  | Weak Pitchers       | .240                    | .260                    |
| Homers    | Strong Pitchers      | .280                    | .300                    |

**Combined:** The Homers still have a better batting average overall (.290 avg) compared to the Sluggers (.250 avg).

**Individually:** Both teams improved.

See how the combined data can be misleading? That's Simpson's Paradox in action. The overall trend (Homers are better) hides the individual trends (both teams improved). A lurking variable (the strength of the pitchers) affected the combined data, and that's where the combined conclusion can be misleading.

A simple framework:
*   **Segment:** Data divided into meaningful groups.
*   **Trend within Segments:** Identify the trend (positive or negative) in each segment.
*   **Overall Trend:** What happens when you combine the data?
*   **The Paradox:** Does the overall trend contradict the trends within segments?

**3. Examples of the Model in Action**

*   **Kidney Stone Treatment:** Doctors compare two treatments for kidney stones. Treatment A seems to have a *lower* success rate overall than Treatment B. However, when they break down the data by the size of the stones, Treatment A actually has a *higher* success rate for both small and large stones! The paradox arises because Treatment A is disproportionately used on larger, more difficult stones.

*   **Gender Pay Gap:** A company analyzes its salary data and finds that *overall*, women earn less than men. However, when they break down the data by job title and experience level, women and men earn roughly the same amount *within* each category. The paradox might be due to women being underrepresented in higher-paying roles or having less seniority on average.

*   **College Admissions:** University X appears to have a lower acceptance rate than University Y. But, when you break it down by major, University X's acceptance rate is *higher* for *every single major*! This can happen if University X receives many more applicants for its highly competitive majors, creating a lower overall rate despite being more selective within each department.

**4. Common Misunderstandings or Pitfalls**

*   **Assuming Simpler is Better:** The combined data *isn't inherently wrong*. The point of the paradox is that the combined data can be misleading if you don't understand the underlying factors and how they're distributed across the segments.
*   **Ignoring Confounding Variables:** Failing to identify and account for confounding variables (like the severity of kidney stones or the level of experience) that might be influencing the relationship.
*   **Over-Simplifying Causation:** Jumping to conclusions about cause and effect without considering the full picture. Just because a trend disappears or reverses doesn't mean there's no relationship – it means the relationship is more complex than it appears.

**5. How to Apply It in Daily Life**

Here's how you can arm yourself against **Simpson's Paradox** in your daily life:

*   **Always Break Down Data:** When presented with aggregate data, ask yourself if it makes sense to break it down into smaller, more specific groups.
*   **Look for Lurking Variables:** Consider what other factors might be influencing the data besides the ones being presented. Ask "What are we not seeing here?"
*   **Don't Trust Averages Blindly:** Averages can be useful, but they can also mask important underlying trends. Dig deeper!
*   **Question Assumptions:** Challenge your own assumptions about the relationships between variables. Are you making any implicit assumptions that might be wrong?
*   **Embrace Complexity:** Recognize that many real-world situations are complex, and simple explanations are often incomplete or misleading.

**6. Related Mental Models**

*   **Correlation vs. Causation:** This model reminds us that correlation doesn't equal causation. Just because two things appear to be related doesn't mean one causes the other. **Simpson's Paradox** can highlight spurious correlations.
*   **First Principles Thinking:** This model encourages you to break down complex problems into their fundamental elements. By understanding the underlying factors, you can avoid being misled by surface-level trends.
*   **Occam's Razor:** This principle states that the simplest explanation is usually the best. However, with **Simpson's Paradox**, the *simplest* explanation based on aggregate data might be completely wrong.
*   **Base Rate Fallacy:** The Base Rate Fallacy occurs when people put too much emphasis on individual information instead of overall information. Being aware of the Base Rate Fallacy helps avoid errors by considering how often something normally happens.

By understanding and applying **Simpson's Paradox**, you can become a more critical thinker, make better decisions, and avoid being fooled by misleading statistics. Now, go forth and dissect those averages!

