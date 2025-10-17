# Introduction

In this project, the goal is to build a model that accurately predicts the recovery of gold in different stages of the extraction process from mined ore. The dataset contains information about various parameters collected during the technological stages of gold processing:flotation and purification. The focus is to analyze the data, verify the calculations, handle missing values, and develop a model that can predict gold recovery efficiently. The evaluation metric used is sMAPE (symmetric Mean Absolute Percentage Error), designed to account for both absolute and relative differences between predicted and actual values.

# Purpose
To develop a regression model which predicts the gold recovery by using the data gathered at different stages of the gold extraction process.

# Data

## Description of data

- date: exact datetime value of the gold extraction process to be carried out

Other columns are named with the format [stage].[parameter_type].[parameter_name]

*Possible values for [stage]*

- rougher: flotation
- primary_cleaner: primary purification
- secondary_cleaner: secondary purification
- final: final characteristics

*Possible values for [parameter_type]*

- input: raw material parameters
- output: product parameters
- state: parameters characterising the current state of the stage
- calculation: calculation characteristics

*Possible values for [parameter_name]*

- _air: volume of air
- _level: fluid level
- feed_size: size of the feed particle
- feed_rate: feeding speed
- concentrate_: percentage of the substance in the concentrate
- tail_: percentage of the substance in the rougher tails
- recovery - gold recovery in percentage

**Targets**

- rougher.output.recovery
- final.output.recovery

# Main Libraries Used

Pandas, Numpy, Statsmodels, Matplotlib, Seaborn, Scikit-Learn, XGBoost, CatBoost, LightGBM, Optuna