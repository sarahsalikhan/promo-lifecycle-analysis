# **Promo Lifecycle Analysis**


**📌 Project Overview**

This project explores how long the effects of promotions and price changes last before dissipating, using a combination of Difference-in-Differences (DiD) and Survival Analysis techniques. While DiD provides insights into the magnitude of the impact, Survival Analysis adds a time dimension, showing how quickly effects fade and whether they differ across regions or store characteristic.



**🎯 Objectives**

Quantify the overall impact of product launches, promotions, or price changes on traffic, sales, and profit.

Compare Difference-in-Differences and Survival Analysis to evaluate their effectiveness in capturing short-term vs. long-term impacts.

Provide decision-makers with deeper insights into how long promotional effects persist and where they vary across different markets.



**📊 Methodology**

1. Difference-in-Differences (DiD)

Measures average pre/post changes between test and control groups.

Provides a dollar-value estimate of impact.

Assumes effects are permanent shifts after the intervention.

2. Survival Analysis

Models the time until effects dissipate, e.g., when sales or traffic return to baseline.

Uses Kaplan-Meier survival curves and Cox Proportional Hazard models.

Captures decay rate of the treatment effect and allows comparison across regions and metrics (sales, profit, traffic).



**📂 Dataset**

Source: Restaurant-level data across multiple regions.

Metrics Analyzed:

Weekly Sales

Weekly Profit

Weekly Traffic

Treatment: Promotion or price change events.

Control: Comparable stores without intervention.



🔑 **Key Findings**

DiD showed average differences in performance but could not explain how long effects lasted.

Survival Analysis revealed:

Sales and profit maintained elevated levels for ~19 weeks before declining to 50% probability of survival.

Traffic dropped more sharply, showing faster dissipation compared to sales and profit.

Regional differences were significant — some regions saw long-term profit lifts, while others saw negative impacts.



🚀 **Applications**

Forecasting promotion lifecycles and planning marketing campaigns.

Identifying regions or store segments with sustained performance.

Supporting pricing and promotional strategy optimization.

Combining DiD and Survival Analysis to give businesses both magnitude and duration of effects.



🛠️ **Tools \& Technologies**

Python / R for statistical modeling

Kaplan-Meier curves for survival probabilities

Cox Proportional Hazard models for multivariate analysis

T-tests / Wilcoxon tests for statistical significance in DiD



📖 **References**

James, G., Witten, D., Hastie, T., \& Tibshirani, R. An Introduction to Statistical Learning. Springer.

Kaufman, J. (2020). The Personal MBA. Penguin.

Meisenzahl, M. (2022). Chicken Sandwich Wars. Business Insider.

Wiener-Bronner, D. (2023). CNN Reports on Restaurant Trends.

Castillo, A. (2023). Restaurant Spending and Traffic Reports.

