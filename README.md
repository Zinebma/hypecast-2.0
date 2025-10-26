# HypeCast 2.0 — CodeWords Hackathon (Non-commercial)

**Purpose:** A forecasting + action-pack tool that aggregates public signals
(YouTube velocity, GitHub stars, Google Trends; optional Adzuna job counts/salary)
to score the near-term “hype” of skills/topics. Outputs include a one-slide
scorecard PNG, a creator carousel, and play-money predictions (no real currency).

**Adzuna usage (if approved):**
We call `/v1/api/jobs/{country}/search` with `what=<skill>` and `max_days_old=7`
to compute **jobs_7d_count** and **median_salary**. We store *aggregates only*
(no republishing of full ads) and show Adzuna attribution + link.

**Compliance:** Play-money only, non-redeemable; no user PII beyond Discord ID.

This is a **hackathon demo**, not for commercial use.

