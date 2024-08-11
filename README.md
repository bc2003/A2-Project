# Loan Approval Amount Analysis

❔This project aimed to explore what predictor variables were most significant in predicting for the monetary value of approved loans. All analytics and visualizations were done using R (especially ggplot2).

Key Findings:
* 💵 annual income, credit score, and loan term proved to be most significant in determining the amounts of approve loans
* 🚩avoided multicollinearity via VIF and correlation heatmaps, finding out that the total value of any type of assets owned did not play a significant role in determining approved loan size
* ✅ fitted a logistic regression model to improve our model's fit, determined via model diagnostics (QQ plots, residual vs leverage plots, etc.)
