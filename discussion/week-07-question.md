---
id: w07-st58-cv-model-selection
title: "Should we pick the lowest CV error?"
author: "Shiyu(Shirley) Tang (st58)"
---

In the SAheart analysis for Homework 7, I compared 27 LDA
and QDA candidates using the same five cross-validation
folds. QDA with five principal components had the lowest
CV error (24.7%), but its test error was 28.8%. Several
other models had similar CV errors.

When many models are compared, the lowest CV error may
be partly due to chance. Should we choose the model with
the lowest CV error, or use the one-standard-error rule
to choose a simpler model? How can we tell which approach
is more reliable?
