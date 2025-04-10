##  Morphine Pain Perception Study

This project explores the **effect of morphine dosage on pain perception** using a statistically sound experimental design and rigorous analysis in R.

###  Objective
Investigate whether increasing levels of morphine significantly change a participant’s pressure pain threshold using simulated patient data from the *Islands* platform.

###  Study Design
-  **Randomized Block Design**  
-  **Factors**:
  - **Dosage** (0mg, 20mg, 40mg, 60mg)  
  - **Blocks**: Gender (2 levels) and Age Group (3 levels)
-  **Sample Size**: 192 participants  
-  **Response Variable**: Pain threshold before and after morphine treatment  

###  Methods
-  Two-Way ANOVA via `aov()` in R  
-  Tukey’s HSD for post-hoc comparisons  
-  Boxplots & residual diagnostics  
-  Power analysis using G*Power  

###  Findings
-  No statistically significant differences in pain tolerance across morphine dosage levels  
-  Neither age nor gender showed a significant effect  
-  Diagnostic plots indicated some non-normality and heteroscedasticity — suggesting caution when interpreting ANOVA results  

###  Tools Used
- `R`: dplyr, ggplot2, base stats  
- `G*Power`: for sample size justification  


