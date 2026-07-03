# ROI Calculator Template

Use this framework to build a customer-facing ROI calculator.

## Input Variables (Ask the Prospect)

| Variable | Your Label | Default Value | Unit |
|----------|-----------|---------------|------|
| Monthly ticket volume | "How many support tickets do you handle per month?" | 5,000 | tickets |
| Average cost per ticket | "What's your fully-loaded cost per ticket?" | $8 | USD |
| Percentage Tier-1 tickets | "% of tickets that are repetitive (password resets, FAQs)?" | 60% | percent |
| Number of support agents | "How many support agents do you have?" | 10 | FTE |
| Average agent salary | "Average fully-loaded agent salary" | $60,000 | USD/year |
| Current CSAT score | "Current customer satisfaction score" | 80% | percent |

## Calculated Outputs

### Cost Savings
```
Tickets Automated = Monthly Tickets x % Tier-1 x AI Resolution Rate (70%)
Monthly Savings = Tickets Automated x Cost Per Ticket
Annual Savings = Monthly Savings x 12
Agent Capacity Freed = Tickets Automated / Tickets Per Agent Per Month
```

### Revenue Impact
```
CSAT Improvement = New CSAT - Current CSAT
Retention Impact = CSAT Improvement x Correlation Factor (0.5% per 1% CSAT)
Revenue Protected = Annual Revenue x Retention Impact
```

### Total ROI
```
Total Annual Value = Cost Savings + Revenue Impact
Product Cost = [Your Product Annual Price]
ROI = (Total Annual Value - Product Cost) / Product Cost x 100
Payback Period = Product Cost / (Total Annual Value / 12)
```

## Example Output Table

| Metric | Value |
|--------|-------|
| Monthly Tickets Automated | 2,100 |
| Monthly Cost Savings | $16,800 |
| Annual Cost Savings | $201,600 |
| Agent Capacity Freed | 2.1 FTE |
| CSAT Improvement | +10 points |
| Annual Revenue Protected | $50,000 |
| **Total Annual Value** | **$251,600** |
| Product Investment | $24,000 |
| **ROI** | **948%** |
| **Payback Period** | **1.1 months** |

## Presentation Tips
1. Always show the math -- transparency builds trust
2. Use conservative estimates for AI resolution rates
3. Include sensitivity ranges (best case / expected / worst case)
4. Let prospects adjust inputs to match their reality
5. Export to PDF for sharing with buying committees
