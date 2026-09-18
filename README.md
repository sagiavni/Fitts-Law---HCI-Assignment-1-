Fitts' Law — HCI Assignment

AI-assisted Fitts' Law experiment simulating a driver reaching a center-console touchscreen, with a divided-attention hazard-light task added as the design's Innovation.

-Live app: https://sagiavni.github.io/Fitts-Law---HCI-Assignment-1-/ 
-Full report: https://sagiavni.github.io/Fitts-Law---HCI-Assignment-1-/report.html

Contents
index.html — the experiment itself (single-file, zero external dependencies)
report.html — Scenario, Innovation, Application, empirical analysis, and the custom Fitts' Law formula
fitts_law_data.csv — raw trial data (27 trials)
scatter-plot.png — Movement Time vs. Index of Difficulty, with regression line
Summary

27 trials across a 3×3 amplitude/width matrix (250/500/750 px × 40/80/140 px), timed with performance.now(). A subset of trials included a concurrent road-hazard response task to model the divided attention of real driving. Fitted equation (n = 27): MT = 595.9 + 97.1 · ID, R² = 0.139 — full analysis, including why the fit improves to R² = 0.468 once hazard trials are isolated, is in the report.

  Sagi Avni · Human-Computer Interaction
