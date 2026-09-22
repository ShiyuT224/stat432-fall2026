---
id: w05-st58-ai-debugging
title: "How can we check AI debugging advice?"
author: "Shiyu(Shirley) Tang (st58)"
---

While working on the KNN homework, my Quarto preview kept showing “Rendering.” The AI agent suggested that the distance calculations were too slow and recommended changing the code. However, running Quarto in the macOS terminal showed that the actual error was “object 'zip.train' not found.” The data had not been loaded during rendering.

This experience showed me that a plausible explanation is not enough to identify a coding problem. What information should we ask an AI agent to check before it suggests changes? How can we distinguish slow calculations from a failed render when the preview does not show an error?
