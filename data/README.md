# Dataset Information

## Dataset
Diabetes Health Indicators Dataset

## Original source
2015 Behavioral Risk Factor Surveillance System (BRFSS)

## Derived dataset source
Kaggle - Alex Teboul

https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## File used
diabetes_binary_5050split_health_indicators_BRFSS2015.csv

## Expected structure
- 70,692 observations
- 21 predictor variables
- 1 binary target variable: `Diabetes_binary`
- Balanced outcome: 35,346 class 0 and 35,346 class 1

## Analytical considerations
The dataset is cross-sectional and based on self-reported health indicators.

The binary outcome combines reported prediabetes/diabetes into the positive class.

The 50:50 class distribution is artificially balanced and does not represent population diabetes prevalence. Prevalence-sensitive metrics must therefore be interpreted cautiously.

The dataset does not contain a unique respondent identifier, so identical rows should not automatically be assumed to represent duplicate respondents.

## Data availability
The dataset itself is not redistributed through this repository. It can be obtained from the Kaggle source above.
