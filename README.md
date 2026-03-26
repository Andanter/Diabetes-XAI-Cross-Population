# Diabetes-XAI-Cross-Population

Using Explainable AI to understand Cross population Differences in Diabetes Risk Prediction using German and Uganda survey data. 

This repository contains the code, notebooks and supporting materials for this thesis. 

**Project Overview**

This project investigates whether diabetes risk prediction models and their explanations remain reliable when transferred across populations. The study uses:
1. BRFSS 2015 as a benchmark dataset
2. GEDA 2019/2020- EHIS as the main German dataset
3. Uganda STEPS 2014 as the main Ugandan dataset

The project focuses on:

- Internal validation within each dataset

- Bidirectional external validation between Germany and Uganda

- SHAP based explanation comparison

- Additionally, Class imbalance, false positives 

**Research Objectives**

- To construct harmonized diabetes prediction datasets across BRFSS, GEDA and Uganda STEPS
- To evaluate internal predictive performance within each dataset
- To assess external transferability between Germany and Uganda
- To compare SHAP feature importance across internal and external settings

**Final harmonized predictors**

The final shared feature set used in the study is:

- age
- sex
- BMI
- hypertension
- current smoking
- physical activity

Alcohol was initially considered but removed from the final shared set because of high missingness in the Uganda dataset. 

**Repository structure**

- README.md
- requirements.txt
- .gitignore
- notebooks/
- data/
- outputs/
- docs/
