# Day 4 schedule

Day 4 focus is biomedical applications.


1. Application of metabolomics to precision medicine


*15 minutes break*


2. Metabolite annotation and reporting

Important to the execution of research projects and writing scientific manuscripts.


3. Review of statistical analysis

- Group comparison
  - assuming normal distribution, use parametric tests
    - 2 groups, Student t-test
    - 2 groups, to include confounders, Logistic regression
    - more groups, ANOVA
  - not assuming distribution, use nonparametric tests
    - Mann Whitney U test
  - Shrinkage methods often used in specialized software tools for -omics

- Association with continuous variables
  - without accounting for confounders, use correlation methods
    - Pearson correlation
    - Spearman rank correlation
  - accounting for confounders, use generalized linear models for regression
    - multiple specialized regression methods, e.g. LASSO and Elastic Net, not covered here.

- FDR, FDR, FDR


*Lunch break*


4. Hand-on session on MWAS and data presentation

We will test the association of antibody response to metabolomic profile in the HZ vaccine study.

The data were prepared for this exercise:
  * HZ_antibody_day28v0.tsv
  * HZ_metabolomics_day0.tsv

In real world situations, one needs to wrangle the data to the correct formats. An example is provided as
  * day4_extra_reference_data_wrangling.html


*15 minutes break*


5. Participant project discussions

Live discussion of research projects from participants.
Please bring your own research questions.
