# PLG Funnel Metrics Framework

## The Product-Led Growth Funnel

### Stage 1: Acquisition
| Metric | Definition | Benchmark |
|--------|------------|-----------|
| Website-to-Signup Rate | % of visitors who create account | 5-15% |
| Signup-to-Activation Rate | % of signups who reach "aha" moment | 30-50% |
| Channel Mix | Organic vs Paid vs Referral vs Viral | Varies by stage |

### Stage 2: Activation
| Metric | Definition | Benchmark |
|--------|------------|-----------|
| Time to First Value | Hours/days to first meaningful action | < 1 day |
| Activation Rate | % completing key activation events | 40-60% |
| Feature Adoption Breadth | Number of features used in first week | 3+ features |

**Define your activation events:**
- Primary: [e.g., First AI resolution completed]
- Secondary: [e.g., Integration connected]
- Tertiary: [e.g., Team member invited]

### Stage 3: Engagement
| Metric | Definition | Benchmark |
|--------|------------|-----------|
| DAU/MAU Ratio | Daily active / Monthly active users | 20-40% |
| Feature Usage Frequency | Core actions per user per week | 3-5x |
| NPS Score | Net Promoter Score | 30+ |

### Stage 4: Conversion
| Metric | Definition | Benchmark |
|--------|------------|-----------|
| Trial-to-Paid Rate | % of trials converting to paid | 15-35% |
| Conversion Time | Days from signup to first payment | 14-30 days |
| Expansion Revenue | Upsell/cross-sell within first 90 days | 10-20% of initial |

### Stage 5: Retention
| Metric | Definition | Benchmark |
|--------|------------|-----------|
| Logo Retention | % of customers retained YoY | 85-95% |
| Net Revenue Retention | NRR including expansion/contraction | 110-130% |
| Gross Revenue Retention | Retention without expansion | 85-95% |

---

## Sales-Assist Trigger Framework

### PQL (Product Qualified Lead) Scoring

| Signal | Points | Threshold |
|--------|--------|-----------|
| Team size > 5 | +20 | -- |
| Integration connected | +15 | -- |
| 100+ core actions | +25 | -- |
| Invited team members | +10 each | -- |
| Visited pricing page | +10 | -- |
| Used advanced feature | +15 | -- |
| **Total for Sales Handoff** | **> 70** | **Trigger AE outreach** |

### Automated Sales-Assist Workflow

```
IF PQL_score > 70 AND company_size > 200:
    -> Assign to Enterprise AE
    -> Schedule demo within 24 hours
    -> Send personalized video

IF PQL_score > 70 AND company_size < 200:
    -> Assign to Product Specialist
    -> Offer guided onboarding call
    -> Monitor for 14 days

IF PQL_score 40-70:
    -> Add to nurture sequence
    -> Trigger in-app prompts
    -> Weekly automated tips

IF PQL_score < 40:
    -> Self-serve only
    -> Automated lifecycle emails
    -> Re-evaluate in 30 days
```
