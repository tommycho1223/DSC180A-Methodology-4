---
title: DSC 180A Methodology Assignment 4
description: Task 2 – public page with reflections
---

# DSC 180A Methodology Assignment 4 – Task 2

**Name:** Tommy Li  
**Email:** wal016@ucsd.edu  
**Section / Mentor:** A14 / Tianhao Wang

---

## Reflection

### 1) What is the most interesting topic covered in your domain this quarter?
I think the grokking phenomenon is the most interesting topic covered in my domain this quarter because the phenomenon was discovered recently (in 2022).

### 2) Describe a potential investigation you would like to pursue for your Quarter 2 Project.
For quarter 2, I would like to investigate how different regularization strategies affect the onset of grokking. In particular, weight decay is known to be one of the strongest signals in the Power et al. paper, so I want to compare different weight decay schedules and magnitudes on the exact same algorithmic task to see how much it shifts the grokking transition point.

### 3) What is a potential change you’d make to the approach taken in your current Quarter 1 Project?
In my current quarter 1 project I focused mainly on reproducing the phenomenon — basically just “making grokking happen.” I didn’t invest enough time in systematically varying hyperparameters in a controlled way. If I were to redo Quarter 1, I would structure my experiments more rigorously using fixed seeds, controlled runs, logging all relevant variables, and running small hyperparameter sweeps instead of just testing values manually.

### 4) What other techniques would you be interested in using in your project?
Honestly, I'm not sure yet because I'm still studying the phenomenon. However, I would like to incorporate more interpretability techniques to understand why the model begins to generalize so abruptly. Some ideas include probing internal activations, computing similarity metrics between hidden layer representations pre-grokking vs. post-grokking, and possibly using probing classifiers to detect when the model is storing algorithmic structure.

---

_Last updated: {{ site.time | date: "%B %d, %Y" }}_
