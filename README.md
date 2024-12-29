# Public Transportation Analysis

### Author: Sagar James, 2348050

---

## Project Overview

This project analyzes satisfaction levels of public transportation users based on their usage frequency, type of transport used, and age. The study uses statistical tests such as t-tests, one-way ANOVA, and correlation analysis, along with visualizations to explore relationships in the data.

---

## Objectives

### 1. Identify differences in satisfaction levels between daily users and non-daily users.
- **Test Used:** Welch Two-Sample t-test
- **Hypotheses:**
  - **Null Hypothesis (H₀):** No significant difference in satisfaction levels between daily and non-daily users.
  - **Alternative Hypothesis (H₁):** A significant difference exists in satisfaction levels between the two groups.

### 2. Analyze satisfaction levels based on the type of public transport used (Bus, Metro, Auto-rickshaw).
- **Test Used:** One-Way ANOVA
- **Hypotheses:**
  - **Null Hypothesis (H₀):** No significant difference in satisfaction levels across transport types.
  - **Alternative Hypothesis (H₁):** A significant difference exists in satisfaction levels across transport types.

### 3. Examine the relationship between age and satisfaction levels with public transport.
- **Test Used:** Correlation analysis and linear regression.
- **Objective:** Identify the strength and direction of the relationship.

---

## Dataset

- The dataset contains survey responses collected from public transport users. The columns include:
  - Usage frequency
  - Transport type
  - Ratings on availability, punctuality, cleanliness, safety, cost, comfort, and staff behavior
  - Overall satisfaction level
  - Demographics (e.g., age)

---

## Statistical Methods

1. **T-Test (Objective 1):**
   - Compares satisfaction levels between daily and non-daily users.
   - Result: p-value > 0.05, indicating no statistically significant difference.

2. **One-Way ANOVA (Objective 2):**
   - Compares satisfaction levels across transport types.
   - Result: p-value < 0.05, indicating significant differences among transport types.

3. **Correlation Analysis (Objective 3):**
   - Examines the relationship between age and satisfaction levels.
   - Result: Weak positive correlation (r ≈ 0.2222).

---

## Visualizations

1. **Bar Plot:**
   - Shows average satisfaction levels by transport type.
2. **Scatter Plot:**
   - Displays the relationship between age and satisfaction levels, including a regression line.

---

## Instructions to Run the Project

1. **Prerequisites:**
   - Install R and RStudio (or any R-compatible IDE).
   - Ensure the required libraries are installed:
     ```r
     install.packages(c("ggplot2", "corrplot"))
     ```

2. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
