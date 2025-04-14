### 📘 **Bayesian Approach — Theoretical Definition**

> **The Bayesian approach** is a framework for statistical inference in which all forms of uncertainty are expressed in terms of probability. It combines prior beliefs about unknown parameters with evidence from observed data using **Bayes’ Theorem** to produce a posterior distribution, which represents the updated beliefs after considering the data.

---

### **Bayes’ Theorem**

$$
P(\theta \mid \text{data}) = \frac{P(\text{data} \mid \theta) \cdot P(\theta)}{P(\text{data})}
$$

Where:
- $P(\theta)$ = **Prior**: belief about the parameter before seeing the data  
- $P(\text{data} \mid \theta)$ = **Likelihood**: how likely the data is, given the parameter  
- $P(\theta \mid \text{data})$ = **Posterior**: updated belief after seeing the data  
- \$P(\text{data})$ = **Evidence**: normalizing constant to ensure probabilities sum to 1

---

### 🔍 Summary:

The Bayesian approach treats unknown parameters as random variables and **updates beliefs as new data becomes available**, providing a coherent and consistent way to reason under uncertainty.
