# README: Z-Test vs T-Test - A Practical Guide with NHANCES BMI Data Analysis  

## Overview  
This guide provides a comprehensive understanding of Z-Test and T-Test statistical methods using NHANCES BMI data. It includes exploratory data analysis, statistical test applications, and a comparison of the two methods. The focus is on practical implementation and mathematical concepts, making it suitable for academic and research purposes.

---

## 1. Exploratory Data Analysis (EDA)  
- **Convert XPT to CSV**: Transform the dataset into a CSV format.  
- **Filter Data**: Retain only relevant columns for analysis.  
- **Handle Missing Values**:  
    - Identify missing values.  
    - Apply Rubin's missing data theory:  
        - <5% missing: Minimal concern.  
        - 5–20% missing: Requires careful analysis.  
        - 20–30% missing: Serious concern.  
        - >50% missing: Often unacceptable.  
    - Reference: *Jakobsen et al. (2017)* - Guidelines for handling missing data.  

---

## 2. Z-Test  
- **Preliminary Steps**:  
    - Test normality using QQ plots and `skewness()`.  
    - Understand that standardization ≠ normalization.  
- **Z-Score Applications**:  
    - Locate data points.  
    - Detect outliers.  
- **Perform Z-Test**:  
    - One-sample, two-sample, and proportion tests.  
    - Use both manual calculations and built-in functions.  

---

## 3. T-Test  
- **Visualizations**: Compare normal vs. t-distributions.  
- **T-Score**: Locate data points within the distribution.  
- **Perform T-Test**:  
    - One-sample, independent two-sample, and paired-sample tests.  
    - Use manual calculations and built-in functions.  
    - Apply Levene's test for variance equality in independent two-sample tests.  

---

## 4. Z-Test vs. T-Test  
- **Confidence Intervals (CI)**: Highlight differences between Z-Test and T-Test.  
- **Implementation**:  
    - Use manual calculations and built-in functions to compute CI.  
    - Focus on mathematical concepts, not business insights.  
- **Key Takeaway**: Compactly explain and implement statistical methods.  

---

## 5. Practical Applications  
- **BMI Data Analysis**:  
    - Use NHANCES BMI data to demonstrate Z-Test and T-Test applications.  
    - Compare BMI values across different groups (e.g., gender, age).  
- **Hypothesis Testing**:  
    - Formulate null and alternative hypotheses.  
    - Interpret p-values and statistical significance.  

---

## 6. Tools and Libraries  
- **Python Libraries**:  
    - `pandas` for data manipulation.  
    - `numpy` for numerical computations.  
    - `scipy.stats` for statistical tests.  
    - `matplotlib` and `seaborn` for visualizations.  
- **Statistical Software**:  
    - Use tools like R or SPSS for additional analysis.  

---

## 7. Limitations and Assumptions  
- **Z-Test**:  
    - Requires a large sample size.  
    - Assumes population variance is known.  
- **T-Test**:  
    - Suitable for small sample sizes.  
    - Assumes data is approximately normally distributed.  

---

## 8. References  
- Jakobsen, J. C., Gluud, C., Wetterslev, J., & Winkel, P. (2017). When and how should multiple imputation be used for handling missing data in randomised clinical trials – a practical guide. *BMC Medical Research Methodology*.  
- Additional references on Z-Test and T-Test methodologies.  

---

## 9. Conclusion  
This guide provides a structured approach to understanding and implementing Z-Test and T-Test methods. By following the steps outlined, users can confidently analyze data and draw meaningful conclusions.

---
##  **📂[Statistics and Hypothesis Project List →](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/README.md)** 
