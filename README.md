# Megashop Online - A/B Testing Project

## 📊 Project Description

In this project, you work as an analyst for an online store that has gathered a series of hypotheses on how to increase revenue. The goal is to prioritize these hypotheses, run an A/B test, and analyze the results to make informed decisions.

## 🎯 Objectives

### Part 1: Prioritize Hypotheses

1. **ICE Framework**:
   - Evaluate hypotheses using the **Reach**, **Impact**, **Confidence**, and **Effort** criteria.
   - Calculate the **ICE** score for each hypothesis and rank them based on priority.

2. **RICE Framework**:
   - Evaluate hypotheses using the same criteria plus effort.
   - Calculate the **RICE** score for each hypothesis and rank them based on priority.

3. Compare the results between the **ICE** and **RICE** frameworks.

### Part 2: A/B Test Analysis

1. **Cumulative Revenue Chart**: Visualization of the cumulative revenue by group.
2. **Cumulative Average Order Size Chart**: Analysis of the evolution of the average order size by group.
3. **Relative Difference in Average Order Size**: Visualization of the difference between groups A and B.
4. **Conversion Rate**: Calculate and visualize the daily conversion rate for each group.
5. **Scatter Plot of Orders Per User**: Analysis of the distribution of orders per user.
6. **Percentiles of Orders Per User**: Identification of anomalies in the number of orders.
7. **Scatter Plot of Order Prices**: Visualization of the distribution of order prices.
8. **Percentiles of Order Prices**: Identification of anomalies in prices.
9. **Statistical Significance Analysis**: Comparison of the conversion and order size differences between groups A and B.

## 📈 Results and Decisions

### Conversion and Order Size Analysis

- **Conversion Rate**: Group B showed a higher conversion rate (0.0310 vs. 0.0268), indicating that group B performs better in terms of conversion.

- **Average Order Size**: No statistically significant difference was observed in the average order size between the groups (p-value = 0.4041), suggesting that the differences in conversion are not driven by the order size.

### 💡 Decision

**Stop the test and consider group B as the leader**:  
Since group B has a significantly higher conversion rate and no significant changes in the order size, the decision is to conclude the test and consider group B as the leading group.

## 🏁 Conclusion

The A/B test analysis suggests that group B performs better in terms of conversion, justifying its consideration as the leading group, even though no significant changes in the order size were observed.
