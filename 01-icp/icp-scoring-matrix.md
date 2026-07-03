# ICP Scoring Matrix

Use this framework to score and prioritize leads/target accounts.

## Scoring Dimensions

| Dimension | Weight | Description | Score 1-10 |
|-----------|--------|-------------|------------|
| **Firmographic Fit** | 25% | Employee count, industry, revenue match | ___ |
| **Technographic Fit** | 20% | Tech stack compatibility, API readiness | ___ |
| **Behavioral Intent** | 20% | Content engagement, trial activity, demo requests | ___ |
| **Pain Signal Strength** | 20% | Job postings, support volume, public complaints | ___ |
| **Timing & Budget** | 15% | Funding events, fiscal calendar, budget cycles | ___ |

## Scoring Guide

### Firmographic Fit (25%)
| Score | Criteria |
|-------|----------|
| 10 | Perfect match on all firmographic criteria |
| 7-9 | Matches 2-3 key criteria |
| 4-6 | Partial match, needs validation |
| 1-3 | Poor fit, unlikely to convert |

### Technographic Fit (20%)
| Score | Criteria |
|-------|----------|
| 10 | Uses complementary tools; API-ready infrastructure |
| 7-9 | Uses one compatible tool; moderate tech maturity |
| 4-6 | Legacy stack; integration would require work |
| 1-3 | Incompatible tech stack |

### Behavioral Intent (20%)
| Score | Criteria |
|-------|----------|
| 10 | Multiple touchpoints; pricing page visits; trial active |
| 7-9 | Downloaded content; attended webinar |
| 4-6 | Single content download; email open |
| 1-3 | No known engagement |

### Pain Signal Strength (20%)
| Score | Criteria |
|-------|----------|
| 10 | Public complaints; rapid hiring; recent escalation |
| 7-9 | Job postings; industry forum mentions |
| 4-6 | Generic growth signals |
| 1-3 | No pain signals detected |

### Timing & Budget (15%)
| Score | Criteria |
|-------|----------|
| 10 | Just raised funding; new leadership; Q1 budget |
| 7-9 | End of fiscal year; known budget cycles |
| 4-6 | Steady state; no timing signals |
| 1-3 | Budget frozen; recent layoffs |

## Weighted Score Calculation

```
Weighted Score = (Firmographic x 0.25) + (Technographic x 0.20) + 
                 (Behavioral x 0.20) + (Pain Signal x 0.20) + 
                 (Timing x 0.15)
```

## Priority Buckets

| Score Range | Priority | Action |
|-------------|----------|--------|
| 8.0 - 10.0 | A (Hot) | Immediate outreach; AE assignment |
| 6.0 - 7.9 | B (Warm) | Nurture sequence; SDR follow-up |
| 4.0 - 5.9 | C (Cool) | Marketing nurture; long-term drip |
| 0 - 3.9 | D (Cold) | Deprioritize; revisit quarterly |
