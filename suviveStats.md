##  Stats Survival Cheatsheet: The No-BS Edition

### 1.   Big Picture
**What is stats really?**  
> A toolbox to help you make decisions when you’re unsure about something especially based on limited data.

---

### 2. Distributions

| Distribution       | Use When...                          | Notes                                         |
|--------------------|--------------------------------------|-----------------------------------------------|
| **Normal (Z)**     | You know the population SD, or large n (> 30) | Standard bell curve (mean = 0, SD = 1)         |
| **t-distribution** | Small n OR unknown population SD     | Flatter tails = more uncertainty              |
| **Binomial**       | Fixed # of trials + yes/no outcomes  | Like flipping coins                           |
| **Chi-squared**    | Testing independence / variance      | Used in crosstabs and model fit               |

---

### 3. Key Concepts

| Term                   | Translation                                |
|------------------------|--------------------------------------------|
| **Mean**               | Average                                    |
| **Median**             | Middle value                               |
| **Variance / SD**      | Spread / how far from the mean             |
| **Z-score**            | How many SDs from the mean (standardized)  |
| **P-value**            | How likely is this result under the null?  |
| **Test Statistic**     | The number you compare to a reference distribution |
| **Null Hypothesis**    | The "nothing going on" assumption          |
| **Alternative Hypothesis** | What you're trying to show             |
| **Confidence Interval**| Range where true value probably lies       |

---

### 4. Common Tests

| Test                  | When to Use                          | Notes                              |
|-----------------------|--------------------------------------|------------------------------------|
| **t-test**            | Compare means                        | Can be 1-sample or 2-sample        |
| **z-test**            | Large sample or known variance       | Rare in practice                   |
| **Chi-squared test**  | Categorical variables                | Tests independence or fit          |
| **ANOVA**             | Comparing more than 2 means          | Uses F-distribution                |
| **Regression (OLS)**  | Predict one variable from others     | Coefficients = effects             |
| **Logistic regression** | Binary outcome (0/1)               | Predict probability                |

---

### 5.  How Hypothesis Testing Works

1. **Set up H₀** (null) and **H₁** (alternative)  
2. Pick test + calculate **test statistic**  
3. Convert it to **p-value**  
4. Compare to alpha (usually 0.05)  
    - p < 0.05 → reject H₀  
    - p ≥ 0.05 → fail to reject H₀  

✅ **Rejecting H₀** = there’s likely an effect  
🚫 **Failing to reject** = not enough evidence (not the same as saying H₀ is true)

---

### 6.  How to Think About It

- **Small p-value = surprise** under the null → maybe H₀ is wrong  
- **Big test statistic = big difference** relative to noise  
- **CI includes 0?** Not significant (in regression)  
- **It’s all about surprise:** stats is just asking _"how weird is this if nothing is going on?"_

---

### 8. Common Mistakes

-  Confusing p-value with probability null is true  
-  Saying "fail to reject" means null is true  
-  Ignoring assumptions (e.g., normality)

---

Stats is hard because it's **about the limits of knowledge.**  
Now you're learning to reason under uncertainty, which is some PhD-level shit. But you got this!
