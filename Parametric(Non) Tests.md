

## 🧪 **Parametric vs. Non-Parametric Tests**

These are two broad categories of statistical tests used depending on the type of data and the assumptions you can make about it.

---

### ✅ **Parametric Tests**
**Definition:**  
Parametric tests **assume** that your data comes from a specific distribution — usually a **normal distribution**. They also assume **homogeneity of variance** and use **interval or ratio scale** data.

**Main features:**
- Require strong assumptions about the population.
- More powerful **if assumptions are met**.
- Typically faster and more informative.

**Examples:**
| Test | Used For |
|------|----------|
| **t-test** | Comparing means of 2 groups.  
  - *e.g., independent t-test, paired t-test* |
| **ANOVA** | Comparing means of 3+ groups |
| **Pearson correlation** | Measures linear relationship between variables |
| **Linear regression** | Predicting a dependent variable based on one or more independent variables |

**When to use:**  
- Your data is **normally distributed**.
- You're working with **interval or ratio** level measurements (e.g., height, temperature).

---

### 🚫 **Non-Parametric Tests**
**Definition:**  
Non-parametric tests **don’t assume** a specific distribution. They're often used when data **violates parametric assumptions**, or when dealing with **ordinal or ranked** data.

**Main features:**
- Fewer assumptions → more flexible.
- Less powerful than parametric tests if assumptions for parametric tests are met.
- Suitable for **small sample sizes**, **skewed data**, or **ordinal data**.

**Examples:**
| Test | Used For |
|------|----------|
| **Mann-Whitney U test** | Non-parametric alternative to the independent t-test |
| **Wilcoxon signed-rank test** | Alternative to the paired t-test |
| **Kruskal-Wallis test** | Alternative to one-way ANOVA |
| **Spearman’s rank correlation** | Alternative to Pearson correlation |
| **Chi-square test** | For categorical data/frequency tables |

**When to use:**  
- Your data is **not normally distributed**.
- You have **ordinal data** or **ranked data**.
- Sample size is **small**.

---

### 🎯 Example Comparison:

**Scenario:** You're testing if a new study method improves test scores.

- If you have a large enough sample and the scores are **normally distributed**:
  ➤ Use a **paired t-test** (parametric).

- If the scores are **skewed**, or sample size is very **small**:
  ➤ Use a **Wilcoxon signed-rank test** (non-parametric).

---

### 📌 Quick Summary:

| Feature              | Parametric Test     | Non-Parametric Test     |
|----------------------|---------------------|--------------------------|
| Assumes distribution | Yes (e.g., normal)  | No                      |
| Data type            | Interval/ratio      | Ordinal/nominal         |
| Power                | Higher (if valid)   | Lower                   |
| Sample size          | Needs to be larger  | Can handle small samples |
| Flexibility          | Less                | More                    |

