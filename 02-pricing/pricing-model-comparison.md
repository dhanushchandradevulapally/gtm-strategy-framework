# Pricing Model Comparison Framework

## Model Definitions

### 1. Freemium
**Description:** Free tier with limited features; paid tiers unlock functionality.

| Pros | Cons |
|------|------|
| Low friction; viral potential | Low conversion (2-5%) |
| Large top-of-funnel | High support cost on free users |
| Network effects possible | Feature cannibalization risk |

**Best For:** Consumer tools, developer tools, collaboration software

---

### 2. Tiered (Seat-Based)
**Description:** Fixed packages at different price points. Customers choose tier based on features needed.

| Pros | Cons |
|------|------|
| Predictable revenue | Seat sprawl; underutilization |
| Simple to communicate | Misaligned with value |
| Easy sales process | Expansion requires negotiation |

**Best For:** Traditional B2B SaaS, team collaboration tools

---

### 3. Usage-Based
**Description:** Pay for what you use. Metered billing based on consumption.

| Pros | Cons |
|------|------|
| Aligned with customer value | Revenue unpredictability |
| Low entry barrier | Customer anxiety about bills |
| Natural expansion | Complex billing infrastructure |

**Best For:** Infrastructure, API products, data processing

---

### 4. Hybrid (Progressive Usage)
**Description:** Tiered plans with usage caps + overage billing. Best of both worlds.

| Pros | Cons |
|------|------|
| Predictable base + expansion | More complex to communicate |
| Aligned incentives | Requires usage monitoring |
| Low entry + high ceiling | Billing system complexity |

**Best For:** AI/ML tools, automation platforms, support software

---

## Decision Matrix

Evaluate your product against these criteria:

| Criterion | Weight | Freemium | Tiered | Usage | Hybrid |
|-----------|--------|----------|--------|-------|--------|
| Ease of adoption | 20% | 10 | 7 | 8 | 8 |
| Revenue predictability | 20% | 3 | 9 | 4 | 8 |
| Expansion potential | 20% | 5 | 6 | 10 | 9 |
| Competitive differentiation | 15% | 6 | 5 | 7 | 8 |
| Implementation complexity | 15% | 7 | 8 | 4 | 5 |
| Customer alignment | 10% | 6 | 5 | 10 | 9 |

**Score each model 1-10 for your specific product, multiply by weight, sum for total.**

## Recommendation Logic

```
IF (network_effects = high AND consumer_orientation = high):
    CHOOSE Freemium

IF (team_collaboration = true AND seat_based_value = true):
    CHOOSE Tiered

IF (infrastructure_or_api = true AND variable_usage = true):
    CHOOSE Usage-Based

IF (ai_or_automation = true AND land_and_expand = true):
    CHOOSE Hybrid (Recommended)
```
