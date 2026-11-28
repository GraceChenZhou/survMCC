# survMCC 0.2.0

* Initial CRAN submission.
* Implements Mean Cumulative Count (MCC) estimation for recurrent event data in
the presence of competing risks (Dong et al., 2015), with support for
left-truncated (delayed-entry) data via time-dependent censoring and
truncation weights (Geskus, 2011).
* Provides subject-level bootstrap confidence intervals, S3 `summary()`,
`plot()`, and `as.data.frame()` methods, aligned number-at-risk table
plotting via `plot_mcc_with_risk_table()`, and cohort simulation helpers
(`simulate_subject()` and `simulate_mcc_data()`).
