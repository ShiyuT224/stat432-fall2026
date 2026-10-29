---
id: w10-st58-oob-tuning
title: "Can tuning make OOB error too optimistic?"
author: "Shiyu(Shirley) Tang (st58)"
---

In this homework, we selected mtry and node size by comparing OOB misclassification rates. Although each observation is evaluated using trees that did not include it in training, its label still influences which parameter combination we select. Could searching many parameter combinations make the lowest OOB error overly optimistic? How does the size of the tuning grid affect this risk, and when should we use a separate validation set or nested cross-validation instead?
