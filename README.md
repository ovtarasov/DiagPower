## DiagPower: Sample Size Planning for Diagnostic Accuracy Studies

# To run DiagPower:
1. Open the [`Repo.pdf`](path/to/Repo.pdf) file from this repository on your computer. 
2. Click the "here" button inside the section titled *"To run our DiagPower app click here"*
3. Wait for the Shiny app to load (may take 2-30 seconds initially)
4. Consult resources:
   - [`Parameter_guide.pdf`](path/to/Parameter_guide.pdf) - comprehensive descriptions
   - [`Q&A.md`](path/to/Q&A.md) - frequently asked questions
5. Reload DiagPower via [`Repo.pdf`](path/to/Repo.pdf) if the session times ouе


# Troubleshooting

# App won't launch
- Ensure you have:
  - Stable internet connection
  - PDF reader that supports hyperlinks (Adobe Acrobat recommended)
  - Pop-ups not blocked in your browser

# Error messages
| Error | Solution |
|-------|----------|
| "Application disconnected" | Refresh the page |
| "502 Bad Gateway" | Wait 2 minutes and reload |
| Blank screen | Clear browser cache |

# Session timeout
The app automatically disconnects after 30 minutes of inactivity. To resume:
1. Close the browser tab
2. Reopen from [`Repo.pdf`](path/to/Repo.pdf)


### Project description

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
- Kim E, Zhang Z, Wang Y, Zeng D. [Power calculation for comparing diagnostic accuracies in a multi-reader, multi-test design](https://doi.org/10.1111/biom.12240). Biometrics. 2014 Dec;70(4):1033-41. 
- Obuchowski NA, McClish DK. [Sample size determination for diagnostic accuracy studies involving binormal ROC curve indices](https://doi.org/10.1002/(SICI)1097-0258(19970715)16:13%3C1529::AID-SIM565%3E3.0.CO;2-H). Stat Med. 1997 Jul 15;16(13):1529-42.
- Obuchowski NA. [Sample size calculations in studies of test accuracy](https://doi.org/10.1177/096228029800700405). Stat Methods Med Res. 1998 Dec;7(4):371-92.  
- Obuchowski NA, Lieber ML, Wians FH Jr. [ROC curves in clinical chemistry: uses, misuses, and possible solutions](https://doi.org/10.1373/clinchem.2004.031823). Clin Chem. 2004 Jul;50(7):1118-25.  
- Grolleau F, Tibshirani R, Chen JH. [powerROC: An Interactive Web Tool for Sample Size Calculation in Assessing Models' Discriminative Abilities](https://arxiv.org/abs/2501.03155). AMIA Jt Summits Transl Sci Proc. 2025 Jun 10;2025:196-204. [GitHub](https://github.com/fcgrolleau/powerROC)   
- Riesthuis P, Otgaar H, Bücken C. [Ready to ROC? A tutorial on simulation-based power analyses for null hypothesis significance, minimum-effect, and equivalence testing for ROC curve analyses](https://doi.org/10.3758/s13428-025-02646-x). Behav Res Methods. 2025 Mar 18;57(4):120.

