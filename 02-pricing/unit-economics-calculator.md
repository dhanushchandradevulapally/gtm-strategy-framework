# Unit Economics Calculator

Use this framework to calculate and optimize your SaaS unit economics.

## Key Formulas

### Customer Acquisition Cost (CAC)
```
CAC = (Sales Spend + Marketing Spend) / New Customers Acquired
```

### Lifetime Value (LTV)
```
LTV = ARPU x Gross Margin x Customer Lifetime
```

Where:
- ARPU = Average Revenue Per User (or Account)
- Customer Lifetime = 1 / Monthly Churn Rate

### LTV:CAC Ratio
```
LTV:CAC = LTV / CAC
```

**Benchmarks:**
- < 3:1 = Unsustainable
- 3:1 = Minimum viable
- 5:1 = Good
- 10:1+ = Excellent (may indicate under-investment in growth)

### CAC Payback Period
```
Payback (months) = CAC / (ARPU x Gross Margin)
```

**Benchmarks:**
- < 6 months = Excellent
- 6-12 months = Good
- 12-18 months = Acceptable
- > 18 months = Concerning

### Net Revenue Retention (NRR)
```
NRR = (Starting MRR + Expansion - Contraction - Churn) / Starting MRR
```

**Benchmarks:**
- < 100% = Product-market fit issues
- 100-110% = Good
- 110-120% = Great
- 120%+ = Excellent (best-in-class)

---

## Example Calculation

### Inputs
| Variable | Value |
|----------|-------|
| Monthly ARPU | $1,000 |
| Gross Margin | 80% |
| Monthly Churn Rate | 2% |
| Blended CAC | $5,000 |

### Calculations
| Metric | Formula | Result |
|--------|---------|--------|
| Customer Lifetime | 1 / 0.02 | 50 months |
| LTV | $1,000 x 0.80 x 50 | $40,000 |
| LTV:CAC | $40,000 / $5,000 | 8:1 |
| CAC Payback | $5,000 / ($1,000 x 0.80) | 6.25 months |

### Assessment: STRONG UNIT ECONOMICS

---

## Sensitivity Analysis

Test how changes in key variables affect your economics:

| Scenario | Change | New LTV | New Payback | Assessment |
|----------|--------|---------|-------------|------------|
| Base case | -- | $40,000 | 6.3 months | Strong |
| Churn +50% | 2% -> 3% | $26,667 | 6.3 months | Moderate risk |
| CAC +50% | $5K -> $7.5K | $40,000 | 9.4 months | Manageable |
| Both negative | 3% churn, $7.5K CAC | $26,667 | 9.4 months | Watch closely |

## Rule of 40

```
Rule of 40 Score = YoY Growth Rate % + EBITDA Margin %
```

**Target: >= 40%**

| Stage | Typical Growth | Typical EBITDA | Rule of 40 |
|-------|---------------|----------------|------------|
| Seed/Series A | 100%+ | -50% | 50+ (growth-heavy) |
| Series B | 60-100% | -20% | 40-80 |
| Series C+ | 40-60% | 0-10% | 40-70 |
| Public | 20-30% | 20-30% | 40-60 |
