---
id: w03-st58-ai-column-name
title: Why Did a Wrong Column Name Cause a Matrix Error?
author: Shiyu(Shirley) Tang (st58)
---

I asked an AI tool for simple R code to run ten-fold cross-validation for ridge regression. The code used `train$fold`, but the actual column was named `cv_fold`. Running the code produced a `system is exactly singular` error from `solve()`. Checking `head(folds)` revealed the mismatch, and I corrected the column name.

Why did a wrong column name lead to a matrix error instead of a clear missing-column error? What simple checks should we add to catch this kind of problem before fitting the models?
