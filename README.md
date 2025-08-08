## DiagPower: Sample Size Planning for Diagnostic Accuracy Studies

Project for the [Public Health Hackathon'2025](https://bioinf.institute/hack2025) \(Kazakhstan, Almaty 8 – 10 August 2025\)  

### Aims and scopes

This project aims to develop an open-source R-based tool (as a Shiny app, package, or just script with functions) for the statistical planning of diagnostic accuracy studies using ROC curve analysis.  
ROC curves and AUC (Area Under the Curve) are widely used in public health and clinical epidemiology to assess diagnostic test performance. However, many researchers lack accessible tools to properly calculate required sample sizes, particularly when dealing with non-standard hypotheses or multiple testing corrections.

The proposed tool will allow users to:  
1. Estimate the sample size needed to detect whether an AUC exceeds a specified null value (not limited to AUC₀ = 0.5).  
2. Compare two AUCs with defined statistical power and significance levels.  
3. Adjust sample size calculations to control for multiple hypothesis testing (e.g., using FDR or Bonferroni correction).  
4. Calculate the sample size required to achieve a target width of 95% confidence intervals for sensitivity, specificity, PPV &amp; NPV.  

### Team members  
 - **Alexey Glazkov** *(Independent researcher)* &ndash; project leader
 - Anastasiia Kolos
 - Olga Potanina
 - Ekaterina Serova
 - Oleg Tarasov

### References  
- Hanley JA, McNeil BJ. [The meaning and use of the area under a receiver operating characteristic (ROC) curve](https://doi.org/10.1148/radiology.143.1.7063747). Radiology. 1982 Apr;143(1):29-36.
- DeLong ER, DeLong DM, Clarke-Pearson DL. [Comparing the areas under two or more correlated receiver operating characteristic curves: a nonparametric approach](https://doi.org/10.2307/2531595). Biometrics. 1988 Sep;44(3):837-45. PMID: 3203132.  
- Carter JV, Pan J, Rai SN, Galandiuk S. [ROC-ing along: Evaluation and interpretation of receiver operating characteristic curves](https://doi.org/10.1016/j.surg.2015.12.029). Surgery. 2016 Jun;159(6):1638-1645.

