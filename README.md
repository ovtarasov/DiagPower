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
- Carter JV, Pan J, Rai SN, Galandiuk S. [ROC-ing along: Evaluation and interpretation of receiver operating characteristic curves](https://doi.org/10.1016/j.surg.2015.12.029). Surgery. 2016 Jun;159(6):1638-1645.
- DeLong ER, DeLong DM, Clarke-Pearson DL. [Comparing the areas under two or more correlated receiver operating characteristic curves: a nonparametric approach](https://doi.org/10.2307/2531595). Biometrics. 1988 Sep;44(3):837-45.  
- Hanley JA, McNeil BJ. [The meaning and use of the area under a receiver operating characteristic (ROC) curve](https://doi.org/10.1148/radiology.143.1.7063747). Radiology. 1982 Apr;143(1):29-36.  
- Hanley JA, McNeil BJ. [A method of comparing the areas under receiver operating characteristic curves derived from the same cases](https://doi.org/10.1148/radiology.148.3.6878708). Radiology. 1983 Sep;148(3):839-43.  
- Obuchowski NA, McClish DK. [Sample size determination for diagnostic accuracy studies involving binormal ROC curve indices](https://doi.org/10.1002/(SICI)1097-0258(19970715)16:13%3C1529::AID-SIM565%3E3.0.CO;2-H). Stat Med. 1997 Jul 15;16(13):1529-42.
- Obuchowski NA. [Sample size calculations in studies of test accuracy](https://doi.org/10.1177/096228029800700405). Stat Methods Med Res. 1998 Dec;7(4):371-92.  
- Obuchowski NA, Lieber ML, Wians FH Jr. [ROC curves in clinical chemistry: uses, misuses, and possible solutions](https://doi.org/10.1373/clinchem.2004.031823). Clin Chem. 2004 Jul;50(7):1118-25.  
