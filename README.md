# The Error Theorem | Conservation of Uncertainty

Welcome to the official repository for the **Error Theorem**. 

This project explores a fundamental principle of probability: that uncertainty is a measure of information, not just a count of available physical options. Originally formulated in 2025, this theorem provides a rigorous framework for understanding why "blind" eliminations do not yield probabilistic gains.

## 📌 The Concept

The Error Theorem posits that the physical removal of an alternative in a multiple-choice scenario only reduces uncertainty if the removal process is **informative** - meaning it carries a non-zero correlation with the correct answer.

### The Theorem
\begin{theorem}[The Error Theorem]
In a multiple-choice question with $n$ equiprobable alternatives, the elimination of an option only alters the probability of success if that elimination is informative (i.e., it carries a correlation with the correct answer). 

If the elimination occurs at random, or without any knowledge of which alternative is true, there is no real probabilistic gain: the total probability of success remains:

$P = \frac{1}{n}$.

In particular, the apparent transition from $n$ to $n-1$ alternatives does not, by itself, constitute a reduction in uncertainty; it only does so when it introduces new information into the system.
\end{theorem}

**You can see a demonstration and a better discuss of this teorem above in the .pdf.**

## 🧪 Theoretical Foundation

This repository validates the hypothesis through three main pillars of modern information science:

1.  **The Monty Hall Variant:** An analysis of how "intentionality" vs. "accidental" elimination (e.g., the *Monty Fall* scenario) dictates the collapse of probabilities.
2.  **Shannon Entropy:** A demonstration that Mutual Information $I(X; Y)$ must be greater than zero for the system's entropy to decrease.
3.  **Fisher Information:** Exploring how an estimator's precision only improves when observed data is sensitive to changes in the underlying truth.

## 📊 Visualizations & Animations

The goal of this repository is to make these abstract concepts tangible through:

* **Monte Carlo Simulations:** Interactive charts showing the convergence of success rates in "Blind" vs. "Informed" elimination scenarios.
* **Entropy Heatmaps:** Visual representations of uncertainty distribution across the sample space.
* **Interactive Playground:** A tool where users can adjust $n$, simulate eliminations, and see the Bayesian update in real-time.

## 🛠️ Tech Stack

* **Python:** Core statistical engine.

---
Developed by [davisilva169](https://github.com/davisilva169)
