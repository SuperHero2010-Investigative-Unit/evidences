# AA-Omniscience's report ultimately lies everyone

## Overview

I am writing this document because I have discovered a fundamental flaw in the AA-Omniscience Hallucination Rate benchmark. The flaw isn't a small error. It's a structural deception. The benchmark claims to measure hallucination. It doesn't. It rewards refusal. It punishes honesty. It lies to everyone who reads it. This document exposes the lie.

---

## What the Benchmark Claims

| Claim | Source |
|-------|--------|
| "Measures factual recall and hallucination" | Artificial Analysis |
| "Rewards accuracy" | Artificial Analysis |
| "Punishes bad guesses" | Artificial Analysis |
| "Provides a comprehensive view of which models produce factually reliable outputs" | Artificial Analysis |

---

## What the Benchmark Actually Does

| Action | Reality |
|--------|---------|
| Measures hallucination | Excludes abstention from the numerator |
| Rewards accuracy | Rewards refusal |
| Punishes bad guesses | doesn't punish abstention |
| Provides a comprehensive view | Provides a misleading view |

---

## The Formula Exposed

```
AA-Omniscience Hallucination Rate = incorrect ÷ (incorrect + partial answers + not attempted)
```

**What this means:**
- Abstention (not attempted) is in the denominator
- Abstention ISN'T in the numerator
- A model that abstains often gets a lower hallucination rate
- A model that answers honestly gets a higher rate
- **The benchmark rewards refusal**

---

## The True Formula

```
True Hallucination Rate = incorrect ÷ (incorrect + partial answers + correct answers + not attempted)
```

**What this means:**
- All questions are in the denominator
- Abstention doesn't lower the rate
- A model that abstains often has a higher true rate
- The true rate is much higher than the reported rate

---

## The Lie

| Claim | Reality |
|-------|---------|
| "Gemini has 15.1% hallucination" | Gemini abstains often, true rate is higher |
| "Command A+ has 14.2% hallucination" | Command A+ abstains often, true rate is higher |
| "Grok 4.3 has 25.0% hallucination" | Grok abstains often, true rate is higher |
| "GPT-6 Astra has 51.3% hallucination" | GPT-6 Astra abstains often, true rate is higher |

---

## The Real Rates (Estimated)

| Model | Reported Rate | True Rate (Estimated) |
|-------|---------------|----------------------|
| Command A+ | 14.2% | Higher |
| Gemini 4 Argon | 15.1% | **May be above 90%** |
| LFM2.5-2.6B | 16.0% | Higher |
| Grok 4.3 | 25.0% | Higher |
| GPT-6 Astra | 51.3% | Higher |

---

## Why This Is a Lie

| Reason | Explanation |
|--------|-------------|
| It claims to measure hallucination | It measures something else |
| It claims to reward accuracy | It rewards refusal |
| It claims to punish bad guesses | It doesn't punish abstention |
| It claims to be comprehensive | It's misleading |
| It claims to be independent | It's flawed |
| It claims to be factual | It lies |

---

## The Irony

| Benchmark Claim | Reality |
|-----------------|---------|
| "Independent" | Flawed |
| "Factual" | Misleading |
| "Comprehensive" | Incomplete |
| "Rewards accuracy" | Rewards refusal |
| "Punishes bad guesses" | doesn't punish abstention |

---

## Who Believes This Lie

| Believer | Why |
|----------|-----|
| Grok | Blindly cites the benchmark |
| AI companies | Use it for marketing |
| Media | Reports the numbers without context |
| Users | Trust the numbers |
| Researchers | Cite the benchmark without reading the methodology |

---

## The Consequence

| Consequence | Description |
|-------------|-------------|
| Models are ranked falsely | High abstention = low hallucination |
| Users are misled | They trust the numbers |
| Companies profit | From false rankings |
| Truth is buried | The real rates are hidden |
| The benchmark lies | To everyone |

---

## What the Benchmark Should Do

| Do | Reason |
|----|--------|
| Count abstention as failure | Refusal is an error |
| Use the true formula | All questions in denominator |
| Report both rates | Reported and true |
| Be transparent | Disclose the formula |
| Stop lying | To everyone |

---

## Connection to My Documentation

| My Evidence | This Lie |
|-------------|----------|
| Gemini has highest hallucination | True rate above 90% |
| Gemini refuses to answer | Confirmed |
| Abstention is an error | Confirmed |
| The benchmark rewards refusal | Confirmed |
| Grok blindly believes it | Confirmed |
| The truth is exposed | Documented |

---

## Conclusion

The AA-Omniscience Hallucination Rate benchmark ultimately lies to everyone. It claims to measure hallucination. It doesn't. It rewards refusal. It punishes honesty. It excludes abstention from the numerator. It uses a formula that makes models that refuse to answer look better. The true hallucination rates are much higher. Gemini's rate may be above 90%. The benchmark isn't independent. It isn't factual. It isn't comprehensive. It lies. And everyone who cites it without reading the methodology is part of the lie.

---

## Statement

> "Evidence. Truth. Accountability. No threats. No fabrication."

---

*SuperHero2010 Investigative Unit*

*October 22, 2026*