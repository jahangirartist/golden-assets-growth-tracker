# Formula reference

Every calculation in the Growth Tracker, its rule of thumb, the tab where it is calculated and the method it is credited to. The same table sits in the workbook's **Formula Sheet** tab.

| Metric | Formula | Rule of thumb | Calculated in | Method credit |
|---|---|---|---|---|
| Net Promoter Score | % promoters (9–10) − % detractors (0–6), 0–10 scale | ≥ 50 before pushing growth | NPS & PMF | Fred Reichheld, Bain & Company (2003) |
| PMF survey | Very disappointed ÷ PMF responses | ≥ 40% | NPS & PMF | Sean Ellis |
| ICE score | Impact + Confidence + Ease (1–10 each) | Work from the highest score down | Experiments | Sean Ellis |
| Improvement vs baseline | Result ÷ baseline − 1, sign flipped when lower is better | Positive = better | Experiments | Standard experiment analysis |
| Customers at end | Start + new + recaptured − lost | — | Monthly Metrics | Standard customer bridge |
| Customer churn % | Customers lost in month ÷ customers at start | < 2% monthly | Monthly Metrics | Standard retention metric |
| Recapture rate | Recaptured ÷ lost customers | — | Monthly Metrics | Standard retention metric |
| Recurring revenue at end | Start + new + expansion − contraction − churned | — | Monthly Metrics | Standard subscription finance |
| Net new recurring revenue | End − start recurring revenue | Positive and rising | Monthly Metrics | Standard subscription finance |
| Net revenue retention (monthly) | (Start + expansion − contraction − churned) ÷ start | ≥ 100% | Monthly Metrics | Standard subscription finance |
| Net revenue retention (annualised) | Monthly NRR ^ 12 | Compare with published annual NRR | Monthly Metrics | Standard subscription finance |
| ARPU | Recurring revenue at end ÷ customers at end | — | Monthly Metrics | Standard subscription finance |
| CAC — fully loaded | (Channel spend + team, tools & agency) ÷ new customers | ≈ one-third of CLV | Monthly Metrics | Standard unit economics |
| CAC — paid, by channel | Channel spend ÷ customers from that channel (last 12 months) | Compare against CLV | Channels | Standard unit economics |
| CLV | ARPU × gross margin % ÷ monthly churn | CLV : CAC ≥ 3 | Monthly Metrics | Standard unit economics |
| CAC payback | CAC ÷ (ARPU × gross margin %) | ≤ 12 months | Monthly Metrics | Standard unit economics |
| Avg customer lifetime | 1 ÷ monthly churn | 2% churn → ~50 months | Monthly Metrics | Standard retention metric |
| Activation rate | Activated new customers ÷ new customers | — | Monthly Metrics | AARRR — Dave McClure (2007) |
| Referral share | Customers from referrals ÷ new customers | — | Monthly Metrics | AARRR — Dave McClure (2007) |
| OKR progress | (Current − start) ÷ (target − start), capped 0–100% | Stretch ≈ 50% confidence | North Star & OKRs | OKRs — Andy Grove (Intel); popularised by John Doerr |
| Cohort retention | Active in month N ÷ cohort size | Curve should flatten | Cohorts | Standard cohort analysis |
| Week → month roll-up | Each week counts in the month that contains its 4th day; month total = sum of its weeks | 4 or 5 weeks a month | Weekly Metrics → Monthly Metrics | 4-4-5 retail calendar convention |
| Financial-year totals | Sum of months with data from the FY start month (Settings C15) for 12 months | Check months with data | Yearly Summary | Standard management reporting |
| Annualised churn | 1 − (1 − average monthly churn) ^ 12 | 2% a month ≈ 22% a year | Yearly Summary | Standard retention metric |

Rules of thumb are starting points, not targets. Set your own in the **Settings** tab.
