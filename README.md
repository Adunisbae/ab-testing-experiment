# A/B Testing Experiment: Conversion Rate Uplift

## Objective
Evaluate whether a new product experience (treatment) increases conversion rate compared to the existing experience (control).

## Experiment Design
- Randomized A/B test (50/50 split)
- ~20,000 users
- Primary metric: Conversion rate
- Secondary metrics: Time to convert, 7-day retention

## Results
- Treatment conversion rate ≈ 10%
- Control conversion rate ≈ 7.6%
- Absolute uplift ≈ +2.4%
- Bootstrap 95% confidence interval excludes zero

## Evidence
The plots in the `figures/` folder show:
- Conversion rate comparison with confidence intervals
- Bootstrap distribution of conversion rate difference
- Time-to-conversion comparison

## Summary Metrics

The table below summarizes key experiment metrics across control and treatment groups, including sample size, conversion rate, retention, and average sessions.

See `figures/summary_metrics_table.png`.

## Conclusion
The treatment outperformed the control with statistically significant uplift. A staged rollout is recommended while monitoring retention.
