# A/B Testing Experiment: Conversion Rate Uplift

## Objective
Evaluate whether a new product experience (treatment) increases conversion rate compared to the existing experience (control).

## Experiment Design
- Randomized A/B test with 50/50 traffic split
- ~20,000 users
- Primary metric: Conversion rate
- Secondary metrics: Time to convert, 7-day retention

## Results
- Treatment conversion rate ≈ 10%
- Control conversion rate ≈ 7.6%
- Absolute uplift ≈ +2.4%
- Bootstrap 95% confidence interval excludes zero

## Evidence
Visual outputs in the `figures/` directory include:
- Conversion rate comparison with confidence intervals
- Bootstrap distribution of the conversion rate difference
- Time-to-conversion comparison

## Summary Metrics
A summary table comparing control and treatment groups (sample size, conversion rate, retention, and average sessions) is available in:

`figures/summary_metrics_table.png`

## Conclusion
The treatment outperformed the control with statistically significant uplift. A staged rollout is recommended while continuing to monitor retention and downstream engagement.
