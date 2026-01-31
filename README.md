## Context

The National Collegiate Athletic Association (NCAA) basketball tournaments captivate millions of fans annually, showcasing the raw talent and strategic process of collegiate athletes, with a business ecosystem that pulsates billions of dollars through the veins of the American sports industry; the choice of analyzing a basketball dataset becomes then a great example of what a professional data scientist working for an NCAA team could do in their workdays.

In this project, we embark on a journey into the heart of college basketball analytics, driven by the conviction that data has the power to unlock new dimensions of understanding and transform the way we perceive and engage with the game.

## Tools and Models Used

- Exploratory Data Analysis (EDA): Descriptive statistics, plots and tests to understand distributions, variability, and data quality.
- Linear Regression (OLS): Modelling the relationship between Adjusted Offensive Efficiency and win ratio, including hypothesis testing and confidence intervals.
- Principal Component Analysis (PCA): Dimensionality reduction to uncover latent performance dimensions based on offensive and defensive playing-style metrics.
- Singular Value Decomposition (SVD): Used to validate PCA results and interpret dominant latent “talent” components.
- Anomalous Pattern Fuzzy C-Means Clustering (AP-FCM): Soft clustering employed to guide the choice of the optimal number of performance groups of teams.

## Main findings

- Offensive efficiency is a key driver of success: ADJOE explains over 60% of win ratio variance on its own.
- Outliers such as Indiana University highlight that strong offense alone is insufficient, as defensive metrics play a crucial complementary role.
- The effect of further stylistic differences on performance, such as inside vs. perimeter play, were revealed.
- Performance is best separated into two main performance groups, reflecting the difficulty of defining "average" teams beyond just "high-performing" and "low-performing" ones.
- Tournament outliers confirm that even robust data-driven models cannot fully capture the stochastic and situational nature of competitive basketball.

## Acknowledgments

I thank my colleague and friend [Matteo Saterini](https://github.com/Sateeee00) who worked with me on this project.
