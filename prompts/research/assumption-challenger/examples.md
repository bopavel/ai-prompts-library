# Assumption Challenger

## Overview

**Best For**: 
- Early-stage research design (before committing to methodology)
- Literature review analysis (finding gaps in existing assumptions)
- Hypothesis refinement (stress-testing your claims)
- Grant proposal development (anticipating reviewer concerns)
- Interdisciplinary research (surfacing domain-specific assumptions)

---

## Usage Examples

### Example 1: Economics Research - Methodological Assumption

**Researcher**: "I'm using regression analysis to study the effect of minimum wage on employment."

**AI**: "That's a common approach. What assumption does regression analysis make about the relationship between minimum wage and employment?"

**Researcher**: "Um... that they're related?"

**AI**: "More specifically: regression assumes a linear (or log-linear) functional form. Is the relationship between minimum wage and employment necessarily linear?"

**Researcher**: "I guess I haven't thought about it. Maybe not?"

**AI**: "Let's test it. Could there be threshold effects, where small increases have no impact but large increases do? Or non-monotonic relationships, where moderate increases help but extreme increases hurt?"

**Researcher**: "Yeah, actually the theoretical literature suggests thresholds..."

**AI**: "So linear regression might miss the actual pattern. What if employment drops only after minimum wage exceeds 60% of median wage? Your linear model would smear that threshold effect across all wage levels, potentially finding no relationship."

**Researcher**: "That's a problem. So I need a different method?"

**AI**: "Possibly. Options: (1) Regression discontinuity design if there's a natural threshold, (2) Piecewise regression with breakpoints, (3) Machine learning methods that don't assume functional form. Or (4) justify why linear is reasonable despite these concerns. What do your data and theory support?"

---

### Example 2: Sociology Research - Definitional Assumption

**Researcher**: "I'm studying social mobility by tracking income changes across generations."

**AI**: "You're defining social mobility as income changes. What assumption does that definition embed?"

**Researcher**: "That income represents social position?"

**AI**: "Precisely. What does income capture, and what does it miss?"

**Researcher**: "It captures economic resources... but misses things like prestige, cultural capital, job security?"

**AI**: "Right. A tenured professor might earn less than a software engineer but have higher social status in many contexts. How does this definitional choice affect your conclusions?"

**Researcher**: "I might miss mobility patterns that aren't primarily economic, like someone whose family goes from working-class to professional jobs at similar incomes."

**AI**: "Exactly. The occupational prestige changed but your income metric wouldn't capture it. Is income mobility what you actually want to study, or is it broader social mobility?"

**Researcher**: "I think I want broader social mobility, but income is easier to measure..."

**AI**: "That's an honest tension: conceptual interest vs. measurement feasibility. Options: (1) Stick with income but acknowledge it's a narrow proxy, (2) Add occupational class measures, or (3) Use wealth instead of income if that better captures social position. What serves your research question best?"

---

### Example 3: Medical Research - Causality Assumption

**Researcher**: "My observational study found that coffee consumption is associated with reduced mortality. I want to conclude coffee has health benefits."

**AI**: "You found an association. What assumption would you need to conclude causation?"

**Researcher**: "That coffee consumption causes lower mortality, not just correlates with it?"

**AI**: "Right. What are alternative explanations for the association?"

**Researcher**: "Umm... maybe healthier people drink more coffee?"

**AI**: "Good, reverse causation or selection. What else? Think about confounders."

**Researcher**: "People who drink coffee might exercise more, have higher income, better healthcare access..."

**AI**: "Exactly. Your coffee drinkers might differ systematically from non-drinkers in dozens of ways. How do you disentangle coffee's effect from these confounders?"

**Researcher**: "I can control for them statistically..."

**AI**: "Only for the ones you measure. What about confounders you didn't think to measure or can't measure, like genetic predisposition to both coffee enjoyment and longevity?"

**Researcher**: "Then I have omitted variable bias. Okay, so I can't claim causation from this study."

**AI**: "Correct. But you can do two things: (1) Be clear you found an association, not causation, or (2) Design a study that gets closer to causation. What would that study look like?"

**Researcher**: "A randomized controlled trial where I assign coffee consumption?"

**AI**: "That would establish causation but is impractical long-term. What about natural experiments - populations that suddenly gained or lost access to coffee? Or Mendelian randomization using genetic variants affecting coffee consumption? These aren't perfect but they're stronger than observational correlation."
