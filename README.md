🏈 NFL Quarterback Correlations (2019–2023)
📌 Project Overview

This project analyzes NFL quarterback performance from 2019–2023, focusing on two key relationships:

Yards After Catch (YAC) vs Passing First Downs

Passing Attempts vs Interceptions

By applying Pearson and Spearman correlation methods, the project explores how passing efficiency and volume contribute to offensive outcomes — and the tradeoffs QBs face between production and turnovers.

📊 Methods

Data Source: nflverse
 R package (player-level stats, 2019–2023).

Tools: R, ggplot2, gt, flextable, regclass.

Analysis:

Pearson correlation for linear relationships.

Spearman correlation for monotonic (non-linear) relationships.

Visualizations with scatterplots, LOESS curves, and histograms.

📈 Results
🔹 Yards After Catch vs Passing First Downs

Strong positive correlation (Pearson).

Insight: Accurate QB ball placement enabling receivers to gain YAC is a key driver of sustained drives.

🔹 Passing Attempts vs Interceptions

Moderate positive correlation (Spearman).

Insight: Higher passing volume is associated with more interceptions, reflecting both game scripts (trailing teams throwing more) and increased defensive pressure.

🔹 QB Passing Yards Distribution

Histogram confirms large variation in QB passing production across seasons.

🏟️ Football Insights

Efficiency matters: More YAC → more first downs → longer drives.

Volume carries risk: More attempts → more interceptions, especially in high-pressure or losing game situations.

Beyond raw totals: QB evaluation should blend volume and efficiency metrics.

🚀 Next Steps

Add additional QB metrics (completion %, TDs, sack rate).

Build a multiple regression model to predict first downs.

Compare rookies vs veterans to see how experience impacts efficiency.

📂 Files in Repo

NFL_QB_Correlations.Rmd → RMarkdown analysis file.

NFL_QB_Correlations.html → Knitted report.

README.md → Project overview (this file).

👤 Author

Andrew Gentilcore — Senior at the University of Tennessee, Knoxville
🎯 Focus: NFL & sports analytics, regression modeling, and data-driven football insights
